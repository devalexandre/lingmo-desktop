# Maintainer: devalexandre <alexandre@dev2learn.com>
# Metapackage: installs the whole Lingmo desktop (Qt 6) in one go.
pkgname=lingmo-desktop
pkgver=1.3.1
pkgrel=1
pkgdesc="Lingmo desktop environment (Qt 6): session, shell, apps, themes and login screen"
arch=('any')
url="https://github.com/devalexandre/lingmo-desktop"
license=('GPL-3.0-or-later')
depends=(
    # Libraries and platform integration
    'LingmoUI' 'liblingmo' 'lingmo-qt-plugins'
    # Session, shell and window manager integration
    'lingmo-core' 'lingmo-statusbar' 'lingmo-dock' 'lingmo-launcher'
    'lingmo-filemanager' 'lingmo-settings' 'lingmo-spotlight' 'lingmo-kwin-plugins'
    # Look and feel
    'lingmo-systemicons' 'lingmo-artwork' 'lingmo-wallpapers'
    'lingmo-cursor-themes' 'lingmo-gtk-themes'
    # Login screen and display server
    'lingmo-sddm-theme' 'sddm' 'xorg-server'
    # Global menu for GTK apps (lingmo-gmenuproxy loads it through gtk-modules)
    'appmenu-gtk-module'
    # Apps
    'lingmo-terminal' 'lingmo-texteditor' 'lingmo-calculator'
    'lingmo-screenshots' 'lingmo-screenlocker' 'lingmo-videoplayer'
    'lingmo-updater' 'lingmo-welcome'
)
optdepends=(
    'konsole: KDE terminal'
    'flameshot: screenshots (bind it to Print in Settings > Shortcuts)'
    'networkmanager: network and VPN in the status bar'
    'bluez: Bluetooth settings'
    'lingmo-camera: auto framing for video calls (Settings > Camera)'
)
