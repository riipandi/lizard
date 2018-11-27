# Wizard - Simplify Linux Servers

This is a simple CLI application for managing Linux Server via terminal. The main focus now is for the Debian distribution.

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
