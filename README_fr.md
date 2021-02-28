# Komga pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/komga.svg)](https://dash.yunohost.org/appci/app/komga) ![](https://ci-apps.yunohost.org/ci/badges/komga.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/komga.maintain.svg)  
[![Installer Komga avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=komga)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Komga rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
Komga est un serveur multimédia pour vos bandes dessinées, mangas, BD et magazines. 

Les fonctionnalités incluent :
* Parcourir les bibliothèques, séries et livres
* Barre de recherche
* Télécharger des livres
* Gérer plusieurs utilisateurs, avec le contrôle des accès par bibliothèque
* Lecteur Web

**Version incluse :** 0.75.1

## Captures d'écran

![](./screenshots/home.png)

## Démo

* [Démo officielle](https://demo.komga.org)

- Login : `demo@komga.org`
- Mot de passe : `komga-demo`

## Configuration

 * Comment configurer cette application : via le panneau d'administration

## Documentation

 * Documentation officielle : https://komga.org/guides/
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ? **Non**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/komga%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/komga/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/komga%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/komga/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/komga_ynh/issues
 * Site de l'application : https://komga.org
 * Dépôt de l'application principale : https://github.com/gotson/komga
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/komga_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/komga_ynh/tree/testing --debug
ou
sudo yunohost app upgrade komga -u https://github.com/YunoHost-Apps/komga_ynh/tree/testing --debug
```
