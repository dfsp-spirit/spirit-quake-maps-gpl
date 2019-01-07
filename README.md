# spirit-quake-maps-gpl
The sources of my maps or levels for the Quake series FPS games, published under the [GPL](LICENSE).

![quake_maps](./spirit_quake_maps.png?raw=true "Quake maps by spirit")

# About

Quite a few years ago, I created some custom maps for the Quake series of first person shooter (FPS) games. This repository contains the sources (the .map files) for all my maps, releases under the GNU Public License 2.0. See the [LICENSE](LICENSE) file in this repo for the full license text.


# How to use this repo

Here are some answers to questions you may have regarding this repo.


## I just want to play the maps - what should I do?

You have come to the wrong place. To get compiled versions of the maps including all assets, download the pak files at [http://maps.rcmd.org](maps.rcmd.org) and read the installation instructions in the README file for each map. You cannot use the source files in this repo to play.

## How to load or modify these maps?

The map files can be opened and modified in popular level editors like [TrenchBroom](http://kristianduske.com/trenchbroom/) or [GtkRadiant](https://icculus.org/gtkradiant/).

## What exactly is included in this repo?

This repo contains only my work, the map files. It does **not** contain the assets used by the maps (textures, sounds, models) as these were not made by me in most cases and are thus not available under the GPL license (at least not from me).

## Who made the assets like textures and sounds? What is the license for them?

This differs for the assets of each map, and many maps use assets from several authors. See the README files of the full released version of the maps at http://maps.rcmd.org for each map. Some maps also use textures from the base game (these are never included in the download and may show up blank if you do not have the full game).

In general, it is pretty safe to assume that you will need to replace all assets if you want to build a version of the map that could be released under the GPL as a whole. This is also the way it is done in projects like OpenArena that ship with modified versions of my maps.

## I want to make a change and then get a new playable version of the map, using the textures and assets from the original version of the map. How can I do that?

In that case you will need to download the full map (pak/pk3 file in the zip) from http://maps.rcmd.org to get the assets, and the source file from this repo (unless it is already included in the full map download, which should be the case for most maps).

Then extract the pak/pk3 file into your mapping work space (usually in the Quake game directory) **preserving** the paths in the zip. This ensures that all assets get extracted and are placed where the maps expects them.

When you now open the map in your level editor of choice, all the textures and other assets should show up. After making your changes, you need to recompile that map to a bsp file. Your editor should allow you to do this. For some maps, I have documented the compilation settings I used in the README file for the map. If I didn't, you'll have to figure something out yourself (the settings also depend on the bsp tool you use, so you will most likely have to do this anyway to get good results).

**Important:** Please rename the bsp file and the zip file to a new name before distributing modified versions of the map! The GPL also requires you to do this: you are not allowed to make changes to the map and pretend this new version was made by me!

In the Quake community, it is common to give the map your name, so *spirit3dm2* is the second Quake 3 map made by me, spirit. If you modify it and make your own version, and you are known as johndoe, name the modified map *johndoe3dm1* or similar. Also create a new README file for the map.

## Do I need to ask the author to create something new based on these maps?

No, they are already published under a free software license. Just make sure you understand the GPL license, it's not that hard. If you made something cool, I'd be happy to hear about it though.

## Have some of these maps been used under the GPL already?

Yes, OpenArena has [a version of spirit3ctfduel1](http://openarena.wikia.com/wiki/Maps/oa_spirit3) and Negke made [an impressive single-player conversion of spirit1dm3](http://maps.rcmd.org/quake1/spirit1dm3/negke_sp_remix/spirit1dm3sp.zip). Some of my Quake 2 maps have been converted for Kingpin by [Mr. Damage](http://kingpin.info/), and some people have written me to show screenshots of new versions of various Quake 3 and Quake 2 maps I made. My map spirit2dm2 is part of [Quetoo, formerly known as Quake2World](http://quetoo.org/). The version was built by jdolan and me, it is known as [(In) the arms of Lilith](http://quetoo.org/books/media/arms-lilith-spirit). And Ricardo Stevens made a custom version of spirit3t3a and included it in [his Uber Arena mod](https://www.moddb.com/mods/uber-arena/) for Q3A.

## My question has not been addressed. How to contact the author?

See the contact page at [http://maps.rcmd.org](maps.rcmd.org).
