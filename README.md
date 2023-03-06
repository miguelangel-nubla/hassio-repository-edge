# miguelangel-nubla Home Assistant Add-ons

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

## About

Home Assistant allows anyone to create add-on repositories to share their
add-ons for Home Assistant easily. This repository is one of those repositories,
providing extra Home Assistant add-ons for your installation.

The primary goal of this project is to provide you (as a Home Assistant user)
with additional, high quality, add-ons that allow you to take your automated
home to the next level.

## Installation

In general, there is no need to install this repository on your
Home Assistant instance. It is activated and added by Home Assistant
by default.

However, if the repository is missing on your setup, adding this add-ons
repository to your Home Assistant instance is pretty easy. In the
Home Assistant add-on store, a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/miguelangel-nubla/hassio-repository
```

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

[addon-step-ca-client]: https://github.com/miguelangel-nubla/hassio-step-ca-client/tree/v0.1.0
[addon-doc-step-ca-client]: https://github.com/miguelangel-nubla/hassio-step-ca-client/blob/v0.1.0/README.md
[step-ca-client-issue]: https://github.com/miguelangel-nubla/hassio-step-ca-client/issues
[step-ca-client-version-shield]: https://img.shields.io/badge/version-v0.1.0-blue.svg
[step-ca-client-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[step-ca-client-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[step-ca-client-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[step-ca-client-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[step-ca-client-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[gitlabci-shield]: https://gitlab.com/miguelangel-nubla/hassio-repository/badges/master/pipeline.svg
[gitlabci]: https://gitlab.com/miguelangel-nubla/hassio-repository/pipelines
[issue]: https://github.com/miguelangel-nubla/hassio-repository/issues
[license-shield]: https://img.shields.io/github/license/miguelangel-nubla/hassio-repository.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2023.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[semver]: http://semver.org/spec/v2.0.0.html