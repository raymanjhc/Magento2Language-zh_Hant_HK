##Installation (Composer Repo)

    * Require via Composer CLI $ composer require fd/language-zh_hant_hk
    * Upgrade Magento installation $ php bin/magento setup:upgrade
    * Clear Magento cache$ php bin/magento cache:clean
    * If necessary, Deploy Static Content $ php bin/magento setup:static-content:deploy zh_Hant_HK


##Installation for source control(Composer VCS) 

    * composer config repositories.language-zh_hant_hk vcs https://github.com/4dhk/Magento2Language-zh_Hant_HK.git
    * composer require fd/language-zh_hant_hk
    * php bin/magento cache:clean
    * If necessary, Deploy Static Content $ php bin/magento setup:static-content:deploy zh_Hant_HK 
