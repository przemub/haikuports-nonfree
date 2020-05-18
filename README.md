# Unofficial non-free recipes repository for HaikuPorter
This unofficial repository collects recipes that could not be included in [haikuports/haikuports](https://github.com/haikuports/haikuports) due to not being allowed to be re-distributed freely.

In other words, it helps you install commercial software on your [Haiku](https://haiku-os.org) operating system.

## Packages
* sys-util/pycharm-professional: IntelliJ [PyCharm](https://www.jetbrains.com/pycharm/) Professional Edition - `./haikuporter-nonfree pycharm_professional_bin`
* sys-util/idea-ultimate: IntelliJ [IDEA](https://www.jetbrains.com/idea/) Ultimate Edition `./haikuporter-nonfree idea_ultimate_bin`

## Usage
First you need to have HaikuPorter installed. If you don't have `haikuporter` command in your system:
* `pkgman install haikuporter`

Installation:
* `git clone https://github.com/przemub/haikuports-nonfree`
* `cd haikuports-nonfree`
* `cp haikuports-sample.conf /boot/home/config/settings/haikuports-nonfree.conf`

Example usage:
* `./haikuporter-nonfree pycharm_professional_bin`
* `pkgman install packages/pycharm_professional_bin*`

## Contributions
Please follow the [HaikuPorts Wiki](https://github.com/haikuports/haikuports/wiki).
