<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Komga YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/komga.svg)](https://dash.yunohost.org/appci/app/komga) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/komga.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/komga.maintain.svg)

[![Instalatu Komga YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=komga)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Komga YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

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


**Paketatutako bertsioa:** 1.10.3~ynh1

**Demoa:** <https://demo.komga.org>

## Pantaila-argazkiak

![Komga(r)en pantaila-argazkia](./doc/screenshots/home.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://komga.org>
- Administratzaileen dokumentazio ofiziala: <https://komga.org/guides/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/gotson/komga>
- YunoHost Denda: <https://apps.yunohost.org/app/komga>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/komga_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/komga_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/komga_ynh/tree/testing --debug
edo
sudo yunohost app upgrade komga -u https://github.com/YunoHost-Apps/komga_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
