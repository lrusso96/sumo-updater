# sumo-updater

A simple PowerShell script to download and install SUMo.

## About

This script downloads the SUMo installer from the official website.
Then it starts the installation process, which needs to be manually completed by the user (for settings, custom installation, etc.).

## How to run

```
> & "sumo-updater.ps1" [-d] [-i]
```

### Flags

- **i**: skips the Installation dialog.
- **d**: skips the Download dialog.
