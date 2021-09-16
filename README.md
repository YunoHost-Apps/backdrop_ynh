<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Backdrop for YunoHost

[![Integration level](https://dash.yunohost.org/integration/backdrop.svg)](https://dash.yunohost.org/appci/app/backdrop) ![](https://ci-apps.yunohost.org/ci/badges/backdrop.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/backdrop.maintain.svg)  
[![Install Backdrop with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=backdrop)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Backdrop quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Backdrop is a full-featured content management system that allows non-technical users to manage a wide variety of content. It can be used to create all kinds of websites including blogs, image galleries, social networks, intranets, and more.

### Features:

- A CMS that can be used out-of-the-box.
- Code that can be learned quickly.
- Extensible APIs.


**Shipped version:** 1.20.0-preview~ynh1

**Demo:** https://backdropcms.org/demo

## Screenshots

![](./doc/screenshots/Hello_world.png)

## Disclaimers / important information

#### upgrade

Backdrop CMS includes an update utility to handle any necessary changes to the database schema or configuration. [See instructions](https://backdropcms.org/upgrade)

## Documentation and resources

* Official app website: https://backdropcms.org/
* Official user documentation: https://backdropcms.org/user-guide
* Official admin documentation: https://yunohost.org/packaging_apps
* Upstream app code repository: https://github.com/backdrop/backdrop
* YunoHost documentation for this app: https://yunohost.org/app_backdrop
* Report a bug: https://github.com/YunoHost-Apps/backdrop_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/backdrop_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/backdrop_ynh/tree/testing --debug
or
sudo yunohost app upgrade backdrop -u https://github.com/YunoHost-Apps/backdrop_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps