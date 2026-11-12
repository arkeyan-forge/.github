<p align="center">
  <img src="https://raw.githubusercontent.com/arkeyan-forge/.github/main/assets/arkeyan.svg" width="140" alt="Arkeyan">
</p>

<h1 align="center">Arkeyan</h1>

<p align="center"><b>Native Skylanders on PC, macOS and Linux, built from your own disc.</b></p>

<p align="center">
  <a href="https://github.com/mflr0/Arkeyan-Launcher/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/mflr0/Arkeyan-Launcher?label=Arkeyan%20Launcher&color=c8873a"></a>
  <a href="https://github.com/mflr0/Arkeyan-Launcher/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/mflr0/Arkeyan-Launcher/total?color=c8873a"></a>
  <img alt="Platforms" src="https://img.shields.io/badge/Windows%20%7C%20macOS%20%7C%20Linux-native-3b4a6b">
  <a href="https://discord.gg/UMQY4SAS3F"><img alt="Discord" src="https://img.shields.io/badge/Discord-join-5865F2?logo=discord&logoColor=white"></a>
  <img alt="License" src="https://img.shields.io/badge/license-MIT-3b4a6b">
</p>

<p align="center">
  <a href="https://github.com/mflr0/Arkeyan-Launcher/releases/latest"><b>Download the launcher</b></a> ·
  <a href="https://github.com/mflr0/Arkeyan-Launcher#the-games">The games</a> ·
  <a href="https://discord.gg/UMQY4SAS3F">Discord</a> ·
  <a href="https://github.com/mflr0/Arkeyan-Launcher/issues/new/choose">Report a bug</a>
</p>

---

The six Xbox 360 Skylanders games, from *Spyro's Adventure* to *Imaginators*, as real native programs: Direct3D 12 or
Vulkan on Windows, Metal on macOS, Vulkan on Linux, with higher resolutions, 60 FPS, a virtual Portal of Power and your
real one.

### How it works
1. **Your disc.** You give the launcher your own disc image. Nothing from the games is ever downloaded or shared.
2. **Translated on your computer.** The game's PowerPC code becomes C++ and its shaders become your system's shaders
   (static recompilation), then it is compiled into a native program.
3. **A runtime made for these games** replaces the Xbox 360: memory, threads, graphics, sound, controllers, saves and
   the Portal of Power.

### The repositories
| | |
|---|---|
| [**Arkeyan Launcher**](https://github.com/mflr0/Arkeyan-Launcher) | The app players install: it builds, starts and updates the games, and holds your figures |
| [**forge**](https://github.com/arkeyan-forge/forge) | Everything else: the runtime that replaces the Xbox 360, the builder that makes a game from your disc, each game's port, the tests and the docs. The code and shader translators are [hedge-dev](https://github.com/hedge-dev)'s, with our patches in `patches/` |

### Get involved
Bugs, ideas and questions go to the [launcher's issues](https://github.com/mflr0/Arkeyan-Launcher/issues/new/choose) (one place for every game). Pull requests:
read [CONTRIBUTING.md](https://github.com/mflr0/Arkeyan-Launcher/blob/main/CONTRIBUTING.md) first. Testers are welcome on the
[Discord](https://discord.gg/UMQY4SAS3F).

<sub>Designed by dorydev, made by mflr0, UI/UX by Gumelia. Built on XenonRecomp, XenosRecomp, plume, SDL and Dear ImGui.
Skylanders, Spyro and Activision are trademarks of Activision Publishing, Inc.; this project is not affiliated with or
endorsed by Activision. You need your own copy of the games.</sub>
