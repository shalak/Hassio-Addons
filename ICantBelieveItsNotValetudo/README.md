# ICantBelieveItsNotValetudo (Home Assistant Supervisor Addon)

This is the adaption of [ICantBelieveItsNotValetudo](https://github.com/Hypfer/ICantBelieveItsNotValetudo) as a Supervisor addon.

![Addon Stage][stage-badge]
![Supports aarch64 Architecture][aarch64-badge]
![Supports amd64 Architecture][amd64-badge]
![Supports armhf Architecture][armhf-badge]
![Supports armv7 Architecture][armv7-badge]
![Supports i386 Architecture][i386-badge]

[![Install on my Home Assistant][install-badge]][install-url]
[![Donate][donation-badge]][donation-url]

## Config

The configuration keys are identical to the [configuration of ICantBelieveItsNotValetudo](https://github.com/Hypfer/ICantBelieveItsNotValetudo/blob/master/README.md).
Please get the meaning for them from there.
It's normal that the structure of the addon differs from the official config file, this is nessesary because of the Supervisor Addon config structure.

If you use the Mosquitto Addon in Home Assistant `core-mosquitto` can be used as broker address like this: `mqtt://<user>:<password>@core-mosquitto`.

## PNG image

The generated image will be served over the Supervisor Ingress feature. So the floor plan can be accessed via the build-in side panel and the auto-configured mqtt camera.

[aarch64-badge]: https://img.shields.io/badge/aarch64-yes-green.svg?style=for-the-badge
[amd64-badge]: https://img.shields.io/badge/amd64-yes-green.svg?style=for-the-badge
[armhf-badge]: https://img.shields.io/badge/armhf-yes-green.svg?style=for-the-badge
[armv7-badge]: https://img.shields.io/badge/armv7-yes-green.svg?style=for-the-badge
[i386-badge]: https://img.shields.io/badge/i386-yes-green.svg?style=for-the-badge
[install-url]: https://my.home-assistant.io/redirect/supervisor_addon?addon=243ffc37_icantbelieveitsnotvaletudo
[stage-badge]: https://img.shields.io/badge/Addon%20stage-stable-green.svg?style=for-the-badge

[install-badge]: https://img.shields.io/badge/Install%20on%20my-Home%20Assistant-41BDF5?logo=home-assistant&style=for-the-badge
[donation-badge]: https://img.shields.io/badge/Buy%20me%20a%20coffee-%23d32f2f?logo=buy-me-a-coffee&style=for-the-badge&logoColor=white
[donation-url]: https://www.buymeacoffee.com/Poeschl
