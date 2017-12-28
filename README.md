# magento-2-norwegian-language-pack
Norwegian Language Pack for Magento 2 updated monthly

**Last updated**: 28 December 2017


## How to Install Norwegian Language Pack

Here are 2 methods to install this language pack.


### #1. Composer method
Install the Norwegian language pack via composer is never easier.

**Install Norwegian pack**:

```
composer require day4code/magento-2-norwegian-language-pack:dev-master
php bin/magento cache:clean
php bin/magento setup:static-content:deploy nn_NO
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```

**Update Norwegian pack**:

```
composer update day4code/magento-2-norwegian-language-pack:dev-master
php bin/magento cache:clean
php bin/magento setup:static-content:deploy nn_NO
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```


### #2. Download and install manually

To download and install Norwegian pack manually, you have to access to your server via FTP or SFTP.

**Step 1: Download the package**

- [Download .zip](https://github.com/u12206050/magento-2-norwegian-language-pack/archive/master.zip)

**Step 1: Unzip and upload**

Unzip the compressed file and upload file `master.zip` into `app/i18n/day4code/nn_NO/nn_NO.csv`

**Step 2: Flush cache**

Follow this guide to [Flush Cache on your Magento 2 store](https://magemojo.com/kb/knowledge-base/clear-magento-2-cache/)


## How to active language pack

Now time to active the language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Norwegian language pack}}](https://i.imgur.com/aPSUA0l.png)


## Want to help out:

https://crowdin.com/project/magento-2/no#

NOTE: Builds and updates will be done on a monthly basis until translation is complete.
