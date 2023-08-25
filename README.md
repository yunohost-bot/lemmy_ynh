<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Lemmy for YunoHost

[![Integration level](https://dash.yunohost.org/integration/lemmy.svg)](https://dash.yunohost.org/appci/app/lemmy) ![Working status](https://ci-apps.yunohost.org/ci/badges/lemmy.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/lemmy.maintain.svg)

[![Install Lemmy with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=lemmy)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Lemmy quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Lemmy is similar to sites like Reddit, Lobste.rs, or Hacker News: you subscribe to forums you're interested in, post links and discussions, then vote, and comment on them. Behind the scenes, it is very different; anyone can easily run a server, and all these servers are federated (think email), and connected to the same universe, called the Fediverse.


**Shipped version:** 0.18.4~ynh1

**Demo:** https://lemmy.ml/

## Screenshots

![Screenshot of Lemmy](./doc/screenshots/screenshot1.webp)

## Documentation and resources

* Official app website: <https://join-lemmy.org/>
* Official admin documentation: <https://join-lemmy.org/docs/en/>
* Upstream app code repository: <https://github.com/LemmyNet/lemmy>
* YunoHost documentation for this app: <https://yunohost.org/app_lemmy>
* Report a bug: <https://github.com/YunoHost-Apps/lemmy_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/lemmy_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/lemmy_ynh/tree/testing --debug
or
sudo yunohost app upgrade lemmy -u https://github.com/YunoHost-Apps/lemmy_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
