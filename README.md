# Danheng Server

**__This project is under development! Some game technique might not correctly!__**

<p align="center">
<a href="https://visualstudio.com"><img src="https://img.shields.io/badge/Visual%20Studio-000000.svg?style=for-the-badge&logo=visual-studio&logoColor=white" /></a>
<a href="https://dotnet.microsoft.com/"><img src="https://img.shields.io/badge/.NET-000000.svg?style=for-the-badge&logo=.NET&logoColor=white" /></a>
<a href="https://www.gnu.org/"><img src="https://img.shields.io/badge/GNU-000000.svg?style=for-the-badge&logo=GNU&logoColor=white" /></a>
</p>
<p align="center">
  <a href="https://discord.gg/xRtZsmHBVj"><img src="https://img.shields.io/badge/Discord%20Server-000000.svg?style=for-the-badge&logo=Discord&logoColor=white" /></a>
</p>

[EN](README.md) | [簡中](docs/README_zh-CN.md) | [繁中](docs/README_zh-CN.md) | [JP](docs/README_ja-JP.md)

## 💡 Function

- [√] **Shop**
- [√] **Formation**
- [√] **Gacha** - Custom probability : )
- [√] **Battle** - Some errors are exist among scene skills
- [√] **Scene** - Walking simulator, interaction, correct loading of entities
- [√] **Basic character development** - Some minor bugs that don't significantly affect the playing experience
- [√] **Quests** - There may be some bugs in some missions, the main story before Penacony is basically playable, and most of the story after Penacony has bugs
- [√] **Friends**
- [√] **Forgotten Hall & Pure Fiction & Apocalyptic Shadow**
- [√] **Simulated Universe & Gold and Gears**
- [√] **Achievements** - Most achievements can be completed.

- [ ] **More**  - Coming soon

Some functions for the game might not support at the first time when new "Anime Game" version drops, please stay tune to our new commit. Since version 2.3, we've created a private fork which supports beta version, and will merge to main branch asap when it's ready.

## 🍗 Use & Installation

### Quick Start

1. Go to releases and download the zip located there
2. head to (https://gitlab.com/Dimbreath/turnbasedgamedata/-/tree/5e960aa11f83b9245c722087caa4621708aa770e) and press the code Button and "Zip"
3. run the .exe and it will make files/folders for you
4. create a folder called "resources" in the same place as the .exe file
5. paste everything from the turnbasegamedata zip into the new resources folder and run it
6. its done! have fun! (if you have issues try the steps under trouble shooting first, and if they don't work try the official discord server)

### Build

DanhengServer is built using .NET Framework

**Requirement: **

- [.NET](https://dotnet.microsoft.com/)
- [Git](https://git-scm.com/downloads)

##### Windows

```shell
git clone --recurse-submodules https://github.com/EggLinks/DanhengServer.git
cd DanhengServer
dotnet build # compile
```
##### Linux （Ubuntu 20.04）
```shell
wget https://packages.microsoft.com/config/ubuntu/20.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
sudo dpkg -i packages-microsoft-prod.deb
rm packages-microsoft-prod.deb

# Install .NET SDK
sudo apt-get update && \
  sudo apt-get install -y dotnet-sdk-8.0
```

- Compile and run environment
```shell
git clone --recurse-submodules https://github.com/EggLinks/DanhengServer.git
cd DanhengServer
.\dotnet build # compile
./Gameserver
```

## ❓ Help

- Support Android system
- Mission 100040119 (cannot complet automatically) (use /mission finish 100040119 to fix it)

## ❕️ Troubleshooting
For solutions to common problems or assistance, please join our Discord server at [https://discord.gg/xRtZsmHBVj](https://discord.gg/xRtZsmHBVj)

## 🙌 Acknowledgements

- Weedwacker - Provides kcp implementation
- [SqlSugar](https://github.com/donet5/SqlSugar) - Provides ORM
- [LunarCore](https://github.com/Melledy/LunarCore) - Some data structures and algorithms
