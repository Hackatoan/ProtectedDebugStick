[![Buy Me A Coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://buymeacoffee.com/hackatoa)

![icon](https://raw.githubusercontent.com/MachiganMC/ProtectedDebugStick/master/plugin/src/main/resources/icon.png)

[![Spiget Downloads](https://img.shields.io/spiget/downloads/102630?color=A87D17&style=for-the-badge)](https://www.spigotmc.org/resources/protected-debug-stick.102630/)
[![Spiget Version](https://img.shields.io/spiget/version/102630?label=Current%20Version&style=for-the-badge)](https://www.spigotmc.org/resources/protected-debug-stick.102630/updates)
[![Spiget tested server versions](https://img.shields.io/spiget/tested-versions/102630?color=FF3333&label=Minecraft%20Version&style=for-the-badge)](https://www.spigotmc.org/resources/protected-debug-stick.102630/)

# ProtectedDebugStick

A Spigot/Paper plugin that makes the vanilla Debug Stick usable in survival — with durability, permission checks, and claim plugin integration (GriefPrevention, WorldGuard).

## Items

| Item | Command | Description |
|---|---|---|
| Basic Debug Stick | `/pds give <player> basic <durability>` | Has durability; costs per property edit |
| Infinity Debug Stick | `/pds give <player> infinity` | No durability limit |
| Inspector | `/pds give <player> inspector` | Read block properties without editing |

## Features

- Integrates with claim plugins (GriefPrevention, WorldGuard) — players must have build permission in the claim
- Configurable durability cost per property type
- Custom crafting recipes for all three items
- Bypass permission: `pds.bypass.plugin-block`

## Installation

1. Download the latest JAR from [SpigotMC](https://www.spigotmc.org/resources/protected-debug-stick.102630/) or [Releases](../../releases/latest)
2. Drop it into your server's `plugins/` folder
3. Restart the server
4. Edit `plugins/ProtectedDebugStick/config.yml` to configure durability costs and recipes

## Block properties reference

- [English](https://github.com/MachiganMC/ProtectedDebugStick/blob/master/src/main/resources/properties_en.MD)
- [Français](https://github.com/MachiganMC/ProtectedDebugStick/blob/master/src/main/resources/properties_fr.MD)

---

[hackatoa.com](https://hackatoa.com) · [GitHub](https://github.com/Hackatoan) · [Buy Me A Coffee](https://buymeacoffee.com/hackatoa)
