## WARNING! THIS IS AN EDGE VERSION!

This Home Assistant Add-ons repository contains edge builds of add-ons.
Edge builds add-ons are based upon the latest development version.

- They may not work at all.
- They might stop working at any time.
- They could have a negative impact on your system.

This repository was created for:

- Anybody willing to test.
- Anybody interested in trying out upcoming add-ons or add-on features.
- Developers.

If you are more interested in stable releases of my add-ons:

<https://github.com/miguelangel-nubla/hassio-repository>

# miguelangel-nubla Home Assistant Add-ons

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

## Installation

The installation of this add-on is pretty straightforward and not different
compared to installing any other Home Assistant add-on.

1. First you will need to add this repository to your add-on store with the
   following button:

   [![Add the add-on repository to your Home Assistant instance.][addon-add-repo-badge]][addon-add-repo]

2. Click on ADD to complete adding the repository.
3. Browse the Add-on Store for the section `miguelangel-nubla Home Assistant Add-ons` and install the add-on you need.

## Add-ons provided by this repository

### &#10003; [step-ca-client][addon-step-ca-client]

![Latest Version][step-ca-client-version-shield]
![Supports armhf Architecture][step-ca-client-armhf-shield]
![Supports armv7 Architecture][step-ca-client-armv7-shield]
![Supports aarch64 Architecture][step-ca-client-aarch64-shield]
![Supports amd64 Architecture][step-ca-client-amd64-shield]
![Supports i386 Architecture][step-ca-client-i386-shield]

SSL/TLS certificates from your own PKI

[:books: step-ca-client add-on documentation][addon-doc-step-ca-client]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

You could open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: step-ca-client][step-ca-client-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

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

[addon-add-repo]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fmiguelangel-nubla%2Fhassio-repository-edge
[addon-add-repo-badge]: https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg
[addon-step-ca-client]: https://github.com/miguelangel-nubla/hassio-step-ca-client/tree/4e34f07
[addon-doc-step-ca-client]: https://github.com/miguelangel-nubla/hassio-step-ca-client/blob/4e34f07/README.md
[step-ca-client-issue]: https://github.com/miguelangel-nubla/hassio-step-ca-client/issues
[step-ca-client-version-shield]: https://img.shields.io/badge/version-4e34f07-blue.svg
[step-ca-client-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[step-ca-client-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[step-ca-client-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[step-ca-client-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[step-ca-client-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[gitlabci-shield]: https://gitlab.com/miguelangel-nubla/hassio-repository-edge/badges/master/pipeline.svg
[gitlabci]: https://gitlab.com/miguelangel-nubla/hassio-repository-edge/pipelines
[issue]: https://github.com/miguelangel-nubla/hassio-repository-edge/issues
[license-shield]: https://img.shields.io/github/license/miguelangel-nubla/hassio-repository-edge.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2023.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[semver]: http://semver.org/spec/v2.0.0.html