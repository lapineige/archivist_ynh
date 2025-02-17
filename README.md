<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Archivist for YunoHost

[![Integration level](https://dash.yunohost.org/integration/archivist.svg)](https://dash.yunohost.org/appci/app/archivist) ![Working status](https://ci-apps.yunohost.org/ci/badges/archivist.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/archivist.maintain.svg)

[![Install Archivist with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=archivist)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Archivist quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Archivist is an automatic backup system for your server.  
It able to makes backups of your YunoHost core and your apps by using the YunoHost backup command.  
It can also makes backups of specified directories.  
Your backups can be send to many other places, local or distant.  
Archivist is automatically launched periodicaly to update your backups and send the modifications to the other places.



**Shipped version:** 1.3.3~ynh1
## Disclaimers / important information

## Configuration

The configuration of archivist can be changed in the file /opt/yunohost/archivist/Backup_list.conf  
Please read the [documentation](https://github.com/maniackcrudelis/archivist/blob/master/Configuration.md) about the configuration of archivist for more informations.

## Limitations

* Encfs, which be used to encrypt the data, is not fully secured.  
Have a look to the [security audit](https://defuse.ca/audits/encfs.htm) to have more informations.


## Documentation and resources

* Official app website: <https://github.com/maniackcrudelis/archivist>
* Upstream app code repository: <https://github.com/maniackcrudelis/archivist>
* YunoHost Store: <https://apps.yunohost.org/app/archivist>
* Report a bug: <https://github.com/YunoHost-Apps/archivist_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/archivist_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/archivist_ynh/tree/testing --debug
or
sudo yunohost app upgrade archivist -u https://github.com/YunoHost-Apps/archivist_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
