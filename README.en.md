<div align="center">
  <img src="./docs/images/server-icon.png" alt="ScrapeFun Server" width="80" />
  <h1>ScrapeFun Server for Windows</h1>
  <p><a href="./README.md">简体中文</a> · <strong>English</strong></p>
  <p><a href="https://scrapefun.com/?lang=en">Website</a> · <a href="https://apps.microsoft.com/detail/9N83B6RSWG01">Microsoft Store</a> · <a href="https://scrapefun.com/?lang=en#/docs">Documentation</a></p>
</div>

> Updated: 2026-11-03. Versions and assets below are the stable releases checked on this date. Follow the corresponding Release for later changes.

A Windows system-tray host with the ScrapeFun Server runtime and a management interface in your default browser. Manage movie, TV, comic, and remote WebDAV / AList libraries, and let Clients on your LAN connect.

## Install from Microsoft Store

The x64 Windows edition is distributed through Microsoft Store. Check the product page for available versions and system requirements.

[Microsoft Store](https://apps.microsoft.com/detail/9N83B6RSWG01)

## Installation and first launch

1. Install from Microsoft Store and open ScrapeFun Server.
2. Open the ScrapeFun web interface from the system tray. The default address is `http://127.0.0.1:8096`.
3. For a new instance, follow the web setup to configure administrator credentials, storage, and libraries.
4. Enable LAN access and check the firewall when other devices need to connect.

Existing instances continue using their existing accounts. An older version's initial-password log workflow should not be assumed to apply to all new versions.

## System tray and data directory

The tray menu provides actions to open the web interface, restart the service, view data and logs, start with Windows, control LAN access, and check for updates.

Runtime data defaults to:

```text
%APPDATA%\ScrapeFunDesktop
```

Business data is in `data` and logs are in `logs`. These files live outside the installation directory; installer updates normally retain them. Deleting the user data directory affects the entire instance. Back up before doing so.

## Updates

Microsoft Store handles updates. Before switching from an older EXE installation, export a full backup from Server settings, exit and uninstall the old application, install the Store version, and restore the backup. Keep your original media files available.

## Support and licensing

This repository provides installation instructions and an archive of previous releases. Submit usage questions and feature requests to the [main repository Issues](https://github.com/HaoweiLi97/ScrapeFun/issues). For accounts, activation, or private logs, contact `scrapefun@outlook.com`. Report security issues privately according to the [security instructions](./SECURITY.en.md).

See the new [commercial license statement](./LICENSE.en.txt) and full [software license agreement](./EULA.en.md). Ordinary personal, household, and internal organizational use is allowed. Pro requires a valid entitlement. Software redistribution, resale, customer delivery, and paid hosting require separate written authorization. The statement does not retroactively change existing licenses; existing assets follow their supplied licenses, and third-party components retain their own licenses.

[Releases and compatibility](https://github.com/HaoweiLi97/ScrapeFun/blob/main/RELEASE_POLICY.en.md) · [Third-party components](https://github.com/HaoweiLi97/ScrapeFun/blob/main/THIRD_PARTY_NOTICES.en.md) · [Support](./SUPPORT.en.md)
