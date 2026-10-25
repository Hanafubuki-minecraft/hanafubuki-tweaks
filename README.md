<div align="center">

# hanafubuki-tweaks

**Server datapack for Hanafubuki — quiet, on-style texts for other datapacks and small vanilla+ touches.**

[![Build](https://github.com/Hanafubuki-minecraft/hanafubuki-tweaks/actions/workflows/release.yml/badge.svg)](https://github.com/Hanafubuki-minecraft/hanafubuki-tweaks/actions/workflows/release.yml)
[![Release](https://img.shields.io/github/v/release/Hanafubuki-minecraft/hanafubuki-tweaks)](https://github.com/Hanafubuki-minecraft/hanafubuki-tweaks/releases/latest)

</div>

## What's inside

| Function | What it does |
|---|---|
| `blazeandcave:msg_welcome` | Replaces the big English welcome of [BlazeandCave's Advancements Pack](https://modrinth.com/datapack/blazeandcaves-advancements-pack) with one quiet line in the [server style](https://github.com/Hanafubuki-minecraft/hanafubuki-brand/blob/main/STYLE.md), keeping the author credit (Cavinator1) |

## Install

Download the zip from [Releases](https://github.com/Hanafubuki-minecraft/hanafubuki-tweaks/releases/latest) into `world/datapacks/` — or let [`apply.sh`](https://github.com/Hanafubuki-minecraft/hanafubuki-brand/blob/main/server/apply.sh) do it.
It must load **after** the packs it overrides: `/datapack enable "file/hanafubuki-tweaks.zip" last`.

Minecraft 1.21.9+ (data pack format 88+).

## Releasing

Bump [`VERSION`](VERSION) and push to `main` — GitHub Actions validates the JSON, zips the pack and publishes release `v<version>`.

## License

[GNU General Public License v3.0](LICENSE) © ByteMe6
