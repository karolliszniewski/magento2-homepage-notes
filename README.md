`vendor/magento/module-theme/view/frontend/page_layout/1column.xml` - header classes are here
`vendor/magento/module-theme/view/frontend/layout/default.xml` - panel wrapper





Update the COMPOSER_AUTH environment variable:

Locate where COMPOSER_AUTH is being set (it may be in your deployment scripts or environment configuration).
Update the credentials in COMPOSER_AUTH to match those in the auth.json file.
Redeploy after updating:

Since auth.json has the correct credentials and should override COMPOSER_AUTH, redeploying should apply the correct configuration.
This change ensures the credentials match, resolving any authentication issues with Magento's repo on deployment.



