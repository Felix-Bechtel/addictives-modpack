# Addictives Modpack — Minecraft 1.21.1 · NeoForge 21.1.240

A small Create-based drug/brewing modpack + realistic plant spawns.
**Java Edition only — Bedrock CANNOT join.**

> ⚠️ **EXACT versions matter.** You must use **Minecraft 1.21.1** and **NeoForge 21.1.240** — not any other build. If your NeoForge is even one number off (e.g. 21.1.233), the server will reject you with *"Incompatible client."*
> **Do NOT install NeoForge for 1.21.11** — the server is 1.21.1.

📖 **[Full gameplay guide: plants, drugs, meth & booze →](GUIDE.md)**

**Server address:** `51.79.109.64:25592`

---

# 🎮 How to Join — EXACT Step-by-Step

## STEP 1 — Install Java 21 (needed to run NeoForge's installer)
1. Go to **https://adoptium.net/temurin/releases/?version=21**
2. Download **JDK 21** for your system (Windows `.msi` or macOS `.pkg`).
3. Install it (double-click, click through).

## STEP 2 — Get Minecraft 1.21.1 in the launcher
1. Open the **official Minecraft Launcher** and log in.
2. Click the version dropdown (left of the green PLAY button) → **Latest release** may not be 1.21.1, so:
   - Go to **Installations** tab → **New installation** → set **Version = release 1.21.1** → **Create**.
3. **Play 1.21.1 once** (let it load to the main menu), then **quit**. (This makes sure 1.21.1 files exist.)

## STEP 3 — Install NeoForge 21.1.240 (the EXACT loader)
1. Go to **https://maven.neoforged.net/#/releases/net/neoforged/neoforge/21.1.240**
   - (Or https://neoforged.net → *Downloads* → scroll to **1.21.1** → find **21.1.240**.)
2. Download the file named exactly: **`neoforge-21.1.240-installer.jar`**
3. **Double-click** the installer.
   - If it opens a text/code editor instead of running, right-click → **Open With → Java (or "OpenJDK Platform binary")**.
4. In the installer window: select **"Install client"** → make sure the path points to your `.minecraft` folder → click **OK**.
5. Wait for **"Successfully installed client"** → close it.

## STEP 4 — Download the modpack
1. Open the **[Releases](../../releases)** page of this repo.
2. Under the newest release → **Assets** → click **`friends-modpack.zip`** (downloads to your **Downloads** folder).

## STEP 5 — Unzip it
- **Windows:** right-click `friends-modpack.zip` → **Extract All** → **Extract**.
- **Mac:** double-click the zip.
- You now have a folder containing **10 `.jar` files** (listed in Step 7).

## STEP 6 — Open your `mods` folder
**Windows:**
1. Press **`Windows key + R`**.
2. Type exactly: **`%appdata%\.minecraft`** → press **Enter**.
3. If there's no **`mods`** folder: right-click → **New → Folder** → name it exactly **`mods`**.

**Mac:**
1. **Finder** → menu **Go** → **Go to Folder…**
2. Paste exactly: **`~/Library/Application Support/minecraft`** → press **Enter**.
3. If there's no **`mods`** folder, create one named exactly **`mods`**.

## STEP 7 — Put ALL 10 mods into the `mods` folder
Drag **all 10 `.jar` files** from the unzipped folder into `mods`. It must contain EXACTLY these (no more, no less):
```
create-1.21.1-6.0.10.jar
addictives-3.1.3.jar
createbb-1.1.3.jar
dinobriks-rum-2.0.jar
jei-1.21.1-neoforge-19.32.0.359.jar
embeddium-1.0.15+mc1.21.1.jar
modernfix-neoforge-5.27.15+mc1.21.1.jar
ferritecore-7.0.3-neoforge.jar
realisticspawns-1.0.0.jar
cartelcontinents-1.1.13.jar
```
> If you already had OLD mods in there (or `voicechat`), **delete them first** so only these 10 remain.

## STEP 8 — Launch with NeoForge
1. Open the **Minecraft Launcher**.
2. Version dropdown (left of PLAY) → select **`NeoForge 1.21.1`** (the installer created this).
3. Click **PLAY**. First launch takes 1–2 minutes.

## STEP 9 — Join the server
1. **Multiplayer → Add Server**.
2. **Server Address:** `51.79.109.64:25592`
3. **Done** → double-click the server to join. 🎉

---

# ⚠️ Troubleshooting (read if it won't connect)
- **"Incompatible client! Please use NeoForge 21.1.240"** → your NeoForge is the wrong version. Redo **Step 3** with exactly **21.1.240**, and pick the `NeoForge 1.21.1` profile in Step 8.
- **"Outdated client/server" / mod mismatch** → your `mods` folder doesn't match. It must be EXACTLY the 10 files in Step 7 (delete anything extra, including any `voicechat` jar).
- **Crash on launch (Mac)** → delete `embeddium-1.0.15+mc1.21.1.jar` from `mods` (FPS mod, unstable on some Macs). Everything else still works — the server doesn't need it.
- **Server unreachable** → the host's server must be online.
- **Bedrock can't join** → Java Edition only.

---

## Mods (8) + 2 built-in feature packs
| Mod | Version | Source |
|-----|---------|--------|
| Create | 1.21.1-6.0.10 | https://modrinth.com/mod/create |
| Create: Addictives | 3.1.3 | https://www.curseforge.com/minecraft/mc-mods/create-addictives |
| Create: Broken Bad (ReBroken) | 1.1.3 | https://modrinth.com/mod/create-broken-bad-fabric |
| DinoBriks Rum | 2.0 | https://modrinth.com/mod/dinobriks-rum |
| JEI | 1.21.1-19.32.0.359 | https://modrinth.com/mod/jei |
| Embeddium (FPS) | 1.0.15 | https://modrinth.com/mod/embeddium |
| ModernFix (performance) | 5.27.15 | https://modrinth.com/mod/modernfix |
| FerriteCore (less RAM) | 7.0.3 | https://modrinth.com/mod/ferrite-core |

> Tip: **Video Settings → Max Framerate → Unlimited** for better FPS.

### Built-in feature packs (bundled, no setup)
| Jar | What it does |
|-----|--------------|
| `realisticspawns-1.0.0.jar` | Wild drug plants spawn in the right biomes (~1 per 20 chunks) + balanced seed drops (1 seed + 5% bonus). Applies to your own singleplayer worlds automatically. |
| `cartelcontinents-1.1.13.jar` | Ocean-separated **continents** worldgen — applies to **new** singleplayer worlds you create. |
> On the **server**, these features are already active for everyone. These two jars give you the same thing in your **own singleplayer** worlds. If you ever can't connect to the server, delete these two — they're only needed for singleplayer.

## Custom plant spawns (`realistic-spawns` datapack — already on the server)
- **Biomes:** weed→jungles · coca→windswept hills · poppy→plains/meadow · tobacco→savanna · shrooms→forests/swamps
- **Rarity:** ~1 wild patch per 20 chunks (only in newly-explored chunks)
- **5% bonus seed** when harvesting a fully-grown crop
- Singleplayer only: add `realistic-spawns.zip` (from Releases) at **Create New World → Data Packs**.
