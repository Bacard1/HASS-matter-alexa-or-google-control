![BANNER](/img/banner.png)

# 🎙️ VOICE CONTROL OF HASS DEVICES WITH ALEXA/GOOGLE HOME
[![PayPal donation](https://img.shields.io/badge/PayPal-donation-синьо?logo=paypal)](https://www.paypal.com/donate/?hosted_button_id=AAWFZVF2XCP5A)
![Script](https://img.shields.io/badge/logo-yaml-green?logo=yaml)
[![Български](https://img.shields.io/badge/BG_Български-език-green?logo=translate&labelColor=gray&style=flat-square&link=https://example.com/bg)](BG.md)

Voice Control for Home Assistant Devices with Alexa or Google Home via Matter

This repository provides an integration between Home Assistant and popular voice assistants like Amazon Alexa and Google Home using the new Matter protocol. It allows you to control your smart devices, automations, and scripts via voice commands – making your smart home more accessible, efficient, and enjoyable.

✅ Supports voice control for lights, switches, sensors, scenes, scripts, and more.
✅ Easy integration steps with Matter Hub.
✅ Multilingual support (English/Bulgarian).
✅ Tested and regularly updated.

👉 Ideal for users who want to combine the power of Home Assistant with the convenience of voice assistants.

---

## 📦 Contents

- [🎙️ VOICE CONTROL OF HASS DEVICES WITH ALEXA/GOOGLE HOME](#️-voice-control-of-hass-devices-with-alexagoogle-home)
	- [📦 Contents](#-contents)
	- [🕸️ Home-Assistant-Matter-Hub](#️-home-assistant-matter-hub)
		- [⚡ Installation](#-installation)
		- [🛠️ Create/Configure the Hub](#️-createconfigure-the-hub)
		- [🔗 Add Automation/Action Sequence/Script:](#-add-automationaction-sequencescript)

---

## 🕸️ Home-Assistant-Matter-Hub
This project simulates bridges to expose your Home Assistant entities to any Matter-compatible controller like Alexa, Apple Home, or Google Home. With Matter, they can connect easily through local communication without the need for port forwarding, etc.<br>

### ⚡ Installation

Click to add the add-on repository:<br>

[![ADD REPO](/img/button%20ADD%20ADD-ON%20REPOSITORY%20TO%20MY.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Ft0bst4r%2Fhome-assistant-addons%2F)

> Result:

![ADDON](/img/repo_ist_add.png)

> [!NOTE]
> If you still don’t see the add-on after adding the repository, refresh the page!

> Install the ADD-ON

![install](/img/install.png)

> [!NOTE]
> The add-on requires no additional configuration. Go directly to start after restarting the system.

![start addon](/img/start_addon.png)

### 🛠️ Create/Configure the Hub
>Create a label that reminds you of `MatterHub`:

![new labels](/img/new_labels.png)

>Open the add-on and click `CREATE NEW BRIDGES`

![my briges](/img/new_bridges.png)

> Configure the new HUB as shown in the image:

![config](/img/config_bridges.png)

After filling out the configuration, save and restart the add-on.

> [!NOTE]
> To add a device to the new HUB, assign it the label `MatterHub` and restart the add-on

>Result:
![img](/img/installed.png)

### 🔗 Add Automation/Action Sequence/Script:
To activate "Automation/Action Sequence/Script" I use "Helpers" which I then add to "Automation/Action Sequence/Script" to trigger the action(s).

Examples of "Helpers":

![button helper](/img/button_helper.png)

or

![boolean helper](/img/boolean_helper.png)

---
> [!TIP]
> If you like this project, [HERE](https://github.com/Bacard1?tab=repositories) you can find more interesting repositories made by me.<br>
> If you encounter difficulties or have questions, don’t hesitate to contact me.
