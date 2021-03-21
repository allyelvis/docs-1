---
id: usage
title: Using the CLI
sidebar_label: Usage
slug: /cli/usage
---

The CLI can help you manage [themes](/customization/themes) and [plugins](/customization/plugins), create them and open Squid from anywhere.

Run `squid --help` for a list of commands:
```shell
Usage: squid [options] [command]

Commands:
  squid [path]            Launch Squid                                 [default]
  squid install <name>    Install a theme or plugin            [aliases: i, add]
  squid uninstall <name>  Uninstall a theme or plugin       [aliases: u, remove]
  squid list              List installed themes and plugins        [aliases: ls]
  squid new [name]        Initialize a new theme or plugin

Options:
  --help     Show help                                                 [boolean]
  --version  Show version number                                       [boolean]
```
