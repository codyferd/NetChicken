<div id="vscodium-logo" align="center">
    <br />
    <img src="./icons/stable/codium_cnl.svg" alt="VSCodium Logo" width="200"/>
    <h1>NetChicken</h1>
    <h3>New-age FOSS IDE with many distinguishing features, such as a cool NetChick.</h3>
</div>

## Table of Contents

- [Download/Install](#download-install)
  - [Install with Brew](#install-with-brew)
  - [Install with Windows Package Manager (WinGet)](#install-with-winget)
  - [Install with Chocolatey](#install-with-choco)
  - [Install with Scoop](#install-with-scoop)
  - [Install with snap](#install-with-snap)
  - [Install with Package Manager](#install-with-package-manager)
  - [Install on Arch Linux](#install-on-arch-linux)
  - [Flatpak Option](#flatpak)
- [Build](#build)
- [Why Does This Exist](#why)
- [More Info](#more-info)
- [Supported Platforms](#supported-platforms)

## <a id="download-install"></a>Download/Install

:tada: :tada:
Download latest release here:
[stable](https://github.com/VSCodium/vscodium/releases) or
[insiders](https://github.com/VSCodium/vscodium-insiders/releases)
:tada: :tada:

[More info / helpful tips are here.](https://github.com/VSCodium/vscodium/blob/master/docs/index.md)


#### <a id="install-with-brew"></a>Install with Brew (Mac)

If you are on a Mac and have [Homebrew](https://brew.sh/) installed:
```bash
# stable
brew install --cask vscodium

# insiders
brew install --cask vscodium@insiders
```

*Note for macOS users: if you can't open the App, please read [the following troubleshooting](https://github.com/VSCodium/vscodium/blob/master/docs/troubleshooting.md#macos).*

#### <a id="install-with-winget"></a>Install with Windows Package Manager (WinGet)

If you use Windows and have [Windows Package Manager](https://github.com/microsoft/winget-cli) installed:
```cmd
:: stable
winget install -e --id VSCodium.VSCodium

:: insider
winget install -e --id VSCodium.VSCodium.Insiders
```

#### <a id="install-with-choco"></a>Install with Chocolatey (Windows)

If you use Windows and have [Chocolatey](https://chocolatey.org) installed (thanks to [@Thilas](https://github.com/Thilas)):
```cmd
:: stable
choco install vscodium

:: insider
choco install vscodium-insiders
```

#### <a id="install-with-scoop"></a>Install with Scoop (Windows)

If you use Windows and have [Scoop](https://scoop.sh) installed:
```bash
scoop bucket add extras
scoop install vscodium
```
#### <a id="install-with-package-manager"></a>Install with Package Manager (Linux)

You can always install using the downloads (deb, rpm, tar) on the releases page for [stable](https://github.com/VSCodium/vscodium/releases) or [insiders](https://github.com/VSCodium/vscodium-insiders/releases), but you can also install using your favorite package manager and get automatic updates.

[@paulcarroty](https://github.com/paulcarroty) has set up a repository with instructions for `apt`, `dnf` and `zypper` [here](https://gitlab.com/paulcarroty/vscodium-deb-rpm-repo).

Any issues installing NetChicken using your package manager should be directed to that repository's issue tracker.

#### <a id="install-on-arch-linux"></a>Install on Arch Linux

NetChicken is available in [AUR](https://wiki.archlinux.org/index.php/Arch_User_Repository), maintained by [@binex-dsk](https://github.com/binex-dsk) as package [vscodium-bin](https://aur.archlinux.org/packages/vscodium-bin/) (stable) and as [vscodium-insiders-bin](https://aur.archlinux.org/packages/vscodium-insiders-bin).

If you want to save disk space by having NetChicken use the Electron system-wide, you also have [vscodium-electron](https://aur.archlinux.org/packages/vscodium-electron),
maintained by [@m00nw4tch3r](https://aur.archlinux.org/account/m00nw4tch3r).

An alternative package [vscodium-git](https://aur.archlinux.org/packages/vscodium-git/), maintained by [@cedricroijakkers](https://github.com/cedricroijakkers), is also available should you wish to compile from source yourself.

#### <a id="flatpak"></a>Flatpak Option (Linux)

VSCodium is available as a Flatpak app [here](https://flathub.org/apps/details/com.vscodium.codium) and the build repo is [here](https://github.com/flathub/com.vscodium.codium).
If your distribution has support for [flatpak](https://flathub.org), and you have enabled the [flathub repo](https://flatpak.org/setup/):

```bash
flatpak install flathub com.vscodium.codium
flatpak run com.vscodium.codium
```

## <a id="build"></a>Build

Build instructions can be found [here](https://github.com/VSCodium/vscodium/blob/master/docs/howto-build.md)

## <a id="more-info"></a>More Info

 by <a href="https://signpath.io/" target="_blank">SignPath.io</a>, certificate by <a href="https://signpath.org/" target="_blank">SignPath Foundation</a></td>
  </tr>
</table>

## <a id="license"></a>License

[MIT](https://github.com/VSCodium/vscodium/blob/master/LICENSE)
