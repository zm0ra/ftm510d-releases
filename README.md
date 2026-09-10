# FTM-510D Programmer: downloads

A programmer for the Yaesu FTM-510D. Reads the backup the radio writes on its
microSD card (or the radio itself over the SCU-20 cable), lets you edit it in
your browser, writes a new file. Reading is free; writing needs a licence key.

Install:

| System | How |
|---|---|
| Windows | `ftm510d-setup-<version>.exe` from the latest release, or `scoop bucket add zm0ra https://github.com/zm0ra/scoop-bucket && scoop install ftm510d` |
| macOS | `brew install --cask zm0ra/tap/ftm510d`, or `curl -fsSL https://github.com/zm0ra/ftm510d-releases/releases/latest/download/install.sh \| sh` |
| Debian, Ubuntu, Raspberry Pi OS | the `.deb` from the latest release |
| Fedora, openSUSE | the `.rpm` from the latest release |
| Any Linux | the `install.sh` line above, or the `.tar.gz` |

Every archive contains GETTING_STARTED.md with the first steps. This repository
holds only releases; the source is not public.
