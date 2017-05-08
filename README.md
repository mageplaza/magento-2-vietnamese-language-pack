## Magento 2 Vietnamese Language Pack

Switching your store to Vietnamese according to **Magento 2 Vietnamese Language Pack** instruction. The transformation will cover both storefront and backend on Magento 2 store. It is time to focus on the localization language when there is any plan to enter the international market as Vietnam. This will help you eliminate the language barrier for the better commerce.

The language package is contributed by the native Vienamese speakers from Magento 2 Translation Project, so the quality of the convertion is surely guanranteed. Then, you will donwload and install the zip file that compress all translated phrases into Vietnamese. 

Read more [Magento 2 Vietnamese Language Pack](https://www.mageplaza.com/magento-2-vietnamese-language-pack.html)


## Overview

- Download & Contribute
- Install Vietnamese Language Pack
- How to Install Vietnamese Language Pack

## Download & Contribute to Vietnamese Language Pack

Below are two active buttons which are required operations before installing the language package. Let's hit them to download and contribute Magento 2 Vietnamese Language Pack immediately!

**Download packages**:

- [Download .zip](https://github.com/mageplaza/magento-2-vietnamese-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-vietnamese-language-pack/tarball/master)
- [Copy & paste package](https://crowdin.com/project/magento-2/vi.zip)


Find other [language packs here]({https://www.mageplaza.com/kb/magento-2-language-pack/)

## How to Install Vietnamese Language Pack

There are 3 different methods to install this language pack.

### #1. Composer method
Install the Vietnamese language pack via composer is never easier.

**Install Vietnamese pack**:

```
composer require mageplaza/magento-2-vietnamese-language-pack:dev-master
php bin/magento cache:clean
php bin/magento setup:static-content:deploy vi_VN
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```


**Update  Vietnamese pack**:

```
composer update mageplaza/magento-2-vietnamese-language-pack:dev-master
php bin/magento cache:clean
php bin/magento setup:static-content:deploy vi_VN
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```

#### Authentication required (Optional)

[Authentication required](https://i.imgur.com/dmryiPk.png)

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)


### #2. Copy & Paste method

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Vietnamese language pack
- Step 2: Unzip Vietnamese pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Vietnamese language pack

You can download the language pack from above link

#### Step 2: Unzip Vietnamese pack

Unzip the Vietnamese language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip fr.zip /var/www/html/
```

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


### #3. Download and install manually

To download and install Vietnamese pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/mageplaza/magento-2-vietnamese-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-vietnamese-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `vi_VN.zip` into `app/i18n/mageplaza/vi_VN/vi_VN.csv`

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## How to active language pack

Now time to active the language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Vietnamese language pack}}](https://i.imgur.com/aPSUA0l.png)


## Translation process of Vietnamese Language Pack
![process](http://progressed.io/bar/80)

Contribute to this language at https://crowdin.com/project/magento-2/vi

## Supported Magento versions

- Magento v2.0.0
- Magento v2.0.1
- Magento v2.0.2
- Magento v2.0.3
- Magento v2.0.4
- Magento v2.0.5
- Magento v2.0.6
- Magento v2.0.7
- Magento v2.0.8
- Magento v2.0.9
- Magento v2.0.10
- Magento v2.0.11
- Magento v2.0.12
- Magento v2.0.13
- Magento v2.1.0
- Magento v2.1.1
- Magento v2.1.2
- Magento v2.1.3
- Magento v2.1.4
- Magento v2.1.5
- Magento v2.1.6



## Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Language packages built by [Mageplaza team](https://www.mageplaza.com/)


References:
- https://www.mageplaza.com/magento-2-vietnamese-language-pack.html
- https://www.mageplaza.com/kb/magento-2-language-pack/