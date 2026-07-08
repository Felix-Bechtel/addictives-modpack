# Addictives Modpack (Minecraft 1.21.1 · NeoForge)

A small Create-based drug/brewing modpack with custom spawn/seed tweaks + performance mods.
**Java Edition only — Bedrock cannot join.** Ask the host for the current server address.

---

# 🎮 How to Join — Full Step-by-Step Guide

## Step 1 — Get Minecraft Java Edition ready
- You need **Minecraft: Java Edition** (not Bedrock / Windows 10 edition).
- Open the launcher and **play version 1.21.1 once**, then close it.

## Step 2 — Install NeoForge (the mod loader)
1. Go to **https://neoforged.net/** → downloads → get **1.21.1**, version **21.1.235**.
2. You'll get a file like `neoforge-21.1.235-installer.jar`.
3. **Double-click it** → choose **"Install client"** → **OK**.
   - If it won't open, install Java 21 first from **https://adoptium.net**, then retry.

## Step 3 — Download the mods
1. Go to the **[Releases](../../releases)** page of this repo.
2. Under the latest release's **Assets**, click **`friends-modpack.zip`**.
3. It saves to your **Downloads** folder.

## Step 4 — Unzip it
- **Windows:** right-click `friends-modpack.zip` → **Extract All** → Extract.
- **Mac:** double-click the zip.
- You now have a folder with **8 `.jar` files**.

## Step 5 — ⭐ Find the `mods` folder (the key step)
**Windows:**
1. Press **`Windows key + R`**.
2. Type exactly **`%appdata%\.minecraft`** → **Enter**.
3. Find the **`mods`** folder. If it's not there: right-click → **New → Folder** → name it **`mods`**.

**Mac:**
1. **Finder → Go → Go to Folder…**
2. Paste **`~/Library/Application Support/minecraft`** → Enter.
3. Find or create a folder named **`mods`**.

## Step 6 — Put the mods in
Copy all the `.jar` files from the unzipped folder **into the `mods` folder**. It should contain:
- `create-1.21.1-6.0.10.jar`
- `addictives-3.1.3.jar`
- `createbb-1.1.3.jar`
- `dinobriks-rum-2.0.jar`
- `jei-1.21.1-neoforge-19.27.0.340.jar`
- `embeddium-1.0.15+mc1.21.1.jar`
- `modernfix-neoforge-5.27.14+mc1.21.1.jar`
- `ferritecore-7.0.3-neoforge.jar`

## Step 7 — Launch with NeoForge
1. Open the Minecraft launcher.
2. Top-left dropdown (next to PLAY) → select the **NeoForge 1.21.1** installation.
3. Click **PLAY** (first launch takes a minute).

## Step 8 — Join the server
1. **Multiplayer → Add Server**.
2. **Server Address:** use **`51.79.109.64:25592`** (24/7 PebbleHost server).
3. **Done** → double-click to join. 🎉

### ⚠️ Troubleshooting
- **"Outdated / can't connect":** your 8 mods must match the host's exactly — the zip guarantees this.
- **Crash on launch (Mac):** delete `embeddium-*.jar` from `mods` (the FPS mod can be unstable on some Macs); everything else still works.
- **Server unreachable:** the host's server must be running.
- **Bedrock can't join** — Java Edition only.

---

## Mods
| Mod | Version | Source |
|-----|---------|--------|
| Create | 1.21.1-6.0.10 | https://modrinth.com/mod/create |
| Create: Addictives | 3.1.3 | https://www.curseforge.com/minecraft/mc-mods/create-addictives |
| Create: Broken Bad (ReBroken) | 1.1.3 | https://modrinth.com/mod/create-broken-bad-fabric |
| DinoBriks Rum | 2.0 | https://modrinth.com/mod/dinobriks-rum |
| JEI | 1.21.1-19.27.0.340 | https://modrinth.com/mod/jei |
| Embeddium (FPS boost) | 1.0.15 | https://modrinth.com/mod/embeddium |
| ModernFix (performance) | 5.27.14 | https://modrinth.com/mod/modernfix |
| FerriteCore (less RAM) | 7.0.3 | https://modrinth.com/mod/ferrite-core |

> Performance tip: set **Video Settings → Max Framerate → Unlimited**.

## Custom logic — `datapack/realistic-spawns`
- **Realistic biome spawns:** weed→jungles, coca→windswept mountains, poppy→plains/meadow, tobacco→savanna, shrooms→forests/swamps.
- **Spawn rate:** ~1 wild plant per jungle/biome area.
- **5% bonus seed:** harvesting a mature crop has a 5% chance to drop an extra seed.

The server already runs this. Singleplayer: add `realistic-spawns.zip` (from the Release) on **Create New World → Data Packs**.
