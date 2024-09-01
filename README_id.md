<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Cultivons untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/cultivons.svg)](https://ci-apps.yunohost.org/ci/apps/cultivons/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/cultivons.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/cultivons.maintain.svg)

[![Pasang Cultivons dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cultivons)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Cultivons secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

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


**Versi terkirim:** 1.9~ynh2

**Demo:** <https://cultivons-demo.xulops.net>

## Tangkapan Layar

![Tangkapan Layar pada Cultivons](./doc/screenshots/cultivonsfull.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://xulops.net/forge/cultivons.php>
- Dokumentasi pengguna resmi: <https://xulops.net/forge/cultivons.php?menu=about>
- Dokumentasi admin resmi: <https://xulops.net/forge/cultivons.php?menu=about>
- Depot kode aplikasi hulu: <https://xulops.net/forge/cultivons.php?menu=download>
- Gudang YunoHost: <https://apps.yunohost.org/app/cultivons>
- Laporkan bug: <https://github.com/YunoHost-Apps/cultivons_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/cultivons_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cultivons_ynh/tree/testing --debug
atau
sudo yunohost app upgrade cultivons -u https://github.com/YunoHost-Apps/cultivons_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
