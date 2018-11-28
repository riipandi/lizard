<div align="center">
  <img alt="Wizard Logo" src="https://image.flaticon.com/icons/svg/178/178396.svg" height="140" />
  <h3 align="center">Wizard - Simplify Linux Servers</h3>
  <p align="center">
    <em>Managing your own Linux server has never been easier.</em>
  </p>
</div>

<p align="center">
  <a href="https://travis-ci.org/riipandi/wizard"><img src="https://travis-ci.org/riipandi/wizard.svg" alt="Build Status"></a>
  <a href="https://GitHub.com/riipandi/wizard/releases/"><img src="https://img.shields.io/github/downloads/riipandi/wizard/total.svg" alt="Github all releases"></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License"></a>
</p>

---

Wizard is a CLI application for managing your Linux Server. Current focus is making it
for the Debian distribution. Install the server stack and configure your instance in
the cloud of Google Cloud Platform, Amazon Web Services, DigitalOcean or any of your
preference.

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

## Installation

You can download binaries at [release page](https://github.com/riipandi/wizard/releases) or using wget.

#### Using wget

```bash
# First download the wizard binary
wget -O /usr/local/bin/wizard https://xxxxxxxx.xxx/wizard

# Then make it executable
chmod +x /usr/local/bin/wizard
```

## Usage

#### Basic usage

It's simple, just run `wizard <COMMAND>`

Use `wizard` or `wizard -h` to show usage and a list of commands

## Things to know

This project use [Golang](https://golang.org/) and [SPF13 Cobra](https://github.com/spf13/cobra) library. For detailed explanation on how things work, checkout their documentation.

## Contributing

Contributions to this project are welcome and encouraged. Wizard is a personal project by [Aris Ripandi](https://aris.web.id).

## License

This project is open-sourced software licensed under the [MIT license](./LICENSE).
