# Home Assistant App: GoDaddy Dynamic DNS Updater

Automatically update your GoDaddy DNS IP address with integrated HTTPS support via Let's Encrypt.

[![Release][release-shield]][release]
![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]

## About

This app updates your DNS records that are hosted on [GoDaddy][godaddy] to an IP address of your choice.
It includes the support for creating and renewing your Let's Encrypt certificate automatically.

**You must have a domain hosting account with GoDaddy and must have a GoDaddy API key before being able to use this
app.**

*This is a modified version of [mrmichaelrb's][mrmichaelrb] GoDaddy Dynamic DNS Updater - so all credit goes to him! Thanks!*

## WARNING! THIS IS AN EDGE VERSION!

This Home Assistant Apps repository contains edge builds of apps.
Edge builds apps are based upon the latest development version.

- They may not work at all.
- They might stop working at any time.
- They could have a negative impact on your system.

This repository was created for:

- Anybody willing to test.
- Anybody interested in trying out upcoming apps or app features.
- Developers.

If you are more interested in stable releases of our apps:

<https://github.com/mreditor97/homeassistant-apps>


[release-shield]: https://img.shields.io/badge/version-4e89547-blue.svg
[release]: https://github.com/mreditor97/app-ddns-godaddy/tree/4e89547
[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[godaddy]: https://www.godaddy.com
[mrmichaelrb]: https://github.com/mrmichaelrb/hassio-addons