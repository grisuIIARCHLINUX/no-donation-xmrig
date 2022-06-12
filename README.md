# XMRig

[![Github All Releases](https://img.shields.io/github/downloads/xmrig/xmrig/total.svg)](https://github.com/xmrig/xmrig/releases)
[![GitHub release](https://img.shields.io/github/release/xmrig/xmrig/all.svg)](https://github.com/xmrig/xmrig/releases)
[![GitHub Release Date](https://img.shields.io/github/release-date/xmrig/xmrig.svg)](https://github.com/xmrig/xmrig/releases)
[![GitHub license](https://img.shields.io/github/license/xmrig/xmrig.svg)](https://github.com/xmrig/xmrig/blob/master/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/xmrig/xmrig.svg)](https://github.com/xmrig/xmrig/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/xmrig/xmrig.svg)](https://github.com/xmrig/xmrig/network)

XMRig is a high performance, open source, cross platform RandomX, KawPow, CryptoNight, AstroBWT and [GhostRider](https://github.com/xmrig/xmrig/tree/master/src/crypto/ghostrider#readme) unified CPU/GPU miner and [RandomX benchmark](https://xmrig.com/benchmark). Official binaries are available for Windows, Linux, macOS and FreeBSD.

## Mining backends
- **CPU** (x64/ARMv7/ARMv8)
- **OpenCL** for AMD GPUs.
- **CUDA** for NVIDIA GPUs via external [CUDA plugin](https://github.com/xmrig/xmrig-cuda).

## Download
* **[Binary releases](https://github.com/xmrig/xmrig/releases) doesnt include the 0% donation!!**
* **[Build from source](https://xmrig.com/docs/miner/build)**

## Building commands for ez copy&paste+

Ubuntu & Arch:
* step 0 for ubuntu: sudo apt-get install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev
* step 0 for arch, (if somethings missing please message me on discord, grisu#0001 and i will add it): sudo pacman -Syu cmake
* step 1: git clone https://github.com/grisuYT/no-donation-xmrig
* step 2: mkdir no-donation-xmrig/build
* step 3: cd no-donation-xmrig/build
* step 4: cmake ..
* step 5: make



For Windows please click the "Build from source" link and follow it for my source since its way to complicated to list here

## Usage
The preferred way to configure the miner is the [JSON config file](https://xmrig.com/docs/miner/config) as it is more flexible and human friendly. The [command line interface](https://xmrig.com/docs/miner/command-line-options) does not cover all features, such as mining profiles for different algorithms. Important options can be changed during runtime without miner restart by editing the config file or executing [API](https://xmrig.com/docs/miner/api) calls.

* **[Wizard](https://xmrig.com/wizard)** helps you create initial configuration for the miner.
* **[Workers](http://workers.xmrig.info)** helps manage your miners via HTTP API.

## Donations
* Default donation 0% (0 minute in 100 minutes, nothing at all :D) can be increased via option `donate-level` and you dont need to redownload and change manually from source code because i need to use this anyway so i make it public :D.
* XMR: `48edfHu7V9Z84YzzMa6fUueoELZ9ZRXq9VetWzYGzKt52XU5xvqgzYnDK9URnRoJMk1j8nLwEVsaSWJ4fhdUyZijBGUicoD`
* XMR grisu (not the creator of xmrig itself, only the 0% donation version): `41utKSmwmQnTYjNk3BFoWPSmSMntGAiLG53RLeDRdFtnQghSpoENuTcaPCcWi6mMozCfqfLqLEjg4Adrk2LhSUk5P9Kh6vT`

## Developers
* **[xmrig](https://github.com/xmrig)**
* **[sech1](https://github.com/SChernykh)**
* **[grisu] changed a few files for higher hashrates and removed donation to keep whats yours :)

## Contacts
* support@xmrig.com
* [reddit](https://www.reddit.com/user/XMRig/)
* [twitter](https://twitter.com/xmrig_dev)
