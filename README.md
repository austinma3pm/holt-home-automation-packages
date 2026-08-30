# Holt Home Automation packages

This public repository contains only verified, signed desktop-client binaries.
The private server source, configuration, credentials, and camera information
are not published here.

## CachyOS / Arch Linux

Import and locally trust `holt-home-automation-signing-key.asc`, then add this
repository to `/etc/pacman.conf`:

```ini
[holt-home-automation]
SigLevel = PackageRequired DatabaseRequired
Server = https://austinma3pm.github.io/holt-home-automation-packages/$arch
```

The package name is `holt-home-automation-desktop`.
