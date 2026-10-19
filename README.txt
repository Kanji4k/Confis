HOW TO BUILD (GitHub, no installs)
1. Create a free account at github.com and click New repository (name: confis-client, Public or Private).
2. On the new repo page click "uploading an existing file", drag in EVERYTHING from this folder
   (including the hidden .github folder) and click Commit changes.
   Tip: easiest is to drag the folders themselves: .github, intermediary-src, src, tools plus the
   loose files build.gradle, gradle.properties, settings.gradle.
3. Click the Actions tab -> "Build mod" -> wait ~3-6 minutes for a green check.
4. Open the finished run -> scroll to Artifacts -> download confis-mod-jar -> unzip -> put the .jar
   in .minecraft/mods (Fabric Loader + Fabric API required).
If the run is red, open it, copy the red error text, and send it to Claude.

WHAT'S NEW IN THIS VERSION (all show up as modules when you press Right Shift)
- Inventory Hub, Totem Count, Potion Count, Saturation, Zoom (key changeable in its options), Tier Tagger
  (PvPTiers / MCTiers / both), Shulker Tooltip (hold Shift over a shulker box), Crosshair Indicator.
- Effect Timer now shows the effect icon instead of the effect name.
- Item Guide: click an item to see its crafting recipe and where to find it.
- Name badge: "C" before your own name; other mod users get it too if you set "userListUrl" in
  .minecraft/config/confis0oooooo.json to a text file (one player name per line).
- Tier tagger web addresses are in the same config file (tierUrlMc / tierUrlPvp) in case a site changes its API.
