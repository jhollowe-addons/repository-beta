# BETA - jhollowe's Home Assistant Addons

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)


## WARNING! THIS IS A BETA REPOSITORY

This Home Assistant Add-ons repository contains beta releases of add-ons.

- They might stop working at any time.
- They could have a negative impact on your system.

This repository was created for:

- Anybody willing to test.
- Anybody interested in trying out upcoming add-ons or add-on features.

If you are more interested in stable releases of our add-ons:

<https://github.com/jhollowe-addons/repository>

## Installation

Adding this add-ons repository to your Home Assistant instance is
pretty straightforward. In the Home Assistant add-on store,
a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/jhollowe-addons/repository-beta
```

## Add-ons provided by this repository

### &#10003; [ser2net server][addon-ser2net]

![Latest Version][ser2net-version-shield]
![Supports armhf Architecture][ser2net-armhf-shield]
![Supports armv7 Architecture][ser2net-armv7-shield]
![Supports aarch64 Architecture][ser2net-aarch64-shield]
![Supports amd64 Architecture][ser2net-amd64-shield]
![Supports i386 Architecture][ser2net-i386-shield]

Expose serial ports over the network, including RFC2217 support for remote port settings change (e.g. baud rate or RTS)


[:books: ser2net server add-on documentation][addon-doc-ser2net]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

The beta add-ons will also have an additional beta marker, unless, the
stable release is newer, in that case, the stable release is published
in this channel.

## Support

You can open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: ser2net server][ser2net-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## Contributing

This is an active open-source project. We are always open to people who want to
use the code or contribute to it.

We have set up a separate document containing our
[contribution guidelines](.github/CONTRIBUTING.md).

Thank you for being involved! :heart_eyes:

## Adding a new add-on

We are currently not accepting third party add-ons to this repository.

[addon-ser2net]: https://github.com/jhollowe-addons/addon-ser2net/tree/v0.0.2
[addon-doc-ser2net]: https://github.com/jhollowe-addons/addon-ser2net/blob/v0.0.2/README.md
[ser2net-issue]: https://github.com/jhollowe-addons/addon-ser2net/issues
[ser2net-version-shield]: https://img.shields.io/badge/version-v0.0.2-blue.svg
[ser2net-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[ser2net-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[ser2net-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[ser2net-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[ser2net-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[issue]: https://github.com/jhollowe-addons/repository-beta/issues
[license-shield]: https://img.shields.io/github/license/jhollowe-addons/repository-beta.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2025.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-development-yellowgreen.svg
[semver]: http://semver.org/spec/v2.0.0.html