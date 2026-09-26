# lingmo-desktop

Metapackage for the Lingmo desktop (Qt 6 port for Arch Linux). Installing it pulls
every Lingmo component, the artwork and the SDDM login theme:

```sh
sudo pacman -S lingmo-desktop
```

Then enable the login manager and pick the **Lingmo** session:

```sh
sudo systemctl enable --now sddm
```
