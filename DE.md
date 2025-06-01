![BANNER](/img/banner.png)  

# 🎙️ SPRACHSTEUERUNG FÜR HASS-GERÄTE MIT ALEXA/GOOGLE HOME  
[![Home Assistant](https://img.shields.io/badge/🏠_Home_Assistant-41BDF5?logo=homeassistant)](https://www.home-assistant.io/) [![Donate via PayPal](https://img.shields.io/badge/PayPal-Donate-blue?logo=paypal)](https://www.paypal.com/donate/?hosted_button_id=AAWFZVF2XCP5A)  
![Script](https://img.shields.io/badge/logo-yaml-green?logo=yaml)  
[![Български](https://img.shields.io/badge/BG_Български-език-green?logo=translate&labelColor=gray&style=flat-square&link=https://example.com/bg  
)](BG.md)  
[![Deutch](https://img.shields.io/badge/DE_Deutsche-sprache-green?logo=translate&labelColor=gray&style=flat-square&link=https://example.com/bg  
)](DE.md)  
[![English](https://img.shields.io/badge/EN_English-language-green?logo=translate&labelColor=gray&style=flat-square&link=https://example.com/bg)](README.md)  

Sprachsteuerung für Home Assistant-Geräte mit Alexa oder Google Home über Matter  

Dieses Repository bietet eine Integration zwischen Home Assistant und beliebten Sprachassistenten wie Amazon Alexa und Google Home unter Verwendung des neuen Matter-Protokolls. Sie können Ihre Smart-Geräte, Automatisierungen und Skripte einfach per Sprachbefehl steuern – für ein komfortableres, effizienteres und intuitiveres Zuhause.  

✅ Unterstützung für Sprachsteuerung von Lichtern, Steckdosen, Sensoren, Szenen, Skripten und mehr.  
✅ Einfache Schritte zur Verbindung über einen Matter-Hub.  
✅ Mehrsprachige Unterstützung (Englisch/Deutsch).  
✅ Regelmäßig getestet und aktualisiert.  

👉 Ideal für Nutzer, die die Leistungsfähigkeit von Home Assistant mit dem Komfort von Sprachassistenten kombinieren möchten.  

---  

## 📦 Inhalt  

- [🎙️ SPRACHSTEUERUNG FÜR HASS-GERÄTE MIT ALEXA/GOOGLE HOME](#️-sprachsteuerung-für-hass-geräte-mit-alexagoogle-home)
	- [📦 Inhalt](#-inhalt)
	- [🕸️ Home-Assistant-Matter-Hub](#️-home-assistant-matter-hub)
		- [⚡ Installation](#-installation)
		- [🛠️ Erstellung/Konfiguration des Hubs](#️-erstellungkonfiguration-des-hubs)
		- [🔗 Hinzufügen einer Automatisierung/Aktionskombination/Skript:](#-hinzufügen-einer-automatisierungaktionskombinationskript)

---  

## 🕸️ Home-Assistant-Matter-Hub  
Dieses Projekt simuliert Bridges, um Ihre Home Assistant-Objekte für jeden Matter-kompatiblen Controller wie Alexa, Apple Home oder Google Home verfügbar zu machen. Mit Matter können sie einfach über lokale Kommunikation verbunden werden, ohne Portweiterleitung oder ähnliches zu benötigen.<br>  

### ⚡ Installation  

Klicken Sie, um das Add-on-Repository hinzuzufügen:<br>  

[![ADD REPO](/img/button%20ADD%20ADD-ON%20REPOSITORY%20TO%20MY.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Ft0bst4r%2Fhome-assistant-addons%2F)  

> Ergebnis:  

![ADDON](/img/repo_ist_add.png)  

> [!NOTE]  
> Wenn Sie das Add-on nach dem Hinzufügen des Repositories nicht sehen, aktualisieren Sie die Seite!  

> Installation des Add-ons  

![install](/img/install.png)  

> [!NOTE]  
> Das Add-on benötigt keine zusätzlichen Einstellungen. Starten Sie es direkt nach einem Neustart des Systems.  

![start addon](/img/start_addon.png)  

### 🛠️ Erstellung/Konfiguration des Hubs  
> Erstellen Sie ein Label, das an `MatterHub` erinnert:  

![new labels](/img/new_labels.png)  

> Öffnen Sie das Add-on und klicken Sie auf `CREATE NEW BRIDGES`  

![my briges](/img/new_bridges.png)  

> Konfigurieren Sie den neuen Hub wie im Bild gezeigt:  

![config](/img/config_bridges.png)  

Nachdem Sie die Konfiguration ausgefüllt haben, speichern Sie sie und starten Sie das Add-on neu.  

> [!NOTE]  
> Um ein Gerät zum neuen Hub hinzuzufügen, weisen Sie ihm das Label `MatterHub` zu und starten Sie das Add-on neu.  

> Ergebnis:  
![img](/img/installed.png)  

### 🔗 Hinzufügen einer Automatisierung/Aktionskombination/Skript:  
Um eine "Automatisierung/Aktionskombination/Skript" zu aktivieren, verwenden Sie "Helfer", die Sie in "Automatisierung/Aktionskombination/Skript" einfügen und die Aktion(en) auslösen.  

Beispiele für "Helfer":  

![button helper](/img/button_helper.png)  

oder  

![boolean helper](/img/boolean_helper.png)  

---  
> [!TIP]  
> Wenn Ihnen dieses Projekt gefallen hat, finden Sie [HIER](https://github.com/Bacard1?tab=repositories) weitere interessante Repositories von mir.<br>  
> Wenn Sie auf Schwierigkeiten stoßen oder Fragen haben, zögern Sie nicht, mich zu kontaktieren.  