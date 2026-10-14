# Front Row

Installers and updates for Front Row.

| Platform | Where |
| --- | --- |
| Windows | Releases tagged `windows-v<version>`. Download `Front-Row-Setup-<version>-x64.exe` for most PCs, or `Front-Row-Setup-<version>-arm64.exe` for Windows on Arm (Snapdragon). Installed apps update themselves from `latest.yml` in the newest Windows release. |
| Mac | Releases for the Mac app and its update feed live here too. |

The installers aren't code signed yet, so Windows SmartScreen asks once before the first install: choose "More info", then "Run anyway".

## Open source software

From version 1.3.0 the Windows app plays video with [mpv](https://mpv.io), which ships inside it unmodified (`resources\mpv\mpv.exe`, with its licence and notice). mpv is free software under the GNU General Public License, version 2 or later. The exact builds and a copy of the mpv source they come from are in the release [`vendor-mpv-20261014`](https://github.com/sparkserian/frontrow-releases/releases/tag/vendor-mpv-20261014); the build scripts are at [shinchiro/mpv-winbuild-cmake](https://github.com/shinchiro/mpv-winbuild-cmake).
