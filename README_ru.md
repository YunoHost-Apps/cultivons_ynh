<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Cultivons для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/cultivons.svg)](https://ci-apps.yunohost.org/ci/apps/cultivons/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/cultivons.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/cultivons.maintain.svg)

[![Установите Cultivons с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cultivons)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Cultivons быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

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


**Поставляемая версия:** 1.9~ynh1

**Демо-версия:** <https://cultivons-demo.xulops.net>

## Снимки экрана

![Снимок экрана Cultivons](./doc/screenshots/cultivonsfull.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://xulops.net/forge/cultivons.php>
- Официальная документация пользователя: <https://xulops.net/forge/cultivons.php?menu=about>
- Официальная документация администратора: <https://xulops.net/forge/cultivons.php?menu=about>
- Репозиторий кода главной ветки приложения: <https://xulops.net/forge/cultivons.php?menu=download>
- Магазин YunoHost: <https://apps.yunohost.org/app/cultivons>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/cultivons_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/cultivons_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cultivons_ynh/tree/testing --debug
или
sudo yunohost app upgrade cultivons -u https://github.com/YunoHost-Apps/cultivons_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
