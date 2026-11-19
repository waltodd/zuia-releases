# Zuia releases

Public downloads for **Zuia** by Uhuru Compliance: the desktop installers for Windows (MSI, EXE), macOS (DMG) and
Linux (DEB), with `SHA256SUMS.txt`.

This repository holds releases only. The source is in `waltodd/api.zuia.uhurucompliance.com`; its workflow
`.github/workflows/desktop-release.yml` builds the installers on each `v*` tag and publishes them here
(repository variable `PUBLIC_RELEASES_REPO=waltodd/zuia-releases`, secret `RELEASES_TOKEN`).

Latest installers:

- https://github.com/waltodd/zuia-releases/releases/latest/download/Zuia-windows-x64.msi
- https://github.com/waltodd/zuia-releases/releases/latest/download/Zuia-windows-x64.exe
- https://github.com/waltodd/zuia-releases/releases/latest/download/Zuia-macos-arm64.dmg
- https://github.com/waltodd/zuia-releases/releases/latest/download/Zuia-linux-amd64.deb
