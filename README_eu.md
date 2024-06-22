<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Cultivons YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/cultivons.svg)](https://dash.yunohost.org/appci/app/cultivons) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/cultivons.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/cultivons.maintain.svg)

[![Instalatu Cultivons YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cultivons)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Cultivons YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

__Cultivons!__ is a software in the form of an internal site aiming at helping the management of a BAD (Sustainable Autonomous Base).

A BAD is a place where one or more people can (over)live a disaster (natural, plague, war, economic collapse ... put here the reason that pleases you or scares you the most), for a more or less long period of time, without needing the outside: supermarkets, hospitals, and other services present in a modern society.

This definition is a little broad, in fact a BAD will often materialize by a place in the countryside where one will try to be as autonomous as possible on the most important aspects of survival:

* food (vegetable garden, orchard, animals... everything that is culture and breeding);
* electricity;
* water (including potabilization);
* heating;
* first aid;
* storage of recipes, guides and other documentation...

With __cultivons!__, you can manage 
- your crops, your garden and the associated tasks (semi, harvest) as well as garden plan.
- the weather,
- the stocks,
- your documents,
- your budget (Bank Account).

### Articles
- https://linuxfr.org/users/xulops/journaux/cultivons-logiciel-de-gestion-de-bad


**Paketatutako bertsioa:** 1.9~ynh1

**Demoa:** <https://cultivons-demo.xulops.net>

## Pantaila-argazkiak

![Cultivons(r)en pantaila-argazkia](./doc/screenshots/cultivonsfull.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://xulops.net/forge/cultivons.php>
- Erabiltzaileen dokumentazio ofiziala: <https://xulops.net/forge/cultivons.php?menu=about>
- Administratzaileen dokumentazio ofiziala: <https://xulops.net/forge/cultivons.php?menu=about>
- Jatorrizko aplikazioaren kode-gordailua: <https://xulops.net/forge/cultivons.php?menu=download>
- YunoHost Denda: <https://apps.yunohost.org/app/cultivons>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/cultivons_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/cultivons_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cultivons_ynh/tree/testing --debug
edo
sudo yunohost app upgrade cultivons -u https://github.com/YunoHost-Apps/cultivons_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
