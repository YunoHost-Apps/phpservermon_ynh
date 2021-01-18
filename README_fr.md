# PHP Server Monitor pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/phpservermon.svg)](https://dash.yunohost.org/appci/app/phpservermon) ![](https://ci-apps.yunohost.org/ci/badges/phpservermon.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/phpservermon.maintain.svg)  
[![Installer phpservermon avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phpservermon)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer PHP Server Monitor rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble

PHP Server Monitor est une application qui contrôle que vos serveurs et site web soient fonctionnels.

**Version incluse :** 3.5.2

## Captures d'écran

![](images/screenshot.png)

## Documentation

 * Documentation officielle : http://www.phpservermonitor.org/
 * Dépot de l'application : https://github.com/phpservermon/phpservermon/


## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'application ne supporte pas le SSO/LDAP.
* L'application peut être utilisées par plusieurs utilisateurs.

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/phpservermon%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/phpservermon/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/phpservermon%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/phpservermon/)

## Limitations

* SSO non supporté

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/phpservermon_ynh/issues
 * Site de l'application : http://www.phpservermonitor.org/
 * Dépôt de l'application principale : https://github.com/phpservermon/phpservermon/.
 * Site web YunoHost : https://yunohost.org/


## Informations pour les développeurs


Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/phpservermon/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/phpservermon/tree/testing --debug
ou
sudo yunohost app upgrade phpservermon -u https://github.com/YunoHost-Apps/phpservermon/tree/testing --debug
```
