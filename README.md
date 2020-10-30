# MagentoCurrencyCBR
Magento 2: Currency converter to get rates from https://cbr.ru/

[Based on "krybbio" code](https://magento.stackexchange.com/a/228671/33058). 

```
$ composer require staskamyshov/magento-currency-cbr
$ ./bin/magento setup:upgrade
$ ./bin/magento deploy:mode:set developer
$ ./bin/magento deploy:mode:set production
```


## Uninstall

```
$ ./bin/magento module:disable EHC_MagentoCurrencyCBR
$ composer remove staskamyshov/magento-currency-cbr
```
