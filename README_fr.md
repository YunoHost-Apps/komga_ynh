<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Komga pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/komga.svg)](https://dash.yunohost.org/appci/app/komga) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/komga.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/komga.maintain.svg)

[![Installer Komga avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=komga)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Komga rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Komga est un serveur de bandes dessinées/mangas gratuit et open source.

### Caractéristiques

- Parcourez les bibliothèques, les séries et les livres via une interface utilisateur Web réactive qui fonctionne sur les ordinateurs de bureau, les tablettes et les téléphones
- Organisez votre bibliothèque avec des collections et des listes de lecture
- Modifiez les métadonnées de vos séries et livres
- Importer automatiquement les métadonnées intégrées
- Lecteur Web avec plusieurs modes de lecture
- Gérer plusieurs utilisateurs, avec contrôle d'accès par bibliothèque
- Propose une API REST, de nombreux outils et scripts communautaires peuvent interagir avec Komga
- Télécharger des fichiers de livres

**Version incluse :** 1.10.3~ynh1

**Démo :** <https://demo.komga.org>

## Captures d’écran

![Capture d’écran de Komga](./doc/screenshots/home.png)

## Documentations et ressources

- Site officiel de l’app : <https://komga.org>
- Documentation officielle de l’admin : <https://komga.org/guides/>
- Dépôt de code officiel de l’app : <https://github.com/gotson/komga>
- YunoHost Store : <https://apps.yunohost.org/app/komga>
- Signaler un bug : <https://github.com/YunoHost-Apps/komga_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/komga_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/komga_ynh/tree/testing --debug
ou
sudo yunohost app upgrade komga -u https://github.com/YunoHost-Apps/komga_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
