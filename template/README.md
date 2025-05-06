# Dashdot
![Version][version]
![Production ready][production-ready]
![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]
![Preview](https://github.com/user-attachments/assets/3d02ac66-3e03-498d-a5e2-0d5ce4b879aa)

## About
This addon is based on the [mauricenino/dashdot](https://hub.docker.com/r/mauricenino/dashdot) docker image and it allows user to see simple information about the host system via nice looking web interface.

## Installation
1. [Add my add-ons repository][repository] to your Home Assistant addons.
1. Install this add-on.
1. Edit add-on config as needed. At the moment you can only change exposed port, which is 3001 by default.
1. Start the add-on.
1. Check the logs of the add-on to see if everything went well. (As shown in the example below)
![Logs example](https://github.com/user-attachments/assets/2b6b83da-b986-4c12-b513-d93d3d1874a7)
1. Done, enjoy!

<!--
Assets
-->

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg

[version]: https://img.shields.io/badge/Version-0.0.2-orange.svg
[production-ready]: https://img.shields.io/badge/Production%20ready-Yes-green.svg

[repository]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https://github.com/Ondra9071/hassio-addons