# Adwise Magento 2 Dutch Language Pack (nl_NL)

Dutch Magento 2 translations for Magento 2 (CE), translated, optimized and maintained by Adwise - Your Digital Brain.

[![Latest Stable Version](https://poser.pugx.org/adwise/language-nl_nl/v/stable)](https://packagist.org/packages/adwise/language-nl_nl) [![Total Downloads](https://poser.pugx.org/adwise/language-nl_nl/downloads)](https://packagist.org/packages/adwise/language-nl_nl) [![Monthly Downloads](https://poser.pugx.org/adwise/language-nl_nl/d/monthly)](https://packagist.org/packages/adwise/language-nl_nl)

### Version
1.2.2

### Configure Magento backend
* Activate language (backend): Account > Settings > Account information > Interface Locale
* Activate language (frontend): Stores > Settings > Configuration > [storeview] > Locale options > Locale

### Installation (manual)
* Clone repository to ``app/i18n/adwise/nl_nl/`` 
* Upgrade Magento installation ``$ php bin/magento setup:upgrade``
* Clear Magento cache``$ php bin/magento cache:clean``
* Deploy Static Content ``$ php bin/magento setup:static-content:deploy nl_NL``

### Installation (Composer)
* Require via Composer CLI ``$ composer require adwise/language-nl_NL``
* Upgrade Magento installation ``$ php bin/magento setup:upgrade``
* Clear Magento cache``$ php bin/magento cache:clean``
* Deploy Static Content ``$ php bin/magento setup:static-content:deploy nl_NL``

### Roadmap
* Translate missing content (50% left)
* Optimize translations (in context for better experience)

### Bugs
There are still missing some translations, due to a bug in the i18n:collect-phrases method. More information about this bug can be found on: https://github.com/magento/magento2/issues/2630. This issue will be fixed in Magento CE 2.1.0 but is already fixed in develop branch.

Please report all bugs/optimizations in Github!

### More information
Visit out website for more information: http://www.adwise.nl/
