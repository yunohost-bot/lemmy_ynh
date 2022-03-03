<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# lemmy for YunoHost

[![Integration level](https://dash.yunohost.org/integration/lemmy.svg)](https://dash.yunohost.org/appci/app/lemmy) ![](https://ci-apps.yunohost.org/ci/badges/lemmy.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/lemmy.maintain.svg)  
[![Install lemmy with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=lemmy)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install lemmy quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

[Lemmy](https://github.com/LemmyNet/lemmy) is similar to sites like [Reddit](https://reddit.com), [Lobste.rs](https://lobste.rs), or [Hacker News](https://news.ycombinator.com/): you subscribe to forums you're interested in, post links and discussions, then vote, and comment on them. Behind the scenes, it is very different; anyone can easily run a server, and all these servers are federated (think email), and connected to the same universe, called the [Fediverse](https://en.wikipedia.org/wiki/Fediverse).


**Shipped version:** 0.15.2~ynh2

**Demo:** https://lemmy.ml/

## Screenshots

![](./doc/screenshots/screenshot1.webp)

## Disclaimers / important information

* Lemmy require full domain path to be installed. Eg. lemmy.domain.tld
* The admin username and password will be sent to the admin of the YunoHost through mail.
## Documentation and resources

* Official app website: https://join-lemmy.org/
* Official admin documentation: https://join-lemmy.org/docs/en/
* Upstream app code repository: https://github.com/LemmyNet/lemmy
* YunoHost documentation for this app: https://yunohost.org/app_lemmy
* Report a bug: https://github.com/YunoHost-Apps/lemmy_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/lemmy_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/lemmy_ynh/tree/testing --debug
or
sudo yunohost app upgrade lemmy -u https://github.com/YunoHost-Apps/lemmy_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps