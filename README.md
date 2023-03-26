[![build](https://github.com/CoolMineman/CheaterDeleter/actions/workflows/build.yml/badge.svg)](https://github.com/CoolMineman/CheaterDeleter/actions/workflows/build.yml)
![GitHub](https://img.shields.io/github/license/CoolMineman/CheaterDeleter)
# BLITZ.AC

A Minecraft Anti-Cheat for Fabric Servers. Detects and prevents many packet exploits, movement cheats, and other unwanted cheat mods.


**This is currently the DEMO VERSION.

## Currently Includes Detection/Prevention for:

* Movement
    * Glide
    * Fly
    * VClip
    * HClip
    * Phase
    * Step (Even "legit" In Some Clients)
    * No Fall
    * Speed
    * XCarry and Inventory Move
    * Vehicle High Jump
    * Boat Fly
    * Poorly Written Inventory Item Movement Cheats (AutoTotem, AutoMlg if Bucket not in Hotbar)
    * Poorly Written Water Walk Cheats (Basically all the Public Ones)
    * Elytra Fly
* Packet Exploits
    * Timer/Extra Movement Packets
    * Timer While on Entity
    * Packet Limiter Stops Various DoS attacks
    * Crafting Packet Crash Exploit
    * Teleport Finder (Gives Fake Data Instead)
    * Illegal Book and Quill Page Length (Used in dupe)
* Rotations
    * Spoofed Rotations (1 tick head snaps)
    * Lock on Entity (Used in KillAura Stay)
    * Clamped Yaw (lol)
* Combat
    * Attacking mobs not facing (No rotation/not enough rotation KillAura)
    * Bad Attack Angle (KillAura)

## Supported Mods

* Step Height Entity Attribute Library [https://github.com/emilyalexandra/step-height-entity-attribute](https://github.com/emilyalexandra/step-height-entity-attribute)
* :key: fabric-permissions-api [https://github.com/lucko/fabric-permissions-api](https://github.com/lucko/fabric-permissions-api)
    * LuckPerms [https://github.com/lucko/LuckPerms](https://github.com/lucko/LuckPerms)

## Permissions

**Requires LuckPerms or Another fabric-permissions-api Compatable Permissions Mod**

`blitzac.bypassanticheat` - Allows a player to bypass this Anti-Cheat

`blitzac.sendmajorflags` - Send major flags from all players to this player in chat

`blitzac.sendminorflags` - Send minor flags from all players to this player in chat

