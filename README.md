<h1 align="center">Djorr — Portfolio</h1>

<p align="center">
  <strong>Minecraft plugins & Discord bots</strong><br>
  A showcase of the servers, plugins and bots I've built — what they do, how they work and what they look like.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Minecraft-Paper%20%7C%20Spigot-62B47A?style=for-the-badge&logo=minecraft&logoColor=white" alt="Minecraft">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/discord.js-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="discord.js">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
</p>

> Source code is not included in this repository — this is a visual portfolio only.

---

## 📑 Contents

| ⛏️ Minecraft | 🤖 Discord |
| --- | --- |
| [CrashVille](#-crashville) — full Dutch roleplay server | [DMuri](#-dmuri) — a bot that feels like a person |
| [MatrixPearls](#-matrixpearls) — Ender Pearl reliability + 3D replay panel | [BioVerse](#-bioverse) — profiles, avatars & community games |
| [YT-Builds](#-yt-builds) — automated cinematic build timelapses | [Invitree](#-invitree) — invite tracking with web dashboard |
| [Linguify](#-linguify) — per-player chat translation | [Bloom Cloud bot](#-bloom-cloud-bot) — licence management in Discord |
| [MT-Grinding](#-mt-grinding) — four grinding jobs | [d2s-bot](#-d2s-bot) — website live chat ↔ Discord |
| [Billify](#-billify) — FiveM-style invoices | [NexusBot](#-nexusbot) — 40+ utility features |
| [Dynamic Shop System](#-dynamic-shop-system) — supply & demand economy | |
| [Smaller plugins](#-smaller-plugins) | |

---

# ⛏️ Minecraft

## 🏙️ CrashVille

A complete Dutch roleplay server built as one large Paper plugin, with its own resource pack, hundreds of custom 3D models and a recreated map of Amsterdam and the Bijlmer.

<table>
<tr>
<td width="50%" valign="top">

**Gameplay**
- 💳 **Banking** — ATMs, card terminals and bank cards with a full banking UI
- ⛏️ **Jobs** — mining, fishing, mail, farming, lumberjack, garbage collector
- 📱 **Phone** — number, carriers, cell towers, apps, App Store, 112
- 🎰 **Casino** — blackjack, slots and a full Crazy Time studio
- 🚗 **Vehicles** — mileage, dirt, wear and trunk weight
- 🏠 **Plots** — buy or rent per day or week

</td>
<td width="50%" valign="top">

**Roleplay systems**
- 🚓 **Police** — handcuffs, frisking, fines, cells, police database
- 🚑 **Emergency services** — ambulance, fire department, enforcement
- 🏛️ **Municipality** — citizen numbers, ID cards, passports, permits
- 🖥️ **In-world computers** — OS with logins for staff, alderman, mayor
- 🏪 **Businesses** — chamber of commerce, wholesale, checkouts, alarms
- 📹 **CCTV** — live view, playback, export to a USB stick

</td>
</tr>
</table>

### World & buildings

![Buildings](images/crashville/gebouwen_overzicht.jpg)

| Amsterdam | Bijlmer |
| :---: | :---: |
| ![Amsterdam](images/crashville/amsterdam_top.jpg) | ![Bijlmer](images/crashville/bijlmer_top.jpg) |
| **Hospital** | **Police station** |
| ![Hospital](images/crashville/gebouw_ziekenhuis.jpg) | ![Police station](images/crashville/gebouw_politiebureau.png) |

### Jobs & machines

| Mine sorting belt | Sawmill |
| :---: | :---: |
| ![Sorting belt](images/crashville/jobs_mijn_sorteerband.png) | ![Sawmill](images/crashville/jobs_hout_zaag.png) |
| **Fish auction** | **Forklift** |
| ![Fish auction](images/crashville/jobs_vis_afslag.png) | ![Forklift](images/crashville/heftruck_3d.png) |

![Wholesale interior](images/crashville/groothandel_interieur.png)

### Casino

![Casino](images/crashville/casino_overzicht.jpg)

| Crazy Time wheel | Blackjack table | Slot machine |
| :---: | :---: | :---: |
| ![Wheel](images/crashville/crazytime_wiel_3d.png) | ![Blackjack](images/crashville/blackjacktafel_3d.png) | ![Slots](images/crashville/gokkast_3d.png) |

### Emergency services & vehicles

![Emergency services](images/crashville/hulpdiensten_overzicht.jpg)
![Civilian cars](images/crashville/burgerauto_overzicht.jpg)

| Ambulance interior | Lock picking |
| :---: | :---: |
| ![Ambulance](images/crashville/ambulance_interieur.png) | ![Lock picking](images/crashville/inbraak_slotpinnen.png) |

### Interfaces

| Phone | Police computer |
| :---: | :---: |
| ![Phone](images/crashville/gui_telefoon.png) | ![Police computer](images/crashville/computer_bureaublad_politie_gui3.jpg) |
| **Municipality — person record** | **CCTV camera HUD** |
| ![Person record](images/crashville/gemeente_persoonskaart_gui3.png) | ![Camera HUD](images/crashville/camera_hud_ingame.png) |
| **ATM** | **Bank card animation** |
| ![ATM](images/crashville/3_startscherm.png) | ![Card](images/crashville/pas_animatie.gif) |

<details>
<summary><b>More: all GUIs, inventories and items</b></summary>

![GUI overview](images/crashville/gui_overzicht.png)
![Inventories](images/crashville/inventories_overzicht.png)
![Items](images/crashville/items.png)

</details>

**Built with:** Java (Paper) · Gradle · custom resource pack with custom models and GUI textures

---

## 🟣 MatrixPearls

An Ender Pearl reliability system for Minecraft **1.7 – 1.20.4**, with its own web panel. On most servers pearls break at corners, trapdoors and glass, and nobody can tell afterwards why. MatrixPearls fixes that — and records every throw.

- 🧩 **Plugin** — shared core plus a compatibility module per Minecraft version, so behaviour is identical everywhere.
- 🎥 **3D replay panel** — every throw is stored as a replayable 3D scene: trajectory, landing block, and what the plugin decided (allowed, corrected or blocked) and why.
- 🔑 **Licences & accounts** — owners link servers, manage licences and file bug reports.

| Labelled impact | Live players |
| :---: | :---: |
| ![Impact](images/matrixpearls/fin-impact.png) | ![Live](images/matrixpearls/live-names.png) |
| **Building the scene** | **Result** |
| ![Build](images/matrixpearls/build-900.png) | ![Ring](images/matrixpearls/ring-done.png) |

**Built with:** Java (multi-version modules) · Nuxt · Three.js · Docker

---

## 🗼 YT-Builds

A fully automated pipeline that designs a Minecraft build, has it built and turns it into a cinematic timelapse — zero manual work.

1. 📐 A build plan is generated (current project: *The Forgotten Light*, an abandoned lighthouse on a rocky island).
2. 🧍 An NPC wearing my skin builds it block by block on a Paper server.
3. 🎥 An automatically launched Minecraft client acts as the camera, finds open ocean and records.
4. ✂️ The footage is edited into a timelapse.

<table>
<tr>
<td width="35%" align="center"><img src="images/yt-builds/timelapse.gif" alt="Timelapse"><br><sub>Timelapse (sped up)</sub></td>
<td width="65%">

![Overview](images/yt-builds/overzicht.jpg)

| During the build | Final result |
| :---: | :---: |
| ![Building](images/yt-builds/snap09.jpg) | ![Finale](images/yt-builds/f_07_finale.jpg) |

</td>
</tr>
</table>

**Built with:** Java (Paper plugin) · automated client · Python & ffmpeg

---

## 🌐 Linguify

Translates server chat for **every player individually** — works out of the box with free translation services, no API key needed.

- 💬 **Player chat** — a Spanish player sees Dutch chat in Spanish; hover reveals the original.
- 👋 **Join & quit messages** in everyone's own language.
- 🔌 **Server & plugin messages** (Essentials, WorldEdit, …) rewritten per player at packet level.

**Built with:** Java (Spigot/Paper) · packet interception

---

## 🎣 MT-Grinding

Four complete grinding jobs for Minetopia servers.

| Job | What it does |
| --- | --- |
| 🎣 **Fishing** | Minigame with a moving marker, green zone and rising loot rarity |
| ⛏️ **Mining** | Ores per pickaxe tier, regenerating blocks and a buy/sell NPC |
| 📦 **Mail delivery** | Pick up parcels and deliver them to the door the particles point to |
| 🌾 **Farming** | Sickle, grind wheat into flour at the mill, sell at the trader |

All tools wear down (Unbreaking included), configurable per ore or crop.

---

## 🧾 Billify

A FiveM-style invoice system for roleplay and economy servers (**1.14 – 1.20**). Players send each other invoices and manage open and paid ones in a GUI, opened via a command, item or block. Commands, permissions and menus are fully configurable.

---

## 🛒 Dynamic Shop System

A shop system for **1.21.5** with a realistic economy: admin shops with fixed prices, player shops with their own stock, categories, and **prices that move with supply and demand** — all through an extensive GUI, backed by a database.

---

## 🧰 Smaller plugins

| Plugin | What it does |
| --- | --- |
| **MTW-AntiDupe** | Detects and logs dupes via chests, hoppers, pistons, redstone, explosions, creative and commands (1.12.2) |
| **MTW-Dienst** | `/indienst` & `/uitdienst` — saves your inventory, gives your duty kit and restores everything afterwards |
| **MTW-Reports** | `/report <message>` to online staff, with cooldown and Discord webhook logging |
| **MinetopiaSDB BalTop** | Async balance top combining Vault balances and MinetopiaSDB savings, paginated (1.12 – 1.21) |
| **MinetopiaSDB BuildMode** | Safe build mode without external dependencies (1.12 – 1.18+) |
| **VloedjeSMP-Addon** | `/live` for streamers (tab tag, broadcast, glow) and `/portal` for Overworld ↔ Nether coordinates |

---

# 🤖 Discord

> ⚠️ **DMuri** and **BioVerse** are unreleased client projects. Their previews are watermarked.

## 💜 DMuri

A Discord bot that feels like a **person, not a command menu** — no AI backend, everything scripted.

- ⌨️ She reads before answering, then types for as long as her reply would really take.
- 🌗 A per-server mood that drifts on its own — lower at 4 am, higher in the evening, shifting with how people treat her.
- 🪪 Profile cards, levels, coins, leaderboards and chat games.
- 🤝 Best friends, favourites and interactions (wave, poke, pat).
- ✅ A full verification flow with animated explainers.
- 🎨 A persona system with its own character creator.

### Cards & profiles

| Profile card | Level card |
| :---: | :---: |
| ![Profile](images/dmuri/01-profile-card.png) | ![Level](images/dmuri/02-level-card.png) |
| **Leaderboard** | **Bio approved** |
| ![Leaderboard](images/dmuri/12-leaderboard.png) | ![Bio](images/dmuri/11-bio-approved.png) |

### Chat games

| Word scramble | Quiz | Winner |
| :---: | :---: | :---: |
| ![Scramble](images/dmuri/03-game-scramble.png) | ![Quiz](images/dmuri/04-game-quiz.png) | ![Win](images/dmuri/05-game-win.png) |

### Friendships & interactions

| Best friend request | Accepted |
| :---: | :---: |
| ![Request](images/dmuri/06-bestfriend-request.png) | ![Accepted](images/dmuri/07-bestfriend-accepted.png) |

![Best friend banner](images/dmuri/08-bestfriend-banner.png)

| Favourite | Wave | Poke | Pat |
| :---: | :---: | :---: | :---: |
| ![Favorite](images/dmuri/09-favorite.png) | ![Wave](images/dmuri/10-wave.png) | ![Poke](images/dmuri/10-poke.png) | ![Pat](images/dmuri/10-pat.png) |

### Persona & mood

| Persona creator | Mood |
| :---: | :---: |
| ![Persona](images/dmuri/persona-creator.png) | ![Mood](images/dmuri/mood.png) |

### Verification flow

| Get verified | Rules |
| :---: | :---: |
| ![Get verified](images/dmuri/GetVerified.gif) | ![Rules](images/dmuri/rules.gif) |
| **Explainer** | **Flagged zone** |
| ![Explainer](images/dmuri/VerificationExplainer.gif) | ![Flagged](images/dmuri/flagged_zone.gif) |

**Built with:** Node.js · discord.js · server-side image rendering

---

## 🌌 BioVerse

A community Discord bot built around **pixel-art avatars and profiles**. New members go through a guided onboarding (avatar, bio, birthday, pronouns, region, languages), then earn XP and coins, play chat games, build friendships and climb leaderboards.

- 🧑‍🎨 **Avatar builder** — layered skin tones, hairstyles and clothing, with a wardrobe to change outfits.
- 📝 **Bios with moderation** — submitted bios are reviewed by staff, with blacklist and length checks.
- 🪙 **Wallet, XP & bonds** — three leaderboards: XP, coins and friendships.
- 🎮 **Chat games**, greetings, favourites and best-friend cards.
- 🛡️ **Staff tools** — timeouts, bans, quarantine and appeals.

| Bios | Wardrobe |
| :---: | :---: |
| ![Bios](images/bioverse/bios.gif) | ![Wardrobe](images/bioverse/wardrobe.gif) |

![Avatar gallery](images/bioverse/avatar-gallery.png)

| Welcome card | Bio card |
| :---: | :---: |
| ![Welcome](images/bioverse/welcome-card.png) | ![Bio card](images/bioverse/bio-card.png) |
| **Wallet** | **Best friend card** |
| ![Wallet](images/bioverse/wallet-card.png) | ![Best friend](images/bioverse/bestfriend-card.png) |
| **XP leaderboard** | **Quiz** |
| ![Leaderboard](images/bioverse/leaderboard-xp.png) | ![Quiz](images/bioverse/game-quiz.png) |
| **Avatar onboarding** | **Greeting in chat** |
| ![Onboarding](images/bioverse/instruction-avatar.png) | ![Greeting](images/bioverse/greet-in-chat.png) |

<details>
<summary><b>How avatars are layered</b></summary>

![Layers](images/bioverse/layers-sample.png)

</details>

**Built with:** Node.js · discord.js 14 · sharp (image compositing)

---

## 🌳 Invitree

**See who invites who.** An invite-tracking bot with a web dashboard and documentation site.

- 🌳 **Invite tree** — follow who invited each member, multiple levels deep.
- 📊 **Stats & leaderboards** — joins, leaves, fakes and rejoins per inviter and per code.
- 🎁 **Rewards** — automatic roles at invite milestones (temporary rewards in Premium).
- 📣 **Campaigns & source links** — measure which channels bring in members.
- 🛡️ **Raid detection** — alerts on suspicious join spikes (kick & lockdown in Premium).
- 🖥️ **Web dashboard** — log in with Discord and manage everything per server.

| | Free | Premium |
| --- | :---: | :---: |
| Invite tree depth | 3 levels | 50 levels |
| Rewards | 3 | 50 |
| Campaigns | 1 | 25 |
| Stats history | 30 days | 365 days |
| Raid actions | Warning | Warning, kick, lockdown |
| Join DM & reports | ❌ | ✅ |

**Built with:** TypeScript · discord.js v14 · Next.js · Nextra · Turborepo · Docker

---

## ☁️ Bloom Cloud bot

Bloom Cloud (a licensing platform for developers) inside Discord. The bot has no database and no rules of its own: every command goes through the same services as the dashboard, with the same limits and audit log. Permissions come from the Bloom account of whoever typed the command — not from the bot.

**Built with:** TypeScript · discord.js · Docker

---

## 💬 d2s-bot

Connects a website's live-chat widget to Discord. Each conversation becomes its own thread in a forum channel, with visitor details and **Take over / Close** buttons. Support simply types in the thread and it arrives live for the visitor — and the other way round.

**Built with:** Node.js · discord.js · WebSockets · Docker

---

## 🧩 NexusBot

An all-in-one Discord bot with **40+ features**: games (counting, word snake, Akinator, coin drops), moderation, status roles, staff management, channel management and more.

**Built with:** Python · discord.py
