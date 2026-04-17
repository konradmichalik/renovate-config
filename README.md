<div align="center">

# Renovate config

[![CGL](https://github.com/konradmichalik/renovate-config/actions/workflows/cgl.yml/badge.svg)](https://github.com/konradmichalik/renovate-config/actions/workflows/cgl.yml)
[![Release](https://github.com/konradmichalik/renovate-config/actions/workflows/release.yml/badge.svg)](https://github.com/konradmichalik/renovate-config/actions/workflows/release.yml)
[![License](https://img.shields.io/github/license/konradmichalik/renovate-config)](LICENSE)

</div>

This repository contains my personal [renovate](https://docs.renovatebot.com/) configuration used as base for my projects. It is not meant to be used anywhere else.

## 🗂️ Presets

- `default.json` - Default configuration for all projects
- `typo3-extension.json` - Configuration for TYPO3 extensions
- `typo3-projects.json` - Configuration for TYPO3 projects

## ⚡ Usage

```json
{
    "$schema": "https://docs.renovatebot.com/renovate-schema.json",
    "extends": [
        "github>konradmichalik/renovate-config"
    ]
}
```

## ⭐ License

This project is licensed under [GNU General Public License 3.0 (or later)](LICENSE).
