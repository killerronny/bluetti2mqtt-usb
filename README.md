# Bluetti to MQTT USB

![update-badge](https://img.shields.io/github/last-commit/killerronny/bluetti2mqtt-usb?label=Last%20Updated)

## Installation
To add this repository to Home Assistant use the badge below:

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fkillerronny%2Fbluetti2mqtt-usb)

Or add it manually by navigating to `Settings` > `Add-ons` > `Add-on Store`.

Click the three-dot menu in the upper right, choose `Repositories`, and add the following URL:

```
https://github.com/killerronny/bluetti2mqtt-usb
```


Refresh the page (hard refresh may be required), scroll down to **Bluetti to MQTT USB** and install the add-on.

## Add-ons

This repository contains the following add-on:

### [Bluetti2MQTT USB](./bluetti2mqtt-usb)

![Supports aarch64 Architecture][aarch64-shield]  
![Supports amd64 Architecture][amd64-shield]  
![Supports armhf Architecture][armhf-shield]  
![Supports armv7 Architecture][armv7-shield]  
![Supports i386 Architecture][i386-shield]

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg  
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg  
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg  
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg  
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg  

---

MQTT bridge between a second Bluetti device (via USB-Bluetooth dongle) and Home Assistant.
This is a forked version for parallel use with the original [SSMCD/bluetti2mqtt](https://github.com/SSMCD/bluetti2mqtt).


bluetti2mqtt-usb/
├── config.json
├── Dockerfile
├── run.sh
├── ...
README.md
repository.yaml
