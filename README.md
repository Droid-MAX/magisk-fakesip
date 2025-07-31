# MagiskFakesip

![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/Droid-MAX/magisk-fakesip/main.yml?branch=main)
![GitHub repo size](https://img.shields.io/github/repo-size/Droid-MAX/magisk-fakesip)
![GitHub downloads](https://img.shields.io/github/downloads/Droid-MAX/magisk-fakesip/total)

> [FakeSIP](https://github.com/MikeWang000000/FakeSIP) is a tool used to disguise your UDP traffic as SIP protocol to evade DPI detection, using Netfilter Queue (NFQUEUE).

> [MagiskFakesip](README.md) lets you run fakesip on boot with multiple root solutions

## Supported root solutions

[Magisk](https://github.com/topjohnwu/Magisk), [KernelSU](https://github.com/tiann/KernelSU) and [APatch](https://github.com/bmax121/APatch)

## Supported architectures

`arm32v7`, `arm64`, `i686`, `x86_64`

## Instructions

Install `MagiskFakesip-[VERSION].zip` from [the releases](https://github.com/Droid-MAX/magisk-fakesip/releases)

> :information_source: Do not use the Magisk modules repository, it is obsolete and no longer receives updates

## How fast are fakesip updates?

Instant! This module is hooked up to the official FakeSIP build process

## Issues?

Please feel free to [open a issues](https://github.com/Droid-MAX/magisk-fakesip/issues/new/choose)

## Building yourself

```bash
uv sync
uv run python3 main.py
```

- Release ZIP will be under `/build`
- fakehttp downloads will be under `/downloads`

## License

GNU General Public License v3.0
