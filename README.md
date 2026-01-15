# WarlordsTemplate

## English

### Overview

This repository contains a `description.ext` file configured as a **Warlords mission template for Arma 3**. It is intended to be used as a base and **must be customized** before running the mission.

---

### Mandatory Configuration

#### Mission Information

You are required to customize the basic mission metadata:

* `onLoadMission` – Mission description shown while loading
* `onLoadName` – Mission name
* `dev` – Your nickname
* `author` – Mission author
* `min/maxPlayers` - Player limits

Leaving default values here is not allowed.

#### `class CfgWLRequisitionPresets`  **(REQUIRED)**

You **must**:

* Add **all of your custom unit and vehicle classes** here
* Ensure every asset used in the mission is registered

If your classes are missing here, they will not be available in Warlords.

[My classes list](https://github.com/KaifKol/A3-classNames)

### Optional Configuration

#### `class CfgWLFactionAssets`

Controls which assets are available per faction.

* Modify this if you want to restrict or expand faction-specific units

#### `class CfgWLAssetCostOverride`

Allows overriding default requisition costs for assets.

* Use this to rebalance units and vehicles
* Optional, but useful for fine-tuning gameplay

### Notes

* This template assumes you understand Arma 3 Warlords configuration
* Always verify classnames via the Config Viewer
* Test the mission after every major change

### Installation
* Place the `description.ext` file into the mission folder.
* Optionally, you may also add the `images` folder to the same directory.

---

## Русский

### Обзор

Данный репозиторий содержит файл `description.ext`, настроенный как **шаблон миссии Warlords для Arma 3**. Он предназначен для использования в качестве базы и **обязательно требует редактирования** перед запуском.

---

### Обязательные настройки

#### Информация о миссии

Эти параметры **обязательно** нужно изменить:

* `onLoadMission` – описание миссии при загрузке
* `onLoadName` – название миссии
* `dev` – ваш никнейм
* `author` – автор миссии
* `min/maxPlayers`- лимит игроков

Использование значений по умолчанию недопустимо.

#### `class CfgWLRequisitionPresets`  **(ОБЯЗАТЕЛЬНО)**

Вы **обязаны**:

* Добавить **все свои классы юнитов и техники**
* Убедиться, что каждый используемый ассет зарегистрирован

Без этого ассеты не появятся в режиме Warlords.

[Мой лист классов](https://github.com/KaifKol/A3-classNames)


### Необязательные настройки

#### `class CfgWLFactionAssets`

Определяет доступные ассеты для каждой фракции.

* Используется для ограничения или расширения списков

#### `class CfgWLAssetCostOverride`

Позволяет переопределять стоимость реквизиции.

* Используется для балансировки
* Полностью необязательный раздел


### Примечания

* Шаблон рассчитан на понимание системы Warlords в Arma 3
* Проверяйте class name через Config Viewer
* Тестируйте миссию после изменений

### Установка
* Поместите файл `description.ext` в папку с миссией.
* При необходимости можно также добавить туда папку `images`.

---

<p align="center" style="font-size: 28px; font-weight: bold;">
    Developed by the RallyPoint community
</p>
<p align="center">
  <a href="https://discord.gg/hJj45jUdjT">
    <img src="https://i.postimg.cc/pXzW7R3X/1.png" width="1500">
  </a>
</p>




