<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# phpBB for YunoHost

[![Integration level](https://dash.yunohost.org/integration/phpbb.svg)](https://dash.yunohost.org/appci/app/phpbb) ![](https://ci-apps.yunohost.org/ci/badges/phpbb.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/phpbb.maintain.svg)  
[![Install phpBB with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phpbb)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install phpBB quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Forum software that is easy to use, powerful, and highly customisable

**Shipped version:** 3.3.4~ynh3

**Demo:** https://www.phpbb.com/demo/

## Screenshots

![](./doc/screenshots/screenshot.png)

## Disclaimers / important information

## Configuration

1. The app will require to complete the registration process after the instllation is complete by **visiting the domain** on  which *phpBB* is installed.
1. The MySQL database credentials will be sent to the **admin mail**.
1. Please delete, move or rename the install directory (`mv /var/www/phpbb/install /var/www/phpbb/install_old`) before you use your board. If this directory is still present, only the Administration Control Panel (ACP) will be accessible.

## Documentation and resources

* Official app website: http://www.phpbb.com/
* Official user documentation: https://yunohost.org/apps
* Official admin documentation: https://www.phpbb.com/support/docs/
* Upstream app code repository: https://github.com/phpbb/phpbb
* YunoHost documentation for this app: https://yunohost.org/app_phpbb
* Report a bug: https://github.com/YunoHost-Apps/phpbb_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/phpbb_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/phpbb_ynh/tree/testing --debug
or
sudo yunohost app upgrade phpbb -u https://github.com/YunoHost-Apps/phpbb_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps