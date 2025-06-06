![BANNER](/img/banner.png)

# 🎙️ ГЛАСОВО УПРАВЛЕНИЕ НА HASS УСТРОЙСТВА С ALEXA/GOOGLE HOME
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?color=ff00d8)](https://opensource.org/licenses/MIT)
![GitHub last commit](https://img.shields.io/github/last-commit/Bacard1/HASS-matter-alexa-or-google-control.svg?color=ff00d8)
[![hacs_badge](https://img.shields.io/badge/HACS-2025.5.3-orange.svg?color=ff00d8)](https://github.com/hacs/integration)

[![Home Assistant](https://img.shields.io/badge/.-HOME_ASSISTANT-blue?logo=homeassistant)](https://www.home-assistant.io/) 
[![Donate via PayPal](https://img.shields.io/badge/PayPal-DONATE-blue?logo=paypal)](https://www.paypal.com/donate/?hosted_button_id=AAWFZVF2XCP5A)
![Script](https://img.shields.io/badge/Script-YAML-blue?logo=yaml)

[![Български](https://img.shields.io/badge/BG-ЕЗИК-gree?logo=translate&labelColor=gray&style=flat-square&link=https://example.com/bg
)](BG.md)
[![Deutch](https://img.shields.io/badge/DE-SPRACHE-gree?logo=translate&labelColor=gray&style=flat-square&link=https://example.com/bg
)](DE.md)
[![English](https://img.shields.io/badge/EN-LANGUAGE-gree?logo=translate&labelColor=gray&style=flat-square&link=https://example.com/bg)](README.md)

Гласово управление на Home Assistant устройства с Alexa или Google Home чрез Matter

Това хранилище предоставя интеграция между Home Assistant и популярните гласови асистенти като Amazon Alexa и Google Home, използвайки новия протокол Matter. Можете лесно да управлявате вашите смарт устройства, автоматизации и скриптове с гласови команди – за по-удобен, ефективен и интуитивен дом.

✅ Поддръжка на гласово управление за светлини, контакти, сензори, сцени, скриптове и други.
✅ Лесни стъпки за свързване чрез Matter Hub.
✅ Многоезична поддръжка (Английски/Български).
✅ Редовно тествано и актуализирано.

👉 Подходящо за потребители, които искат да комбинират мощта на Home Assistant с удобството на гласовите асистенти.

---

## 📦 Съдържание

- [🎙️ ГЛАСОВО УПРАВЛЕНИЕ НА HASS УСТРОЙСТВА С ALEXA/GOOGLE HOME](#️-гласово-управление-на-hass-устройства-с-alexagoogle-home)
	- [📦 Съдържание](#-съдържание)
	- [🕸️ Home-Assistant-Matter-Hub](#️-home-assistant-matter-hub)
		- [⚡ Инсталиране](#-инсталиране)
		- [🛠️ Създаване/Конфигуриране на хъб](#️-създаванеконфигуриране-на-хъб)
		- [🔗 Добавяне на Автоматизация/Комбинация от действия/Скрипт:](#-добавяне-на-автоматизациякомбинация-от-действияскрипт)

---

## 🕸️ Home-Assistant-Matter-Hub
Този проект симулира мостове за публикуване на вашите обекти от Home Assistant към всеки контролер, съвместим с Matter, като например Alexa, Apple Home или Google Home. С помощта на Matter те могат да бъдат свързани лесно чрез локална комуникация без нужда на пристанищна спедиция и др.<br>

### ⚡ Инсталиране

Кликни за да добавиш хранилището на добавката:<br>

[![ADD REPO](/img/button%20ADD%20ADD-ON%20REPOSITORY%20TO%20MY.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Ft0bst4r%2Fhome-assistant-addons%2F)

> Резултат:

![ADDON](/img/repo_ist_add.png)

> [!NOTE]
> Ако след добавянето на хранилището все още не виждате добавката, обновете страницата!

>Инсталиране на добавката

![install](/img/install.png)

> [!NOTE]
> Добавката не се нуждае от допълнителни настройки. Приминете директно към старт след като рестартирате системата.

![start addon](/img/start_addon.png)

### 🛠️ Създаване/Конфигуриране на хъб
>Създаване на едикет който да напомня за `MatterHub`:

![new labels](/img/new_labels.png)

>Отворете добавката и кликнете на `CREATE NEW BRIDGES`

![my briges](/img/new_bridges.png)

> Настройте новият HUB както е показано на снимката:

![config](/img/config_bridges.png)

След като полълните конфигурацията запазете и рестартирайте добавката.

> [!NOTE]
> За да се добави към новият HUB устойство, добавете му етикет `MatterHub` и рестартирайте добавката

>Резултат:
![img](/img/installed.png)

### 🔗 Добавяне на Автоматизация/Комбинация от действия/Скрипт:
За целта да активирате "Автоматизация/Комбинация от действия/Скрипт" използвам "Помощници" който ги добавям в "Автоматизация/Комбинация от действия/Скрипт" и да активират действието/действията. 

Примери за "Помощници":

![button helper](/img/button_helper.png)

или

![boolean helper](/img/boolean_helper.png)

---
> [!TIP]
> Ако този проект ви е харесъл, [ТУК](https://github.com/Bacard1?tab=repositories) ще намерите още интересни гранилища направени от мен.<br>
> Ако срещате затруднения или имате въпроси не се колебайте да се свържете с мен.