<div align="center">
  <img alt="Lizard Logo" src="https://image.flaticon.com/icons/svg/178/178396.svg" height="140" />
  <h3 align="center">Lizard - Simplify Linux Servers</h3>
  <p><em>Managing your own Linux server has never been easier.</em></p>
</div>

<p align="center">
  <a href="https://travis-ci.org/riipandi/lizard"><img src="https://travis-ci.org/riipandi/lizard.svg" alt="Build Status"></a>
  <a href="https://GitHub.com/riipandi/lizard/releases/"><img src="https://img.shields.io/github/downloads/riipandi/lizard/total.svg" alt="Github all releases"></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License"></a>
</p>

---

Lizard is a simple CLI application for managing your Linux Server just like
[EasyEngine](https://easyengine.io/), [CentminMod](https://centminmod.com/) and
[Webinoly](https://webinoly.com/en/). Install the server stack and configure your
instance in the cloud of Google Cloud Platform, Amazon Web Services, DigitalOcean
or any of your preference. Current focus is making it for the Debian distribution.

This project adheres to the Contributor Covenant [code of conduct](CODE_OF_CONDUCT.md).
By participating, you are expected to uphold this code. For questions send an email to
ripandi@pm.me.

__Important Note:__ *This project still heavy development, not ready to use at production server.*

## Features and TODO

- [ ] LEMP Installater
- [ ] VirtualHost Manager
- [ ] Let's Encrypt Generator
- [ ] MySQL Management
- [ ] PgSQL Management
- [ ] FTP User Management
- [ ] Mail User Management
- [ ] DNS Record Management
- [ ] Domain availability checker
- [ ] Send detailed information via email
- [ ] *You add here*

## Requirements

You will need a fresh [Debian 9.x (Stretch)](https://debian.org/) installation and public IP address.

## Installation

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/lizard)

You can download binaries at [release page](https://github.com/riipandi/lizard/releases) or using wget.

#### Using wget

```bash
# First download the lizard binary
wget -O /usr/local/bin/lizard https://xxxxxxxx.xxx/lizard

# Then make it executable
chmod +x /usr/local/bin/lizard
```

#### Using Snapcraft

```bash
sudo snap install lizard --edge
```

## Usage

#### Basic usage

It's simple, just run `lizard <COMMAND>`

Use `lizard` or `lizard -h` to show usage and a list of commands

## Things to know

This project written in [Golang](https://golang.org/) and use
[SPF13 Cobra](https://github.com/spf13/cobra) library. For detailed
explanation on how things work, checkout their documentation.

## Contributing

Contributions to this project are welcome and encouraged. Lizard is a
personal project by [Aris Ripandi](https://aris.web.id).

## License

This project is open-sourced software licensed under the [MIT license](./LICENSE).
