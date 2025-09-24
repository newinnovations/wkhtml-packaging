# Binary (amd64) releases of wkhtmltopdf 0.12.6.1

The wkhtmltopdf project was archived at version 0.12.6.1, but I still use it
in my projects. This repo provides binary releases (both full .deb files
and just the wkhtmltopdf executable) through github actions for current (amd64)
versions of Debian and Ubuntu. This includes Ubuntu 24.04 (noble), which uses
g++ 13 by default and required some patching of the Qt configure script.

## wkhtmltopdf

- Debian 13: [trixie](https://github.com/newinnovations/wkhtml-packaging/releases/download/v0.12.6.1/wkhtmltopdf_0.12.6.1-trixie_amd64)
- Debian 12: [bookworm](https://github.com/newinnovations/wkhtml-packaging/releases/download/v0.12.6.1/wkhtmltopdf_0.12.6.1-bookworm_amd64)
- Debian 11: [bullseye](https://github.com/newinnovations/wkhtml-packaging/releases/download/v0.12.6.1/wkhtmltopdf_0.12.6.1-bullseye_amd64)
- Ubuntu 24.04: [noble](https://github.com/newinnovations/wkhtml-packaging/releases/download/v0.12.6.1/wkhtmltopdf_0.12.6.1-noble_amd64)
- Ubuntu 22.04: [jammy](https://github.com/newinnovations/wkhtml-packaging/releases/download/v0.12.6.1/wkhtmltopdf_0.12.6.1-jammy_amd64)
- Ubuntu 20.04: [focal](https://github.com/newinnovations/wkhtml-packaging/releases/download/v0.12.6.1/wkhtmltopdf_0.12.6.1-focal_amd64)

## wkhtmltox.deb

- Debian 13: [trixie](https://github.com/newinnovations/wkhtml-packaging/releases/download/v0.12.6.1/wkhtmltox_0.12.6.1-trixie_amd64.deb)
- Debian 12: [bookworm](https://github.com/newinnovations/wkhtml-packaging/releases/download/v0.12.6.1/wkhtmltox_0.12.6.1-bookworm_amd64.deb)
- Debian 11: [bullseye](https://github.com/newinnovations/wkhtml-packaging/releases/download/v0.12.6.1/wkhtmltox_0.12.6.1-bullseye_amd64.deb)
- Ubuntu 24.04: [noble](https://github.com/newinnovations/wkhtml-packaging/releases/download/v0.12.6.1/wkhtmltox_0.12.6.1-noble_amd64.deb)
- Ubuntu 22.04: [jammy](https://github.com/newinnovations/wkhtml-packaging/releases/download/v0.12.6.1/wkhtmltox_0.12.6.1-jammy_amd64.deb)
- Ubuntu 20.04: [focal](https://github.com/newinnovations/wkhtml-packaging/releases/download/v0.12.6.1/wkhtmltox_0.12.6.1-focal_amd64.deb)

Warning: **Do not use wkhtmltopdf with any untrusted HTML**
