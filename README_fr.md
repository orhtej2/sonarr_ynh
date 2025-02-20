<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Sonarr pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/sonarr.svg)](https://dash.yunohost.org/appci/app/sonarr) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/sonarr.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/sonarr.maintain.svg)

[![Installer Sonarr avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=sonarr)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Sonarr rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Sonarr est un PVR pour les utilisateurs Usenet et BitTorrent. Il peut surveiller plusieurs flux RSS pour les nouveaux épisodes de vos émissions préférées et les récupérer, les trier et les renommer. Il peut également être configuré pour mettre à niveau automatiquement la qualité des fichiers déjà téléchargés lorsqu'un format de meilleure qualité devient disponible.


**Version incluse :** 3.0.6.1196~ynh3

## Captures d’écran

![Capture d’écran de Sonarr](./doc/screenshots/screenshot.jpg)

## Avertissements / informations importantes

* Le dépôt des développeurs de Sonarr ne permet de télécharger que la toute dernière version.
  * La version annoncée ici peut être différente de celle réellement installée.
* Les architectures compatibles sont `arm`, `armhf`, `arm64`, et `amd64`
* Le contrôle de l'accès se fait avec le système de permissions de YunoHost.
  * L'API (`domain.tld/path/api`) est accessible aux visiteurs pour permettre le contrôle via des clients externes.
* L'application utilise les dossiers multimédia de YunoHost, elle a donc accès en écriture aux dossiers utilisateurs et communs de `/home/yunohost.multimedia`. Après installation, vous pourrez choisir ces dossiers pour y stocker vos médias.

## Documentations et ressources

- Site officiel de l’app : <https://sonarr.tv>
- Documentation officielle de l’admin : <https://wiki.servarr.com/Sonarr>
- Dépôt de code officiel de l’app : <https://github.com/Sonarr/Sonarr>
- YunoHost Store : <https://apps.yunohost.org/app/sonarr>
- Signaler un bug : <https://github.com/YunoHost-Apps/sonarr_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/sonarr_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/sonarr_ynh/tree/testing --debug
ou
sudo yunohost app upgrade sonarr -u https://github.com/YunoHost-Apps/sonarr_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
