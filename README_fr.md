# Komga pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/komga.svg)](https://dash.yunohost.org/appci/app/komga) ![](https://ci-apps.yunohost.org/ci/badges/komga.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/komga.maintain.svg)  
[![Installer Komga avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=komga)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Komga rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Komga is a free and open source comics/mangas server.

### Features

- Browse libraries, series and books via a responsive web UI that works on desktop, tablets and phones
- Organize your library with collections and read lists
- Edit metadata for your series and books
- Import embedded metadata automatically
- Webreader with multiple reading modes
- Manage multiple users, with per-library access control
- Offers a REST API, many community tools and scripts can interact with Komga
- Download book files


**Version incluse :** 0.126.0~ynh1

**Démo :** https://demo.komga.org

## Captures d'écran

![](./doc/screenshots/home.png)

## Documentations et ressources

* Site officiel de l'app : https://komga.org
* Documentation officielle utilisateur : https://yunohost.org/apps
* Documentation officielle de l'admin : https://komga.org/guides/
* Dépôt de code officiel de l'app : https://github.com/gotson/komga
* Documentation YunoHost pour cette app : https://yunohost.org/app_komga
* Signaler un bug : https://github.com/YunoHost-Apps/komga_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/komga_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/komga_ynh/tree/testing --debug
ou
sudo yunohost app upgrade komga -u https://github.com/YunoHost-Apps/komga_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps