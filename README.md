# Rodarion CLI — Distribution

Public distribution repository for the **Rodarion CLI** — a command-line tool to
push and pull Rodarion language-resource data via the REST API.

The CLI's source code is maintained in a separate, private repository. This repo
exists so the compiled binaries and packages are **publicly downloadable without
authentication**; every release here is produced automatically by CI.

## Install

**Homebrew** (macOS and Linux/Ubuntu via Linuxbrew):

```bash
brew install cubera-ch/tap/rodarion
```

**Scoop** (Windows):

```bash
scoop bucket add cubera-ch https://github.com/cubera-ch/scoop-bucket
scoop install rodarion
```

**Native package / manual download** — grab the matching asset from the
[latest release](https://github.com/cubera-ch/rodarion-dist/releases/latest):

```bash
sudo apt install ./rodarion_<version>_linux_amd64.deb      # Debian/Ubuntu
sudo rpm -i     rodarion_<version>_linux_amd64.rpm         # Fedora/RHEL
sudo pacman -U  rodarion_<version>_linux_amd64.pkg.tar.zst # Arch
```

Each release also ships a `checksums.txt` for verification.

## Manufacturer, support and security

The Rodarion CLI is made by Cubera Solutions AG, General-Wille-Strasse 96,
8706 Feldmeilen, Switzerland ([info@cubera.ch](mailto:info@cubera.ch),
[www.rodarion.com](https://www.rodarion.com)).

- **Support period:** at least until 27 July 2031. Security updates ship as new releases,
  so always use the latest one.
- **Security vulnerabilities:** report them to
  [security@cubera.ch](mailto:security@cubera.ch). Our
  [disclosure policy](https://www.cubera.ch/security/) explains how we handle reports.

## License

The Rodarion CLI is proprietary software © Cubera Solutions AG. The license text
is bundled with every release archive and package.
