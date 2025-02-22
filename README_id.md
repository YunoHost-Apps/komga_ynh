<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Komga untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/komga)](https://ci-apps.yunohost.org/ci/apps/komga/)
![Status kerja](https://apps.yunohost.org/badge/state/komga)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/komga)

[![Pasang Komga dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=komga)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Komga secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

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


**Versi terkirim:** 1.20.0~ynh2

**Demo:** <https://demo.komga.org>

## Tangkapan Layar

![Tangkapan Layar pada Komga](./doc/screenshots/home.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://komga.org>
- Dokumentasi admin resmi: <https://komga.org/guides/>
- Depot kode aplikasi hulu: <https://github.com/gotson/komga>
- Gudang YunoHost: <https://apps.yunohost.org/app/komga>
- Laporkan bug: <https://github.com/YunoHost-Apps/komga_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/komga_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/komga_ynh/tree/testing --debug
atau
sudo yunohost app upgrade komga -u https://github.com/YunoHost-Apps/komga_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
