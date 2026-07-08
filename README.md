# Mod Starter Pack
## By QuieType

Hi! This isn't actually a mod, but a collection of other mods, all of them picked because I think they add a lot to the game without changing the core 'CrossCode' experience too much. If you decided to install mods for your first playthrough, or if you are just now playing with the mosdloader and want to try some small stuff that don't change the game overuch, this is for you!

Want more people to see this? If you have or make a Github account, press that little ⭐ button! (Engagementbait, github style!)

### Installing This Mod
Your going to need [CCLoader](https://github.com/CCDirectLink/CCLoader), Crosscode's current modloader, and the CCModManager mod that comes with it. For easy installation, I recommend following [Xenon's Excellent Guide](https://youtu.be/7oBYnF_xMvU).  
Afterwards, simply find this mod in the mod manager, select it, and press install.

Unlike most mods, which can also be installed manually, that can't really be done with this one. If you're installing mods manually, you should know why.

### Uninstalling This Mod

> [!WARNING]
> Crosscode's modloader does not currently support actual Manifests or Modpacks as some other games do. Because of the way this modpack was made, trying to uninstall it may result in unintuitive results. Please read the following if you want to uninstall or disable this mod or any of the included mods.

If you try to uninstall (using the mod manager's standard uninstall button) any of the mods that come with this one, you'll get a popup saying you can't, because 'Other mods depend on it.'  
Conversely, if you uninstall this mod, nothing will happen. This mod will be uninstalled, but the others will remain.

To uninstall all the mods in this pack, you will have to first uninstall this mod, *then* uninstall all the mods that come with it manually. Of course, you can also uninstall this mod just to uninstall *some* of the mods that come with it.  
I'm sorry it's confusing, but with the way the current mod manager works, that's the best way. 

(Here are the technical reasons behind what's going on here. You don't have to read it.) Because CCLoader doesn't support modpacks, this mod relies on the `dependency` system to include other mods. The dependency system is meant for a completely different purpose entirely: some mods use the code or files from other mods, and can declare them as dependencies, which causes the modloader to install them as they install the parent mods, as well as block uninstalling or disabling them unless the parent mods are disabled too.

### Included Mods

This mod pack includes the following mods:
#### [New Game++](https://github.com/CCDirectLink/CCNewGamePP)
Adds several additional New Game+ options to the game, which you can unlock like regular New Game+ options after beating the game. Many of these use cool systems from other mods that I didn't include here because they'd be cheats.
#### [Azure's Adjustments](https://github.com/Azure-Lazuline/azures-adjustments)
Balances the game, making certain enemies and Combat Arts fairer, as well as some ui changes. Read the [mod's page](https://github.com/Azure-Lazuline/azures-adjustments) for detailed tweaks (spoilers for mechanics but not story)
#### [El-Tweaks](https://github.com/elluminance/el-crosscode-tweaks)
Allows you to favorite trades, in a system exactly like the already-existing quest-bookmarking system, as well as many other useful tweaks. See the [mod's page](https://github.com/elluminance/el-crosscode-tweaks) for detailed tweaks (spoilers for mechanics but not story)
> [!WARNING]
> This mod adds a single cheat, an Item Spawner that must first be enabled in settings. If this is your first playthrough, or if you don't know what your doing, *please* don't touch it. This is the only part of any of the mods here that I think have the potential to actually ruin the experience of playing.
#### [Named Saves](https://github.com/canbora/cc-named-saves)
Allows you to name specific save files to whatever you wish. Useful!
#### [Rich Presence for Discord](https://github.com/CCDirectLink/CCdiscord)
Integrates Crosscode with Discord Rich Presence, allowing your friends to wonder what you've been playing for so long, and then causing them to buy the game as well. Recommend the mod (or this modpack) to continue the chain!
#### [Extra Dialogue](https://github.com/krypciak/cc-extra-dialogue)
Adds extra (canon-compliant) incidental party dialogue to the game, most of which you'll find in the dlc or late game. If you want to see the various possible conversations, check out the [mod's page](https://github.com/krypciak/cc-extra-dialogue), but beware spoilers!
#### [Fancy Crash](https://github.com/krypciak/cc-fancy-crash)
Currently, when Crosscode crashes it displayes the crash screen from early access, telling you to contact the game developers. Now that you're installing possibly game-breaking mods, use this (slightly) less scary crash screen instead! Now with configurable explosions!  
If you do crash, visit our [![discord](https://shields.io)](https://discord.gg/3Xw69VjXfW), and tell us what happened. Copying the crash log and list of mods is always a good idea.
#### [Dungeon Revisits](https://github.com/Azure-Lazuline/dungeon-revisits)
Crosscode, **spoilers**, has difficult zelda-like dungeons in it. This mod let's you play them again once you get modt of the way through the game. Don't worry: if you, like most of us, never want to see a crosscode dungeon again, just ignore those weird hologram panels next to the temple openings.
#### [Junolea Skin](https://github.com/Inevitabilis/CC-Junolea)
In case you live a productive life that doesn't spend most of the time on the internet, Radical Fish, the studio that made Crosscode, has their next game [Alabaster Dawn](https://store.steampowered.com/app/3110760/Alabaster_Dawn/) in early access now. This skin recolors Lea's hair to look more like Alabaster Dawn's protagonist, Juno. Access it the same way you'd access the dlc ninja skin, through the add-ons menu in your inventory.
#### [Load from Pause](https://github.com/Leo40Git/cc-load-from-pause)
This mod adds a button to your menu you may use once or twice. Why not?
#### [World Map Overhaul](https://github.com/dmitmel/cc-world-map-overhaul)
This is just a straight-up visual improvement. When I want to show someone who knows this game well how cool modding is, I show them a screenshot of this map once all areas are unlocked.
#### [Refund Circuits](https://github.com/quietype/qt-refund-circuits)
Like many RPGs, Crosscode has deliciously complex and windy skill trees. There's lots of cool stuff there, but Circuit Points are limited and *very* hard to refund. This mod, forked off a tool for speedrun testing, lets you do that much more easily.

### Mods That Almost Made it in
The following mods deserve a special mention, though for one reason or another I decided not to include them.

#### [Dmitmel's Tweak Pack](https://github.com/dmitmel/crosscode-tweak-pack)
This mod has a very nice amount of little tweaks and changes, but also many cheats and debig tools that are not good to have in the menu on a first playthrough. I highly recommend checking it out though!
#### [Remastered Melodies](https://github.com/Ronkad/CCRemasteredMelodies)
This mod lets you use alternate tracks for the games background music, which is cool. It also takes incredibly long to download, and can cause people downloading a mod called "Mod Starter Pack" to think something is broken. But you're down here, meaning you had the patience to read through this whole page, so I think you can handle it.
#### [Ninja Skin Rework](https://github.com/fauxless/crosscode-ninja-skin-rework)
Crosscode's Ninja DLC skin is charming, but missing many specific sprites and thus disables itself in cutscenes. This mod fixes that, but has manual installation steps and requires a paid cosmetic dlc, so I'm not putting it in.

### Credits
There is a very large amount of people who worked on these mods, and I'd like to thank all of them. Once this is installed, you'll see their names on all the mods they made.  
I'd also like to thank Xenon, a modder who took the time to teach modding as well as use it, allowing me (and maybe you!) to give back to this community.
