# Awesometastically Unleashed

If you've been invited to play on this private server, then welcome!

## Basic rules:

- Don't grief other players. Griefing is behaviour that will make the game less fun for other people, such as destroying their creations, stealing their stuff or killing them outside of an agreed-upon fight.
- Be responsible with your creations. Don't make things that will cause excessive server lag. Some key things that cause server lag include dropping a lot of loose materials, rapidly spawning blocks (eg water+lava=cobblestone) or rapidly oscillating redstone circuits.
- Don't do anything that will cause me to require more rules.

## Server details:

You can connect to the server using the following hostname:

> unleashed.undo.it

Before you do, please make sure you have your client set up properly and that you have been added to the whitelist.

The whitelist is a list of people who have been authorised to play on the server. Restricting the server in this manner allows us to keep out the rabid members of the public who want to come and destroy all of our creations for giggles.

## How to get added to the whitelist:

Currently, the only person who can do this for you is lukearndt. If you want to be added, contact him by any of the usual channels or raise an issue on this repository. If you haven't actually been invited (maybe you just found this page on while exploring the intercats?), you won't be added; it is a private server after all.

## Setting up your minecraft client:

If you haven't done this before, it can be a little daunting at first. It's not too bad, though, and I'll try to walk you through as clearly as I can.

### Get the launcher

The first thing that you'll need to get going is the Feed the Beast Launcher. You can find this here:

> http://feed-the-beast.com/launcher

#### If you're on windows:

Select the .exe and install it however you like.

#### If you're on OSX:

Select the .jar and put it in whatever folder makes you happy. I put mine in ~/minecraft to make it easier to launch from the terminal.

Minecraft works with Java 6 so to get it working on OS/X you need to point it to the 1.6.0 JDK.  To do this you can create a little start up script like so:

```bash
export JAVA_HOME=/System/Library/Java/JavaVirtualMachines/1.6.0.jdk/Contents/Home
$JAVA_HOME/bin/java -jar FTB_Launcher.jar
```

To make the script runnable, type chmod +x your_script_file_name

Put the script in the same directory as your minecraft stuff and run it to launch the game.

If you don't have Java 6 installed, you can find it here: http://support.apple.com/kb/DL1572

#### Once that's done...

When you open it for the first time, it'll ask you to set a folder location. That's where it'll store a bunch of stuff, and it might take up some space, so make sure you put it somewhere that you don't mind having large files downloaded to. I put mine in ~/minecraft for no particular reason.

### Put your minecraft profile into the launcher

Once you've downloaded and installed the launcher, open it up. At the bottom of the window you'll find a dropdown that says "Select Profile". Click on it and select "Create Profile". Type your minecraft details into the dialog box and hit Add.

Easy mode... unless you need to copy paste your password. It's not letting me do that on OSX. Time to type in a long string of garbage! Woohoo!

### Install the FTB Unleashed mod pack

Now that your profile is set up, it's time to grab the modpack. Make sure that you're on the tab in the middle called "Modpacks". Find "FTB Unleashed" in the list and double click on it. It may take a little while to download and install, unless your intertubes are awesome, in which case it won't take very long at all. When it finished, it rudely opened up minecraft before automatically closing both minecraft and the launcher. Your mileage may vary.

If it decides to be a miscreant on your system too, just open up the launcher again.

### Configure the FTB Unleashed mod pack

Select FTB Unleashed from the list of modpacks and hit 'Edit Mod Pack' to enable and disable mods. If you don't have the correct set of mods enabled and disabled, the server won't let you connect.

Enabled mods are on the left. Disabled mods are on the right. Use the arrows in the middle to move them around.

All of the mods should be enabled except the following:

- EnchantingPlus
- EquivalentExchange
- NetherOres
- Reliquary
- Vending

### Install a texture pack

This step isn't manditory, but your game will look really ugly if you don't do it. In the FTB launcher, navigate to the 'Texturepacks' tab. It's on the right hand side of the top menu.

I highly recommend Soartex Fanver. It works great with Feed the Beast and looks very nice.

To install a modpack, select it and then make sure FTB Unleashed is selected in the dropdown at the bottom left of the launcher. Then click Install TexturePack, conveniently located next to that dropdown.

