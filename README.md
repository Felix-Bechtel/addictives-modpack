# Addictives Modpack (Minecraft 1.21.1 · NeoForge)

A small Create-based drug/brewing modpack with custom spawn/seed tweaks + performance mods.

## Install
1. Install **Minecraft Java Edition** and run **1.21.1** once.
2. Install **NeoForge 1.21.1 (21.1.233)** → https://neoforged.net/
3. From the latest **Release**, download **`friends-modpack.zip`**, unzip, and put the `.jar` files in your `mods` folder
   (Windows: `%appdata%\.minecraft\mods` · Mac: `~/Library/Application Support/minecraft/mods`).
4. Launch the **NeoForge 1.21.1** profile.

## Mods
| Mod | Version | Source |
|-----|---------|--------|
| Create | 1.21.1-6.0.10 | https://modrinth.com/mod/create |
| Create: Addictives | 3.1.3 | https://www.curseforge.com/minecraft/mc-mods/create-addictives |
| Create: Broken Bad (ReBroken) | 1.1.3 | https://modrinth.com/mod/create-broken-bad-fabric |
| DinoBriks Rum | 2.0 | https://modrinth.com/mod/dinobriks-rum |
| JEI | 1.21.1-19.27.0.340 | https://modrinth.com/mod/jei |
| **Embeddium** (FPS boost) | 1.0.15 | https://modrinth.com/mod/embeddium |
| **ModernFix** (performance) | 5.27.14 | https://modrinth.com/mod/modernfix |
| **FerriteCore** (less RAM) | 7.0.3 | https://modrinth.com/mod/ferrite-core |

> Performance: also set **Video Settings → Max Framerate → Unlimited**.
> Mac note: if Minecraft crashes on launch, remove `embeddium-*.jar` (Sodium-style renderers can be unstable on some Macs); the rest are safe.

## Custom logic — `datapack/realistic-spawns`
- **Realistic biome spawns:** weed→jungles, coca→windswept mountains, poppy→plains/meadow, tobacco→savanna, shrooms→forests/swamps.
- **Spawn rate:** wild plants appear ~1 per jungle/biome area (rarity 20).
- **5% bonus seed:** harvesting a mature crop has a 5% chance to drop an extra seed.

Singleplayer: add `realistic-spawns.zip` on **Create New World → Data Packs**.
