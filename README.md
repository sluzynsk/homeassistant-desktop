# Home Assistant - Desktop

Linux/Windows Desktop App for [Home Assistant](https://www.home-assistant.io/) built with [Electron](https://www.electronjs.org)

Marvin seems to have moved on from this project; he's removed the repository. This fork is
my attempt to keep it working and make some changes to make it work better. I've removed the build for MacOS as those users are better served by using the official app:

- MacOS: [Home Assistant for MacOS](https://apps.apple.com/us/app/home-assistant/id1099568401)

![Home Assistant - Desktop](https://raw.githubusercontent.com/sluzynsk/homeassistant-desktop/master/media/screenshot.png)

## Installation

Just download the latest version for your platform from the [release section](https://github.com/sluzynsk/homeassistant-desktop/releases/latest) to install Home Assistant

## Usage / Features

- hover / click the tray icon to open the app
- supports multiple instances of Home Assistant (including automatic switching)
- automatic instance discovery using bonjour
- right-click context menu for settings / reset / quit the app
- global keyboard shortcut (Cmd/Ctrl + Alt + X) can be enabled to show / hide Home Assistant
- fullscreen mode (Cmd/Ctrl + Alt + Return)
- automatic updates (if not disabled in context menu)

## Recent changes:

- added fullscreen mode
- added arm64 builds (experimental)
- updated electron to v20 + dependencies
- moved to electron-forge because it is easier to build mulitple output types with it
- work to make Linux build work better on GNOME 42, have proper icons, etc.

## Notes

- if using "detached window" on Windows, instead of dragging, you have to resize it to move it

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
