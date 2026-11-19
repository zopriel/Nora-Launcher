<div align="center">

# Nora Launcher

**A newer, brighter, faster way to play Roblox.**

A modern, password-free desktop launcher and bootstrapper for Roblox featuring live game discovery, an advanced server browser, allowlisted FastFlag optimization, local playtime tracking, and full theme customization.

[![Download Latest Release](https://shields.io)](https://github.com)
![Platform](https://shields.io)
![Security](https://shields.io)

</div>

---

## About

Nora Launcher is a custom Windows desktop launcher and bootstrapper built to upgrade how you browse, optimize, and launch Roblox experiences—without ever asking for your password or touching your account cookies.

---

## Features

### Game Discovery & Rich Modals
* **Live Roblox Discovery:** Browse real-time explore categories (*Top Trending*, *Up-and-Coming*, *Most Players Online Now*) or search any experience instantly.
* **Detailed Game Pages:** View thumbnails, live player counts, visits, like ratios, genres, and avatar types in one place.
* **Built-In Creator & Group Viewers:** Click any creator or group to inspect bios, member counts, group shouts, member lists, and other published experiences without leaving the launcher.
* **Advanced Server Browser:** Filter public servers by player count, ping, server FPS, or Job ID, preview player avatars inside each server, and join with a single click.

### Bootstrapper & FastFlag Optimization
* **Allowlisted FastFlag Presets:** Apply verified allowlisted optimization profiles (*Stock*, *Max FPS / Potato*, *Balanced Boost*, *Crisp Visuals*) directly to `ClientAppSettings.json`.
* **Granular Graphics Controls:** Customize your graphics renderer (`D3D11`, `Vulkan`, `OpenGL`), texture quality, MSAA samples, render quality (`1–21`), 3D grass distance, voxelizer lighting, low-poly CSG, and custom JSON flags—complete with a live `ClientAppSettings.json` preview.
* **Launch & System Controls:** Launch via official `roblox://` protocol URIs or directly through `RobloxPlayerBeta.exe`, set Windows CPU priority (`Normal`, `Above Normal`, `High`), auto-minimize Nora while playing, and clear Roblox temp/log caches in one click.

### Social, Library & Catalog
* **Nora Friends & Live Presence:** Search and add Roblox players locally to track who is online, in Studio, or in-game, and join joinable sessions directly.
* **Favorites, Recents & Backup:** Pin favorite experiences, view recently played games, and export/import your friends and favorites list as a JSON backup.
* **Built-In Marketplace Browser:** Search avatar items, bundles, limiteds, and animations with filters for category, subcategory, price range, creator username, and sales type.

### Tracking & Customization
* **Local Playtime & Session History:** Automatically detects `RobloxPlayerBeta.exe` to record session durations, total hours played, and session counts locally on your machine.
* **Themes & Custom Accents:** Switch between **Midnight**, **Slate**, **AMOLED**, **Light**, **Christmas (Animated)**, and **Galaxy (Animated)** themes with a custom accent color picker.
* **Discord Rich Presence *(Work in Progress)*:** Live browsing and in-game Discord status integration is currently in active development.

---

## Security & Account Safety

Nora is built from the ground up to keep your Roblox account safe:
* **Zero Password or Cookie Access:** Nora never asks for your Roblox password and never reads or stores `.ROBLOSECURITY` cookies.
* **Official OAuth 2.0 + PKCE:** Optional account sign-in uses Roblox's official browser OAuth 2.0 flow, with refresh tokens encrypted locally via OS-level credential storage.
* **No Client Modification:** Nora launches the official, unmodified Roblox client using standard protocol URIs and allowlisted `ClientAppSettings.json` flags.

---

## Installation (Windows)

1. Head to the **[GitHub Releases page](https://github.com)** and download the latest `Nora Setup.exe`.
2. Run the installer *(if Windows SmartScreen appears because the build is unsigned, click **More info** -> **Run anyway**)*.
3. Nora will automatically detect your active `RobloxPlayerBeta.exe` installation on startup.

---

## Copyright & Disclaimer

Copyright (c) 2026 zopriel. All rights reserved. No license is granted to copy, modify, distribute, or create derivative works from this project. For permission, contact the repository owner.

Nora Launcher is an independent, community-made project and is not affiliated with, endorsed, or sponsored by Roblox Corporation.
