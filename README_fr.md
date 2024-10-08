<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Cultivons pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/cultivons.svg)](https://ci-apps.yunohost.org/ci/apps/cultivons/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/cultivons.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/cultivons.maintain.svg)

[![Installer Cultivons avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cultivons)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Cultivons rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

__Cultivons!__ est un logiciel sous forme de site interne visant à aider à la gestion d'une BAD (Base Autonome Durable).

Une BAD est un endroit où une ou plusieurs personnes peuvent (sur)vivre à une catastrophe (naturelle, fléau, guerre, effondrement économique … mettez ici la raison qui vous plaît ou vous fait le plus peur), pendant une période plus ou moins longue, sans avoir besoin de l’extérieur : supermarchés, hôpitaux, et autres services présents dans une société moderne.

Cette définition est un peu large, dans les faits une BAD se matérialisera souvent par un endroit à la campagne où on tentera d’être au maximum autonome sur les aspects les plus importants de la survie :

- la nourriture (potager, verger, animaux … tout ce qui est culture et élevage),
- électricité,
- eau (y compris la potabilisation),
- chauffage,
- premiers soins,
- stockage de recettes, guides et autres documentations,
- ...

Avec __Cultivons!__, vous pouvez gérer 
- vos cultures, votre jardin et les tâches associées (semis, récoltes) ainsi qu'un plan.
- la météo,
- les stocks,
- vos documents,
- votre budget.

### Articles
- https://linuxfr.org/users/xulops/journaux/cultivons-logiciel-de-gestion-de-bad


**Version incluse :** 1.9~ynh2

**Démo :** <https://cultivons-demo.xulops.net>

## Captures d’écran

![Capture d’écran de Cultivons](./doc/screenshots/cultivonsfull.png)

## Documentations et ressources

- Site officiel de l’app : <https://xulops.net/forge/cultivons.php>
- Documentation officielle utilisateur : <https://xulops.net/forge/cultivons.php?menu=about>
- Documentation officielle de l’admin : <https://xulops.net/forge/cultivons.php?menu=about>
- Dépôt de code officiel de l’app : <https://xulops.net/forge/cultivons.php?menu=download>
- YunoHost Store : <https://apps.yunohost.org/app/cultivons>
- Signaler un bug : <https://github.com/YunoHost-Apps/cultivons_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/cultivons_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cultivons_ynh/tree/testing --debug
ou
sudo yunohost app upgrade cultivons -u https://github.com/YunoHost-Apps/cultivons_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
