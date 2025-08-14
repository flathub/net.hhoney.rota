[![Flathub](https://img.shields.io/flathub/v/net.hhoney.rota?logo=flathub&logoColor=white&style=for-the-badge)][flathub]
[![Installs](https://img.shields.io/flathub/downloads/net.hhoney.rota?label=Installs&logo=flathub&logoColor=white&style=for-the-badge)][flathub]

# Flathub manifest for ROTA

- To install the app, visit [Flathub]
- For the game source code, issue tracking, etc. see [@HarmonyHoney/ROTA](https://github.com/HarmonyHoney/ROTA)

## Permissions

- **`--socket=x11`**: ROTA is built with Godot Engine 3.6. Wayland support didn't come until [Godot 4.3](https://godotengine.org/article/dev-snapshot-godot-4-3-dev-3/#wayland-support-for-linux), and porting from 3.6 to 4.3 is pretty monumental; thus X11/XWayland needs to be used unless/until someone volunteers to port to Godot Engine 4.3+.

- **`--device=all`**: Currently necessary for controller support. See: https://github.com/flathub/net.hhoney.rota/pull/2

- **`--talk-name=org.freedesktop.ScreenSaver`**: Allows the game to inhibit idle. See: https://github.com/godotengine/godot/issues/108634

[flathub]: https://flathub.org/apps/details/net.hhoney.rota
