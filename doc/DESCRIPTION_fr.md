# Cultivons for YunoHost

[![Integration level](https://dash.yunohost.org/integration/cultivons.svg)](https://dash.yunohost.org/appci/app/cultivons) ![Working status](https://ci-apps.yunohost.org/ci/badges/cultivons.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/cultivons.maintain.svg)  
[![Install cultivons with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cultivons)

## Overview

__Cultivons!__ est un logiciel sous forme de site interne visant à aider à la gestion d'une BAD (Base Autonome Durable).

Une BAD est un endroit où une ou plusieurs personnes peuvent (sur)vivre à une catastrophe (naturelle, fléau, guerre, effondrement économique … mettez ici la raison qui vous plaît ou vous fait le plus peur), pendant une période plus ou moins longue, sans avoir besoin de l’extérieur : supermarchés, hôpitaux, et autres services présents dans une société moderne.

Cette définition est un peu large, dans les faits une BAD se matérialisera souvent par un endroit à la campagne où on tentera d’être au maximum autonome sur les aspects les plus importants de la survie :

- la nourriture (potager, verger, animaux … tout ce qui est culture et élevage) ;
- électricité ;
- eau (y compris la potabilisation) ;
- chauffage ;
- premiers soins ;
- stockage de recettes, guides et autres documentations ;
- …

Avec __Cultivons!__, vous pouvez gérer 
- vos cultures, votre jardin et les tâches associes (semis, récoltes) ainsi qu'un plan.
- la météo,
- les stocks,
- vos documents,
- votre budget.

### Features
- 
- 

**Shipped version:** 1.6

**Demo:** https://cultivons-demo.xulops.net

## Screenshots

![Screenshot of cultivons](./doc/screenshots/cultivonsfull.png)

## Documentation and resources

* Official app website: <https://xulops.net/forge/cultivons.php>
* Official admin documentation: <https://xulops.net/forge/cultivons.php>
* Upstream app code repository: <https://xulops.net/forge/cultivons.php?menu=download>
* YunoHost documentation for this app: <https://yunohost.org/app_cultivons>
* Report a bug: <https://github.com/YunoHost-Apps/cultivons_ynh/issues>

## Articles

* linuxfr <https://linuxfr.org/users/xulops/journaux/cultivons-logiciel-de-gestion-de-bad>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/cultivons_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/cultivons_ynh/tree/testing --debug
or
sudo yunohost app upgrade cultivons -u https://github.com/YunoHost-Apps/cultivons_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
