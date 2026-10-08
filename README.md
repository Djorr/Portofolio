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
| [CrashVille](#-crashville) — full Dutch roleplay server | [BioVerse](#-bioverse) — avatars, profiles & a human-like bot |
| [MatrixPearls](#-matrixpearls) — Ender Pearl reliability + 3D replay panel | [Invitree](#-invitree) — invite tracking with web dashboard |
| [YT-Builds](#-yt-builds) — automated cinematic build timelapses | [Bloom Cloud bot](#-bloom-cloud-bot) — licence management in Discord |
| [Linguify](#-linguify) — per-player chat translation |  |
| [MT-Grinding](#-mt-grinding) — four grinding jobs |  |
| [Billify](#-billify) — FiveM-style invoices |  |
| [Dynamic Shop System](#-dynamic-shop-system) — supply & demand economy |  |
| [Smaller plugins](#-smaller-plugins) |  |

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

**How it works:** each player picks their own language with `/lang` — through a menu, a clickable chat list or `/lang set <code>`. Linguify then translates player chat, join/quit messages and server/plugin messages into that language. By default chat keeps the original text with the translation on hover; in *replace* mode it's the other way round. Players toggle features and hover style in `/lang settings`. Free providers (Google, MyMemory) need no key, and every translation is cached so each text is only translated once.

| Choosing a language | Clickable chat picker |
| :---: | :---: |
| ![](images/linguify/ex-pick-language.png) | ![](images/linguify/ex-chat-selector.png) |

| Chat translated per player |
| :---: |
| ![](images/linguify/ex-chat-translation.png) |

| Personal settings (`/lang settings`) | Server statistics (`/lang stats`) |
| :---: | :---: |
| ![](images/linguify/ex-settings.png) | ![](images/linguify/ex-stats.png) |

**Built with:** Java (Spigot/Paper) · packet interception

---

## 🎣 MT-Grinding

Four complete grinding jobs for Minetopia servers. Every tool wears down (Unbreaking included), configurable per ore or crop.

### 🎣 Fishing
When a fish bites, a minigame appears on screen: a marker slides over a bar with a green zone. Right-click while it's in the green to fill the progress bar — miss and you lose progress. The further you get, the rarer the loot (Common → Legendary). Better rods fill faster and widen the green zone.

| Minigame flow | Fisher NPC shop |
| :---: | :---: |
| ![](images/mt-grinding/ex-fishing-minigame.png) | ![](images/mt-grinding/ex-fishing-shop.png) |

### ⛏️ Mining
Each ore has its own allowed pickaxes, required level, drop and regrow time. A mined ore turns into bedrock with a countdown hologram and grows back. The Miner NPC buys ores and sells pickaxes.

| Pickaxe rules & ore regeneration | Miner NPC sell flow |
| :---: | :---: |
| ![](images/mt-grinding/ex-mining-ores.png) | ![](images/mt-grinding/ex-mining-shop.png) |

### 📦 PostNL delivery
The postman hands out a route of 1–5 packages, each with its own resident, address and reward. The actionbar shows the distance, and a particle trail paths around walls to the right door, where a short knock-and-hand-over cutscene plays.

| Route & directions | Doorstep delivery |
| :---: | :---: |
| ![](images/mt-grinding/ex-postnl-route.png) | ![](images/mt-grinding/ex-postnl-delivery.png) |

### 🌾 Farming
Harvest crops with a hoe; they replant automatically. In the Farmer NPC's mill you put in wheat, click the gears and watch the progress bar turn it into flour, which sells for a high price.

| Farmer NPC & hoe shop | Mill flow |
| :---: | :---: |
| ![](images/mt-grinding/ex-farming-farmer.png) | ![](images/mt-grinding/ex-farming-mill.png) |

---

## 🧾 Billify

A FiveM-style invoice system for roleplay and economy servers (**1.14 – 1.20**).

**How it works:** players with the right rank send an invoice with `/invoice create <player> <amount> <reason>` — each rank has its own maximum amount, and the receiver is notified instantly. `/invoice` (or right-clicking a configured item or block) opens a menu with tabs for open and paid invoices, the player's balance and pagination. Clicking an open invoice pays it. Unpaid invoices past their deadline go to debt collection, which sends reminders, adds a fee and can collect automatically. Staff can view or cancel anyone's invoices.

| Sending an invoice | Open invoices menu |
| :---: | :---: |
| ![](images/billify/ex-create-invoice.png) | ![](images/billify/ex-open-invoices.png) |
| **Paying an invoice** | **Paid / cancelled history** |
| ![](images/billify/ex-pay-invoice.png) | ![](images/billify/ex-paid-invoices.png) |
| **Debt collection** | **Commands** |
| ![](images/billify/ex-debt-collection.png) | ![](images/billify/ex-commands.png) |

---

## 🛒 Dynamic Shop System

A shop system for **1.21.5** with a realistic economy.

**How it works:** `/shop` opens a category menu (Food, Tools, Blocks, Weapons, Armor, Misc). From there you browse admin and player shops, open an item to see its current price, base price, stock and % change, and buy or sell 1–64 at a time. Every 5 minutes player-shop prices move 5–25% based on supply and demand and are saved to a price history; stock refills every 10 minutes. Selling pays 80% of the buy price, while admin shops keep fixed prices and unlimited stock. Stored in SQLite or MySQL.

| Category menu | Shop item list |
| :---: | :---: |
| ![](images/dynamic-shop-system/ex-main-menu.png) | ![](images/dynamic-shop-system/ex-shop-items.png) |

| Buy flow: details → quantity → result |
| :---: |
| ![](images/dynamic-shop-system/ex-buy-flow.png) |

| Dynamic pricing: before, after and price history |
| :---: |
| ![](images/dynamic-shop-system/ex-price-change.png) |

| Shop management (`/shopadmin`) |
| :---: |
| ![](images/dynamic-shop-system/ex-shop-management.png) |

---

## 🧰 Smaller plugins

### 👮 MTW-Dienst — duty system for roleplay servers
Made for police, ambulance and other services on a roleplay server. Admins create a service with `/dienst maak <name>` and save a kit from their own inventory (`/dienst edit <name> setkit`). A player with permission runs `/indienst <name>`: their own items and armor are stored and replaced by the duty kit. `/uitdienst` restores everything exactly, so personal items and service gear never mix.

| Duty cycle: before → `/indienst politie` → kit → `/uitdienst` → restored |
| :---: |
| ![](images/mtw-dienst/ex-duty-cycle.png) |

| Admin setup | Permission & state checks |
| :---: | :---: |
| ![](images/mtw-dienst/ex-admin-setup.png) | ![](images/mtw-dienst/ex-permissions.png) |

### 🛡️ MTW-AntiDupe — dupe detection (1.12.2)
Watches for known dupe methods: rapid or multiple chest opening, breaking an open chest, hoppers, deaths near containers, oversized creative stacks and blocked commands like `/more`. Every detection alerts staff in-game, is written to a log file and can be posted to Discord. Repeat offenders get warnings (1/3 → 3/3) and are then kicked or banned.

| Staff alerts | Player warnings & kick |
| :---: | :---: |
| ![](images/mtw-antidupe/ex-staff-alerts.png) | ![](images/mtw-antidupe/ex-player-warning.png) |

| `/antidupe status` | Log file | Discord webhook |
| :---: | :---: | :---: |
| ![](images/mtw-antidupe/ex-status.png) | ![](images/mtw-antidupe/ex-log-file.png) | ![](images/mtw-antidupe/ex-discord.png) |

### 💰 MinetopiaSDB BalTop
`/sdbbaltop [page] [personal|savings|business|government|all]` adds up every player's MinetopiaSDB balances, shows server-wide totals per account type and a ranked, paginated list of the richest players. Fully asynchronous, works on 1.12 – 1.21.

| Page 1 with server totals | Pagination |
| :---: | :---: |
| ![](images/baltop/ex-baltop-page1.png) | ![](images/baltop/ex-baltop-page2.png) |

### 🏗️ MinetopiaSDB BuildMode
`/buildmode` puts staff in creative and stores their survival inventory, which comes back when they switch off — also automatically on restart or reload. While active they can build, but dropping or picking up items, opening containers and using entities are blocked, so creative items never leak into the economy.

| Enable / disable flow | What is blocked |
| :---: | :---: |
| ![](images/buildmode/ex-buildmode-toggle.png) | ![](images/buildmode/ex-buildmode-blocked.png) |

### 📺 VloedjeSMP-Addon
`/live` gives a streamer a `[LIVE]` tag in the tab list, announces the stream server-wide and makes them glow for 30 seconds. `/portal` converts your position into the matching Nether or Overworld coordinates (÷8 / ×8) so linked portals line up.

| [LIVE] tab tag | Stream broadcast | Portal coordinates |
| :---: | :---: | :---: |
| ![](images/vloedjesmp/ex-live-tab.png) | ![](images/vloedjesmp/ex-live-broadcast.png) | ![](images/vloedjesmp/ex-portal.png) |

---

# 🤖 Discord

> ⚠️ **BioVerse** is an unreleased client project. All previews are watermarked.

## 🌌 BioVerse

A community Discord bot built around **pixel-art avatars and profiles** — and a bot that feels like a **person, not a command menu**. There is no AI backend; everything is scripted. New members go through a guided onboarding (avatar, bio, birthday, pronouns, region, languages), then earn XP and coins, play chat games, build friendships and climb leaderboards.

- ⌨️ **Human-like replies** — she reads before answering and types for as long as her reply would really take.
- 🌗 **Mood per server** — drifts on its own (lower at 4 am, higher in the evening) and shifts with how people treat her.
- 🧑‍🎨 **Avatar builder** — layered skin tones, hairstyles and clothing, with a wardrobe to change outfits.
- 📝 **Bios with moderation** — submitted bios are reviewed by staff, with blacklist and length checks.
- 🪙 **Wallet, XP & bonds** — three leaderboards: XP, coins and friendships.
- 🎮 **Chat games**, greetings, favourites, best friends and interactions (wave, poke, pat).
- ✅ **Verification flow** with animated explainers.
- 🛡️ **Staff tools** — timeouts, bans, quarantine and appeals.

### Avatars & profiles

| Bios | Wardrobe |
| :---: | :---: |
| ![Bios](images/bioverse/bios.gif) | ![Wardrobe](images/bioverse/wardrobe.gif) |

![Avatar gallery](images/bioverse/avatar-gallery.png)

| Welcome card | Bio card |
| :---: | :---: |
| ![Welcome](images/bioverse/welcome-card.png) | ![Bio card](images/bioverse/bio-card.png) |
| **Profile card** | **Level card** |
| ![Profile](images/bioverse/01-profile-card.png) | ![Level](images/bioverse/02-level-card.png) |
| **Wallet** | **Bio approved** |
| ![Wallet](images/bioverse/wallet-card.png) | ![Bio approved](images/bioverse/11-bio-approved.png) |
| **Avatar onboarding** | **Persona creator** |
| ![Onboarding](images/bioverse/instruction-avatar.png) | ![Persona](images/bioverse/persona-creator.png) |

### Chat games & leaderboards

| Word scramble | Quiz | Winner |
| :---: | :---: | :---: |
| ![Scramble](images/bioverse/03-game-scramble.png) | ![Quiz](images/bioverse/game-quiz.png) | ![Win](images/bioverse/05-game-win.png) |

| XP leaderboard | Leaderboard |
| :---: | :---: |
| ![XP](images/bioverse/leaderboard-xp.png) | ![Leaderboard](images/bioverse/12-leaderboard.png) |

### Friendships, interactions & mood

| Best friend request | Accepted |
| :---: | :---: |
| ![Request](images/bioverse/06-bestfriend-request.png) | ![Accepted](images/bioverse/07-bestfriend-accepted.png) |

![Best friend banner](images/bioverse/08-bestfriend-banner.png)

| Favourite | Wave | Poke | Pat |
| :---: | :---: | :---: | :---: |
| ![Favorite](images/bioverse/09-favorite.png) | ![Wave](images/bioverse/10-wave.png) | ![Poke](images/bioverse/10-poke.png) | ![Pat](images/bioverse/10-pat.png) |

| Best friend card | Greeting in chat | Mood |
| :---: | :---: | :---: |
| ![Best friend](images/bioverse/bestfriend-card.png) | ![Greeting](images/bioverse/greet-in-chat.png) | ![Mood](images/bioverse/mood.png) |

### Verification flow

| Get verified | Rules |
| :---: | :---: |
| ![Get verified](images/bioverse/GetVerified.gif) | ![Rules](images/bioverse/rules.gif) |
| **Explainer** | **Flagged zone** |
| ![Explainer](images/bioverse/VerificationExplainer.gif) | ![Flagged](images/bioverse/flagged_zone.gif) |

<details>
<summary><b>How avatars are layered</b></summary>

![Layers](images/bioverse/layers-sample.png)

</details>

**Built with:** Node.js · discord.js 14 · sharp (image compositing)

---

## 🌳 Invitree

**See who invites who.** An invite-tracking bot with a web dashboard and documentation site.

**How it works:** Invitree caches every invite and its use count. When someone joins it compares the counts to find which invite was used and who owns it. Joins are counted as regular, left, fake or bonus, and suspicious joins (new accounts, no avatar, rejoins) are flagged. Raid protection watches for join bursts and can alert, kick or temporarily raise the verification level. Reward roles update whenever someone's invite count changes, and join messages, campaigns and source links are managed from the web dashboard.

| Invites, inviter and invited | Leaderboard |
| :---: | :---: |
| ![](images/invitree/ex-invites.png) | ![](images/invitree/ex-leaderboard.png) |
| **Invite tree** | **`/setup` with channel picker** |
| ![](images/invitree/ex-tree.png) | ![](images/invitree/ex-setup.png) |
| **Join log, suspicious join & raid alert** | **Bonus invites & campaigns** |
| ![](images/invitree/ex-alerts.png) | ![](images/invitree/ex-bonus-campaigns.png) |

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

Bloom Cloud (a licensing platform for developers) inside Discord.

**How it works:** the bot links a Discord server to a Bloom Cloud workspace. It has no database and no rules of its own — every command names the Discord user who ran it, and Bloom checks *their* account and role, so the bot follows exactly the same limits and audit log as the dashboard. Replies containing licence keys are ephemeral, so keys never end up in a channel. `/licence create` without options opens a step-by-step builder where each button fills in one field, and **Create** only appears once a product is chosen.

| `/bloom` status | Licence builder |
| :---: | :---: |
| ![](images/bloom-cloud-bot/ex-bloom-status.png) | ![](images/bloom-cloud-bot/ex-licence-builder.png) |
| **One-line licence create** | **Licence lookup** |
| ![](images/bloom-cloud-bot/ex-licence-create.png) | ![](images/bloom-cloud-bot/ex-licence-lookup.png) |
| **Permission denied & errors** | **Products** |
| ![](images/bloom-cloud-bot/ex-errors.png) | ![](images/bloom-cloud-bot/ex-products.png) |

**Built with:** TypeScript · discord.js · Docker
