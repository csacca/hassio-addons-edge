# hassio-addons-edge

Christopher Sacca's Home Assistant Add-ons

This is a repository for experimental hass.io add-ons.

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

## WARNING! THIS IS AN EDGE REPOSITORY

This Home Assistant Add-ons repository contains edge builds of add-ons. Edge
builds add-ons are based upon the latest development version.

- They may not work at all.
- They might stop working at any time.
- They could have a negative impact on your system.

This repository was created for:

- Anybody willing to test.
- Anybody interested in trying out upcoming add-ons or add-on features.
- Developers.

If you are more interested in stable releases of our add-ons:

<https://github.com/csacca/hassio-addons>

## Installation

Adding this add-ons repository to your Home Assistant instance is
pretty straightforward. In the Home Assistant add-on store,
a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/csacca/hassio-addons-edge
```

## Add-ons provided by this repository

### &#10003; [MQTT Explorer][addon-mqtt-explorer]

![Latest Version][mqtt-explorer-version-shield]
![Supports armhf Architecture][mqtt-explorer-armhf-shield]
![Supports armv7 Architecture][mqtt-explorer-armv7-shield]
![Supports aarch64 Architecture][mqtt-explorer-aarch64-shield]
![Supports amd64 Architecture][mqtt-explorer-amd64-shield]
![Supports i386 Architecture][mqtt-explorer-i386-shield]

Home Assistant addon for MQTT Explorer

[:books: MQTT Explorer add-on documentation][addon-doc-mqtt-explorer]

### &#10003; [rtl_433 to MQTT][addon-rtl_433-mqtt]

![Latest Version][rtl_433-mqtt-version-shield]
![Supports armhf Architecture][rtl_433-mqtt-armhf-shield]
![Supports armv7 Architecture][rtl_433-mqtt-armv7-shield]
![Supports aarch64 Architecture][rtl_433-mqtt-aarch64-shield]
![Supports amd64 Architecture][rtl_433-mqtt-amd64-shield]
![Supports i386 Architecture][rtl_433-mqtt-i386-shield]

rtl_443 to MQTT add-on

[:books: rtl_433 to MQTT add-on documentation][addon-doc-rtl_433-mqtt]

## Releases

Add-on releases are **NOT** based on [Semantic Versioning][semver], unlike
all our other repositories. The latest build commit SHA hash of each
add-on, represents the version number.

## Support

Got questions?

You have several options to get them answered:

- Join the [Reddit subreddit][reddit] in [/r/homeassistant][reddit]

You could also open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: MQTT Explorer][mqtt-explorer-issue]
- [Open an issue for the add-on: rtl_433 to MQTT][rtl_433-mqtt-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## Contributing

This is an active open-source project. We are always open to people who want to
use the code or contribute to it.

We have set up a separate document containing our
[contribution guidelines](CONTRIBUTING.md).

Thank you for being involved! :heart_eyes:

## License

MIT License

Copyright (c) 2021 Christopher Sacca

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[addon-mqtt-explorer]: https://github.com/csacca/addon-mqtt-explorer/tree/beb3a1b
[addon-doc-mqtt-explorer]: https://github.com/csacca/addon-mqtt-explorer/blob/beb3a1b/README.md
[mqtt-explorer-issue]: https://github.com/csacca/addon-mqtt-explorer/issues
[mqtt-explorer-version-shield]: https://img.shields.io/badge/version-beb3a1b-blue.svg
[mqtt-explorer-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[mqtt-explorer-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[mqtt-explorer-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[mqtt-explorer-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[mqtt-explorer-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-rtl_433-mqtt]: https://github.com/csacca/addon-rtl_433-mqtt/tree/df2e7e7
[addon-doc-rtl_433-mqtt]: https://github.com/csacca/addon-rtl_433-mqtt/blob/df2e7e7/README.md
[rtl_433-mqtt-issue]: https://github.com/csacca/addon-rtl_433-mqtt/issues
[rtl_433-mqtt-version-shield]: https://img.shields.io/badge/version-df2e7e7-blue.svg
[rtl_433-mqtt-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[rtl_433-mqtt-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[rtl_433-mqtt-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[rtl_433-mqtt-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[rtl_433-mqtt-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[csacca]: https://github.com/csacca
[issue]: https://github.com/csacca/hassio-addons-edge/issues
[license-shield]: https://img.shields.io/github/license/csacca/hassio-addons-edge.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2021.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-experimental-yellow.svg
[reddit]: https://reddit.com/r/homeassistant
[semver]: http://semver.org/spec/v2.0.0.html
[third-party-addons]: https://home-assistant.io/hassio/installing_third_party_addons/