# Folio releases

Installers for **Folio**, a page-layout editor for Windows 11 that opens Microsoft Publisher
files. This repository holds release files only; Folio's source code is private.

**Download the latest version:**
[Folio-windows-x64.msi](https://github.com/labmsau/folio-releases/releases/latest/download/Folio-windows-x64.msi)

Run the MSI to install Folio, or to upgrade an installed copy in place. Once installed, Folio
checks here for new versions and offers to install them.

Each release also carries `latest.json` and `latest.json.sig`: the version, size and SHA-256 of
the installer, signed with Folio's update key. Folio installs an update only when that signature
and the installer's size and checksum match. The installers are not yet code-signed.
