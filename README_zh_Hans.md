<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Komga

[![集成程度](https://dash.yunohost.org/integration/komga.svg)](https://dash.yunohost.org/appci/app/komga) ![工作状态](https://ci-apps.yunohost.org/ci/badges/komga.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/komga.maintain.svg)

[![使用 YunoHost 安装 Komga](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=komga)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Komga。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

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


**分发版本：** 1.10.3~ynh1

**演示：** <https://demo.komga.org>

## 截图

![Komga 的截图](./doc/screenshots/home.png)

## 文档与资源

- 官方应用网站： <https://komga.org>
- 官方管理文档： <https://komga.org/guides/>
- 上游应用代码库： <https://github.com/gotson/komga>
- YunoHost 商店： <https://apps.yunohost.org/app/komga>
- 报告 bug： <https://github.com/YunoHost-Apps/komga_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/komga_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/komga_ynh/tree/testing --debug
或
sudo yunohost app upgrade komga -u https://github.com/YunoHost-Apps/komga_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
