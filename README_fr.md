# Backdrop pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/backdrop.svg)](https://dash.yunohost.org/appci/app/backdrop) ![](https://ci-apps.yunohost.org/ci/badges/backdrop.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/backdrop.maintain.svg)  
[![Installer Backdrop avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=backdrop)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d’installer Backdrop rapidement et simplement sur un serveur YunoHost.  
Si vous n’avez pas YunoHost, consultez [le guide](https://yunohost.org/install) pour apprendre comment l’installer.*

## Vue d’ensemble

Backdrop CMS is a simple, lightweight, and easy-to-use Content Management System for building professional websites.

**Version incluse :** 1.19.0

## Captures d’écran

![](https://backdropcms.org/files/inline-images/Hello_world.png)

## Démo

* [Démo officielle](https://backdropcms.org/demo)

## Configuration

Backdrop CMS inclus un utilitaire de mise à jour pour gérer toutes les modifications nécessaires à configuration et base de données. [Voir les instructions](https://backdropcms.org/upgrade)

## Documentation

* Documentation officielle : https://backdropcms.org/user-guide

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateurs

* L’authentification LDAP est-elle prise en charge ? **Oui**
* L’application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/backdrop.svg)](https://ci-apps.yunohost.org/ci/apps/backdrop/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/backdrop.svg)](https://ci-apps-arm.yunohost.org/ci/apps/backdrop/)

## Limitations

## Informations additionnelles

## Liens

* Signaler un bug : https://github.com/YunoHost-Apps/backdrop_ynh/issues
* Site web de Backdrop : https://backdropcms.org/
* Dépôt de l’application principale : https://github.com/backdrop/backdrop
* Site web YunoHost : https://yunohost.org/

---

## Developers infos

Merci de faire vos pull request sur la [testing branch](https://github.com/YunoHost-Apps/backdrop_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/backdrop_ynh/tree/testing --debug
ou
sudo yunohost app upgrade backdrop -u https://github.com/YunoHost-Apps/backdrop_ynh/tree/testing --debug
```
