# Otherworld mods

Auto-update files for the Otherworld Minecraft server. The Otherworld Updater mod checks the latest release here when
the game starts: it downloads newer builds of the Otherworld mods (itself included), installs or updates the other mods the server's
modpack lists, and applies the changes when you close the game. Each release has the Otherworld mod jars and a
`manifest.json` (build ids, versions, sizes and SHA-256 checksums). Other authors' mods are not hosted here: the
manifest points at their official Modrinth or CurseForge downloads.

To turn auto-update off, set `autoUpdate=false` in `config/otherworldupdater.properties`.
