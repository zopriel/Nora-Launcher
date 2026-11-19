# Nora Launcher

A custom Windows desktop launcher and bootstrapper for Roblox.

## FOR ANY PROBLEMS, CONTACT ME ON MY DISCORD: .mxcz


---

## Features

| Feature | Details |
| :--- | :--- |
| **Game Discovery** | Live Roblox explore sorts, game search, thumbnails, player counts, visit stats, and like ratios. |
| **Server Browser** | Public server list with ping, server FPS, player count, Job ID filtering, and direct server joining. |
| **Users & Groups** | In-app creator profiles, group details, group shouts, member lists, and published experiences. |
| **FastFlags & Launch Tweaks** | Allowlisted FPS presets (*Stock*, *Max FPS*, *Balanced*, *Crisp*), graphics API overrides (`D3D11`, `Vulkan`, `OpenGL`), texture/MSAA/render quality overrides, custom JSON flags, Windows CPU priority, and cache clearing. |
| **Friends & Library** | Local friend tracking with live online/in-game presence, direct friend joining, favorites, recent games, and JSON import/export. |
| **Catalog Browser** | Search avatar items, bundles, limiteds, and animations with category, price, creator, and sales filters. |
| **Playtime Tracking** | Local session and total playtime tracking via `RobloxPlayerBeta.exe` process detection. |
| **Themes** | *Midnight*, *Slate*, *AMOLED*, *Light*, *Christmas*, and *Galaxy* themes with custom accent colors. |
| **Discord Rich Presence** | Work in progress. |

---

## Upcoming / Planned

* **Full Controller Support:** Navigate the bottom dock, scroll game carousels, filter servers, and launch games with a gamepad.
* **Classic Pre-2023 Xbox Launcher Theme:** Recreates the 2016–2023 dark-blue Xbox One Roblox dashboard.
* **Optional Pre-2023 Xbox Logging-In Screen:** Toggleable classic blue console login/loading screen on startup.
* **Post-2023 Roblox Console Theme:** Recreates the modern PlayStation and Xbox console interface.
* **Expanded Theme System & Dedicated Themes Window:** Additional themes and a separate themes window to keep Settings clean.
* **Auto-Focus on Game Exit:** Automatically brings Nora to the front when closing Roblox.
* **Community Bug Fixes:** Ongoing fixes for issues reported by users.
* **Linux and MacOS Support:** Yes, Nora will fully support both of these OS's.

---

## Account Safety

* **No passwords or cookies:** Nora never asks for your Roblox password and does not access `.ROBLOSECURITY` cookies.
* **Official OAuth 2.0 (PKCE):** Account sign-in runs through Roblox's official browser OAuth flow, with refresh tokens encrypted locally via Windows credential storage.
* **No client modification:** Launches the unmodified Roblox client using standard `roblox://` protocol URIs and allowlisted `ClientAppSettings.json` flags.

---

## Installation

1. Download the latest `Nora Setup.exe` from **[Releases](https://github.com)**.
2. Run the installer. Because the executable is unsigned, Windows SmartScreen will show a warning—click **More info** -> **Run anyway**.
3. Nora detects your active `RobloxPlayerBeta.exe` path automatically on startup.

---

## Copyright

Copyright (c) 2026 zopriel. All rights reserved. No license is granted to copy, modify, distribute, or create derivative works from this project without permission from the repository owner.

Nora Launcher is not affiliated with, endorsed, or sponsored by Roblox Corporation.
