# Backdrop for YunoHost

[![Integration level](https://dash.yunohost.org/integration/backdrop.svg)](https://dash.yunohost.org/appci/app/backdrop) ![](https://ci-apps.yunohost.org/ci/badges/backdrop.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/backdrop.maintain.svg)  
[![Install Tiny Tiny RSS with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=backdrop)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install Backdrop quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

Backdrop CMS is a simple, lightweight, and easy-to-use Content Management System for building professional websites.

**Shipped version:** 1.17.4

## Screenshots

![](https://backdropcms.org/files/inline-images/Hello_world.png)

## Demo

* [Official demo](https://backdropcms.org/demo)

## Configuration

#### upgrade

Backdrop CMS includes an update utility to handle any necessary changes to the database schema or configuration. [See instructions](https://backdropcms.org/upgrade)

## Documentation

 * Official documentation: https://backdropcms.org/user-guide
 * YunoHost documentation: https://yunohost.org/#/app_backdrop

## YunoHost specific features

#### Multi-users support

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/backdrop%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/backdrop/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/backdrop%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/backdrop/)

## Limitations

## Additionnal informations

## Links

 * Report a bug: https://github.com/YunoHost-Apps/ttrss_ynh/issues
 * Backdrop website: https://backdropcms.org/
 * Backdrop repository: https://github.com/backdrop/backdrop
 * YunoHost website: https://yunohost.org/

---

## Developers infos

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/backdrop_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/backdrop_ynh/tree/testing --debug
or
sudo yunohost app upgrade backdrop -u https://github.com/YunoHost-Apps/backdrop_ynh/tree/testing --debug
```
