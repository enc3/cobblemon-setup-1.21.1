# Cobblemon Setup - Minecraft

# Please read this entire file like a literate person and practice some critical thinking. Thank you.
Minecraft setup for the [Cobblemon mod](https://modrinth.com/mod/cobblemon). If you don't have a launcher, I've posted a link for one on Discord.

# Minecraft setup

1. Download Minecraft ***1.21.1 Fabric*** (***not*** vanilla, or any other version). I've included this in the discord message as well.
2. If you don't wanna use launcher in the discord message, look up how to setup Fabric for `1.21.1`, its a straightforward process.

# Install Mods

1. Download as a ZIP and then unzip.

![Download as ZIP](assets/download-as-zip.png)

### Ignore the `assets/` folder.

2. Drag all the mods in `mods/` folder to your Minecraft mods folder, usually located at
    `C:/Users/name/AppData/Roaming/.minecraft/mods`

    Your `.minecraft/mods/` folder should look like this:

![Installed mods folder](assets/installed-mods.png)

3. Download latest version of Cobblemon mod separately, GitHub enforces a limit of 100MB per file, so cannot push it here\
https://modrinth.com/mod/cobblemon/versions?g=1.21.1&l=fabric \
This link should directly open the correct version; v1.21.1 and Fabric mod loader. ***Put the downloaded .jar file into your minecraft mods folder.***

# Install Resource Pack

1. Drag and drop the `resourcepacks/MysticMons_v3.2.1.zip` file in the `.minecraft/resourcepacks/` folder.

2. DO NOT UNZIP THIS FILE, keep it a zip.

3. After loading into the game, open the Resource Packs screen from the Options menu.
    You should see the MysticMons resource pack on the left, move it to the right to enable it and exit the screen.
    Pokemons like Dialga, Xerneas, Yveltal, etc. should be modelled.

Refer https://modrinth.com/datapack/mysticmons/ to see which pokemon are modelled.

# Post Install Check

### Reminder to download Cobblemon as well.
### Reminder to download and move resource pack as well.
1. Start the game, it should start normally without crashing.

2. To test if the mod works, create a new single player world with Creative mode and cheats enabled. Pressing `M` should open the starter pokemon selection menu. Commands like `/spawnpokemon`, `/spawnallpokemon` should be available (unless you forgot to enable cheats on world creation).

3. Change keybinds in `Options > Controls > Keybinds` menu. Video settings are in `Options > Video Settings`, you can adjust resolution, set full screen, etc.

4. Connect to the server, IP is in the discord message. If you cannot connect on the first try, retry a few times.

# Mods category

## Mandatory
- architectury
- Cobblemon
- fabric-api

## Performance (Recommended)
- c2me
- entityculling
- ferritecore
- ImmediatelyFast
- indium
- krypton
- lithium
- modernfix
- moreculling
- sodium-extra
- sodium

## Miscellaneous QoL
- BetterF3
- continuity
- modmenu