Again, unless you're on some sort of awesometernet, it may take a while to load. Or not.

### Enable the texture pack

This step only applies if you actually installed a texture pack. If you took my advice, you should now launch FTB Unleashed. First, navigate to the 'Modpacks' tab of the launcher. Then select FTB Unleashed in the list of modpacks. Then make sure that the name of your profile is written in the dropdown at the bottom right. Finally, click Launch.

Once minecraft loads up, which may take a while, you'll be greeted with the titlescreen. It will probably tell you to update your client to the latest version.

#### DON'T UPDATE YOUR CLIENT TO THE LATEST VERSION.

Instead, click on Options followed by Texture Packs. Select the one that you installed. If you share my tastes, that will be Soartex Fanver. Once it's selected, click Done.

### Connect to the server

If you've enabled the texture pack, you'll know by now that to launch the game you need to click Launch at the bottom right of the Modpacks tab in the FTB Launcher. Make sure that you have the correct profile selected in the dropdown next to the Launch button.

Once the game client is open,

#### DON'T UPDATE YOUR CLIENT TO THE LATEST VERSION.

Instead, click on Multiplayer. Then click "Add Server" and type in the server details. You'll find them at the top of this document, but I'll be nice and give them to you again:

> unleashed.undo.it

Save them and then connect.

If it explodes in your face, first make sure that you've followed the instructions correctly. The error message that you receieve may give you an indication of what went wrong.

If you can't figure it out how to get it working, open an Issue on this github repository asking for help and quote the error message that you recieve. Or just ask me for help in person, 'cause that's probably easier.


If it doesn't explode, you're in. Have fun.

## How do I Unleash?

Never played Unleased before? There are a bucketload of mods that are included and it can be difficult to know where to start.

One approach is to pick some one or two mods to focus on at the start. Some of the more approachable mods include:

[BiblioCraft](http://ftbwiki.org/BiblioCraft)

BiblioCraft is a mod which adds a number of useful blocks, that are aesthetically pleasing and are used to display items and equipment. Most of these blocks allow quick and easy access to the items displayed on them, providing an excellent way for using them, while simultaneously freeing up storage space, when they are not needed anymore.

[Iron Chests](http://ftbwiki.org/Iron_Chests)

Iron Chests is a mod created by cpw. This mod adds a variety of new chests to the game in addition to iron chests. All are better than vanilla chests in that they have more capacity and can be placed next to each other.

[Twilight Forest](http://ftbwiki.org/Twilight_Forest)

Twilight Forest is a mod that adds a new dimension of the same name. As the name implies, the Twilight Forest is densely forested and in a perpetual twilight; the normal day-night cycle is suspended. An overstory of larger trees further shades most of the world below. The canopy is pierced only occasionally by massive trees that rise to the ceiling of the world. The terrain is flatter, or at least less mountainous than regular Minecraft, but featuring occasional hills, sometimes rising far above the canopy level. These hills are hollow, containing caves filled with valuable ores, treasure and dangerous monsters.

In addition to the new dimension, this mod also adds dungeons and bosses, as well as a number of new items, trees, and numerous mobs.

[Hats](http://ftbwiki.org/Hats_Mod)

Adds hats to the game. Kill mobs wearing the hat to unlock them.

### What next?

After this you'll probably want some form of power. Many of the machines in the more advanced mods use power of which there are two main forms. EU and MJ. EU is introduced by the mod IndustrialCraft and MJ by the mod Buildcraft. Most other machine based mods are extensions of one these two.

There are many many ways to produce energy. Solar, geothermal, boilers, wind, coal generators, oil refining, ethonol production. Pick your poison and go nuts. Hint: geothermal is a good option.

Some good cheap machines to start with come from the Thermal Expansion mod. They're generally relatively cheap to produce and take MJ as a unit of power.

Alternatively if machines aren't your thing you could try your hand at Thaumatugy. Thaumcraft allows you to use the magic around you in the form of "vis" (pronounced "veece") to perform different tasks and create fantastic items.

http://ftbwiki.org/ is your main resource. Direwolf20 puts out some great material on many of these mods as well: http://www.youtube.com/playlist?list=PL0356053BA45C3464
