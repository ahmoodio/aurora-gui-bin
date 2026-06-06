
# aurora-gui-bin

<div align="center">
  <img src="https://raw.githubusercontent.com/ahmoodio/aurora/main/assets/logo.png" alt="Aurora logo" width="120"/>

  <p><em>Prebuilt Arch Linux package for <a href="https://github.com/ahmoodio/aurora">Aurora</a></em></p>

  [![AUR](https://img.shields.io/aur/version/aurora-gui-bin?style=flat&color=7C3AED&logo=arch-linux&logoColor=white)](https://aur.archlinux.org/packages/aurora)
  [![License](https://img.shields.io/github/license/ahmoodio/aurora?style=flat&color=7C3AED)](https://github.com/ahmoodio/aurora/blob/main/LICENSE)
</div>

---

## What is this?

This is the AUR package for [Aurora](https://github.com/ahmoodio/aurora), a modern GTK4 GUI for Arch Linux package management. It installs prebuilt binaries from the official [GitHub releases](https://github.com/ahmoodio/aurora/releases).

## Install

```bash
# Using yay
yay -S aurora-gui-bin

# Using paru
paru -S aurora-gui-bin
```

## Dependencies

- `gtk4`
- `libadwaita`
- `vulkan-icd-loader`
- `openssl`
- `zlib`
- `libssh2`

### Optional

| Package | Purpose |
|---------|---------|
| `yay` or `paru` | AUR support |
| `flatpak` | Flatpak package management |

## What gets installed

| File | Location |
|------|----------|
| `aurora` | `/usr/bin/aurora` |
| `aurora-helper` | `/usr/bin/aurora-helper` |
| Desktop entry | `/usr/share/applications/io.github.ahmoodio.aurora.desktop` |
| Metainfo | `/usr/share/metainfo/io.github.ahmoodio.aurora.metainfo.xml` |
| Polkit policy | `/usr/share/polkit-1/actions/io.github.ahmoodio.aurora.policy` |
| Icons | `/usr/share/icons/hicolor/` |

## Links

- [Aurora Source](https://github.com/ahmoodio/aurora)
- [Releases](https://github.com/ahmoodio/aurora/releases)
- [AUR Package](https://aur.archlinux.org/packages/aurora-gui-bin)
