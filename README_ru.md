<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Komga для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/komga)](https://ci-apps.yunohost.org/ci/apps/komga/)
![Состояние работы](https://apps.yunohost.org/badge/state/komga)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/komga)

[![Установите Komga с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=komga)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Komga быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

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


**Поставляемая версия:** 1.20.0~ynh2

**Демо-версия:** <https://demo.komga.org>

## Снимки экрана

![Снимок экрана Komga](./doc/screenshots/home.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://komga.org>
- Официальная документация администратора: <https://komga.org/guides/>
- Репозиторий кода главной ветки приложения: <https://github.com/gotson/komga>
- Магазин YunoHost: <https://apps.yunohost.org/app/komga>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/komga_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/komga_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/komga_ynh/tree/testing --debug
или
sudo yunohost app upgrade komga -u https://github.com/YunoHost-Apps/komga_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
