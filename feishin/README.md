# Feishin
![Version][version]
![Production ready][production-ready]
![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]
![Preview][preview]

## About
This addon is based on the [jeffvli/feishin](https://ghcr.io/jeffvli/feishin:latest) docker image and it allows user to connect to jellyfin, navidrome or subsonic server to play music in a nice looking web interface.

## Installation
1. [Add my add-ons repository][repository] to your Home Assistant addons.
1. Install this add-on.
1. Edit add-on config as needed. At the moment you can only change exposed port, which is 9180 by default.
1. Start the add-on.
1. Check the logs of the add-on to see if everything went well.
1. Done, enjoy!

<!--
Assets
-->

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg

[version]: https://img.shields.io/badge/Version-0.0.1-orange.svg
[production-ready]: https://img.shields.io/badge/Production%20ready-yes-green.svg

[repository]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https://github.com/Ondra9071/hassio-addons
[preview]: https://i.imgur.com/2A7lKR5.png
