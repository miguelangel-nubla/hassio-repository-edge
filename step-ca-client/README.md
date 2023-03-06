# Home Assistant Add-on: step-ca-client

[![GitHub Release][releases-shield]][releases]
![Project Stage][project-stage-shield]
[![License][license-shield]](LICENSE.md)

![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports i386 Architecture][i386-shield]

[![Github Actions][github-actions-shield]][github-actions]
![Project Maintenance][maintenance-shield]
[![GitHub Activity][commits-shield]][commits]

## About

This is an [step-ca][step-ca] client add-on for Home Assistant.

It manages the automatic creation and renewal of x509 certificates from a
remote step-ca PKI server, in order to enable TLS/SSL connections in
Home Assistant and the installed addons.

Here is a [quick-start guide][pki-guide] on how to setup step-ca.

With a Yubikey you can even set up setup a [hardware based, local PKI][pki-guide-yubikey].

[:books: Read the full add-on documentation][docs]

## Contributing

This is an active open-source project. We are always open to people who want to
use the code or contribute to it.

We have set up a separate document containing our
[contribution guidelines](.github/CONTRIBUTING.md).

Thank you for being involved! :heart_eyes:

## Authors & contributors

Addon created by [Miguel Angel Nubla][miguelangel-nubla] based on the
[addon-example][addon-example] repository by [Franck Nijhof][frenck].

For a full list of all authors and contributors,
check [the contributor's page][contributors].

## License

MIT License

Copyright (c) 2023 Miguel Angel Nubla <miguelangel.nubla@gmail.com>

Copyright (c) 2017-2023 Franck Nijhof <frenck@addons.community>

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

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[addon-example]: https://github.com/hassio-addons/addon-example
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[commits-shield]: https://img.shields.io/github/commit-activity/y/miguelangel-nubla/hassio-step-ca-client.svg
[commits]: https://github.com/miguelangel-nubla/hassio-step-ca-client/commits/main
[contributors]: https://github.com/miguelangel-nubla/hassio-step-ca-client/graphs/contributors
[docs]: https://github.com/miguelangel-nubla/hassio-step-ca-client/blob/main/step-ca-client/DOCS.md
[frenck]: https://github.com/frenck
[github-actions-shield]: https://github.com/miguelangel-nubla/hassio-step-ca-client/workflows/CI/badge.svg
[github-actions]: https://github.com/miguelangel-nubla/hassio-step-ca-client/actions
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[license-shield]: https://img.shields.io/github/license/miguelangel-nubla/hassio-step-ca-client.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2023.svg
[miguelangel-nubla]: https://github.com/miguelangel-nubla
[pki-guide]: https://smallstep.com/blog/build-a-tiny-ca-with-raspberry-pi-yubikey/
[pki-guide-yubikey]: https://smallstep.com/blog/build-a-tiny-ca-with-raspberry-pi-yubikey/
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[releases-shield]: https://img.shields.io/github/release/miguelangel-nubla/hassio-step-ca-client.svg
[releases]: https://github.com/miguelangel-nubla/hassio-step-ca-client/releases
[step-ca]: https://smallstep.com/docs/step-ca/installation