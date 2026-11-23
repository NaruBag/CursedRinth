# CursedRinth

A personal, non-commercial launcher and mod manager for **Minecraft: Java Edition**, made for me and one other person.

It is not distributed publicly and is not affiliated with Mojang, Microsoft, CurseForge or Modrinth.

## What it does

- **One mod list for CurseForge and Modrinth.** You can search, install and update mods, resource packs, shaders and data packs from both sites in the same place.
- **Modpack manager.** You can create modpacks, import `.mrpack` and CurseForge modpacks, duplicate them, and share them as small `.cursedpack` files.
- **Safe updates.** You can lock updates for a whole modpack or for a single mod, and the lock is strictly respected.
- **Launches the game itself.** It downloads the official game files from Mojang and supports Fabric, Quilt, Forge and NeoForge.
- **Portable.** Everything stays inside the app folder: no installer and nothing in AppData.

## Microsoft sign-in

CursedRinth uses the standard Microsoft device code sign-in. Each player signs in with their own Microsoft account:

1. Microsoft account sign-in.
2. Xbox Live / XSTS token.
3. `api.minecraftservices.com` (login with Xbox, then the profile).

These steps only get the player's own Minecraft access token and profile, so the launcher can start the game with their account and play online.

- Tokens are stored only on the player's own PC, encrypted by the operating system (Windows DPAPI).
- Nothing is sent to any server other than Microsoft, Xbox Live and Mojang.
- No analytics, no ads and no data collection.

## Status

This is a private hobby project used by two people. The source code is not published.
