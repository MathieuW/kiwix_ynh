# Kiwix pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/kiwix.svg)](https://dash.yunohost.org/appci/app/kiwix) ![](https://ci-apps.yunohost.org/ci/badges/kiwix.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/kiwix.maintain.svg)  
[![Installer Kiwix avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kiwix)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Kiwix rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Kiwix est un lecteur hors-ligne pour contenus web qui permet en particulier d’accéder à Wikipédia sans connexion à Internet.

### Fonctionnalités
- Un moteur de recherche de tout texte
- Suggestions de recherche
- Réellement petit et efficace
- Compatible avec la majorité des navigateurs internet
- Disponible avec toutes les plateformes
- Disponible par ligne de commande exécutables
- Embedded in Kiwix UI
- Capable de traiter un fichier ZIM ou des fichiers de bibliothèque XML

**Version incluse :** 3.1.2~ynh1

**Démo :** http://library.kiwix.org/

## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Documentations et ressources

* Site officiel de l'app : https://www.kiwix.org/
* Documentation officielle de l'admin : https://wiki.kiwix.org/wiki/Kiwix-serve/
* Dépôt de code officiel de l'app : https://github.com/kiwix/kiwix-tools
* Documentation YunoHost pour cette app : https://yunohost.org/app_kiwix
* Signaler un bug : https://github.com/YunoHost-Apps/kiwix_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
ou
sudo yunohost app upgrade kiwix -u https://github.com/YunoHost-Apps/kiwix_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps