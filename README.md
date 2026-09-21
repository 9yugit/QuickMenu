<img width="400" height="225" alt="2026-06-10 03-50-39" src="https://github.com/user-attachments/assets/f18a9646-6d9a-4443-b9a5-ce9a6b90fae2" />


# QuickMenu

QuickMenu is a lightweight GUI menu plugin for Minecraft servers.

Unlike traditional menu plugins, QuickMenu allows administrators to create and edit menus directly in-game without touching configuration files or YAML files.

Build menus faster, manage them entirely through a GUI, and connect menu buttons to commands from other plugins.

## Features

* Create and edit menus directly in-game
* No YAML or configuration file editing required
* Execute commands as player
* Execute commands as console
* Run commands from other plugins
* Shows the viewer's own player head
* Quick access with Shift + F
* Lightweight and easy to set up

## Configuration

Menus are managed in-game, but a few options are available in `config.yml`:

- `open-with-shift-f` — Toggle the Shift + F shortcut (default: `true`)
- `head-slot` — Slot for the viewer's head, `-1` to disable (default: `22`)
- `command-input-timeout` — Seconds to wait for chat input (default: `30`)
- `debug` — Log player command executions (default: `false`)

## Why QuickMenu?

Most menu plugins require administrators to edit configuration files and reload the plugin whenever changes are needed.

QuickMenu focuses on simplicity by allowing menu creation and management entirely in-game through an intuitive GUI editor.

Whether you want to open a shop, teleport players, manage jobs, execute LuckPerms commands, or connect any other plugin command, QuickMenu lets you do it without leaving the game.

## Commands

Alias: `/m`

| Command | Description | Permission |
|---|---|---|
| `/menu open` | Open the menu | `menu.use` |
| `/menu edit` | Open the in-game editor | `menu.admin` |
| `/menu setcmd` | Assign a command to a slot | `menu.admin` |
| `/menu clearcmd` | Remove a slot's command | `menu.admin` |
| `/menu listcmd` | List assigned commands | `menu.admin` |
| `/menu setsize` | Change menu size | `menu.admin` |
| `/menu settitle` | Change menu title | `menu.admin` |
| `/menu console` | Toggle console execution | `menu.admin` |
| `/menu reload` | Reload configuration | `menu.admin` |
| `/menu help` | Show help | `menu.use` |

## Permissions

| Permission | Default | Description |
|---|---|---|
| `menu.use` | everyone | Open and use the menu |
| `menu.admin` | op | Edit and manage the menu |

## Compatibility

- Tested on Paper 1.21.11
- Expected to work on most Paper 1.21.x versions
- Java 21


## Installation

1. Download the latest release.
2. Place the jar file into your server's `plugins` folder.
3. Restart the server.

## Download

Download the latest version from the Releases page.

## License

All rights reserved.

## Support & Custom Plugins

Found a bug or need help? Open an issue or contact me on Discord.

**Need a custom plugin for your server?** I take commissions for
Paper plugins, server setup, and custom launchers.

- Discord: gyu_.m1n
- 커미션 문의는 한국어로 편하게 주셔도 됩니다.
