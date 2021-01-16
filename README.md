# PHP Server Monitor for YunoHost

[![Integration level](https://dash.yunohost.org/integration/phpservermon.svg)](https://dash.yunohost.org/appci/app/phpservermon) ![](https://ci-apps.yunohost.org/ci/badges/phpservermon.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/phpservermon.maintain.svg)  
[![Install PHP Server Monitor with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phpservermon)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install PHP Server Monitor quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

PHP Server Monitor is a script that checks whether your websites and servers are up and running.

**Shipped version:** 3.5.2

## Screenshots

![](images/screenshot.png)


## Documentation

 * Official documentation: http://www.phpservermonitor.org/
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

 LDAP and HTTP auth are not supported.
The app can be used by multiple users.

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/phpservermon%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/phpservermon/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/phpservermon%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/phpservermon/)

## Limitations

* SSO are not supported.
## Links

 * Report a bug: https://github.com/YunoHost-Apps/phpservermon_ynh/issues
 * App website: http://www.phpservermonitor.org/.
 * Upstream app repository: https://github.com/phpservermon/phpservermon/.
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/phpservermon_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/phpservermon_ynh/tree/testing --debug
or
sudo yunohost app upgrade phpservermon -u https://github.com/YunoHost-Apps/phpservermon_ynh/tree/testing --debug
```
