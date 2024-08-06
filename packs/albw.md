---
date: 2024-08-06
description: Replace the ALttP music with orchestrated equivalents from A Link Between Worlds.
slug: albw
tags: Extended MSU
title: A Link Between Worlds
type: pack
author: arborelia
musicians: Ryo Nagamatsu, Koji Kondo
released: 2024-08-06
version: 3.0
tracks: 54
link: http://arborelia.net/downloads/albw-msu-v3.zip
page: https://msu-1.link/albw
---

# Setting up this pack for the first time

On Windows, you can run `ALBW Pack Builder.bat` to create the PCM files you'll need.

Or you can run `msupcm.exe msu_albw.json` at the command line, or drag and drop
`msu_albw.json` onto `msupcm.exe`. All of these do the same thing.

msupcm.exe is a copy of msupcm++, by qwertymodo. The source code (which also runs on
Linux) is available at https://github.com/qwertymodo/msupcmplusplus.


# What is MSU-1?

[MSU-1][] is a custom co-processor for the SNES that allows it to play CD-quality
audio. It was designed long after the SNES era, so it never existed in an official
game cartridge, but it's implemented in modern SNES interfaces such as sd2snes,
and emulators such as [Snes9x][].

[MSU-1]: https://www.zeldix.net/t1607-msu1-getting-started-guide


# Playing ALttP with this pack

Put your ROM from the ALttP Randomizer in this folder. Name it "msu_albw.sfc".
Run it with [Snes9x][] 1.60 or later. (The music will be choppy on 1.55.)

[Snes9x]: https://github.com/gocha/snes9x-rr/releases

You can also use a vanilla ROM of ALttP if you apply its MSU patch. However, the
vanilla game doesn't support unique music per dungeon.

If you see directions telling you to disable music in the randomizer settings,
those directions are old and won't work. Music should be _enabled_.


# Some features of this pack

Unlike the original ALBW pack (which predates extended MSU-1 support in the randomizer),
this pack has unique music for most dungeons.

Where possible, I made use of the different variations on themes that appear in ALBW:

- Hyrule Overworld changes to Hyrule Overworld 2, including the initial fanfare, after
  you pull the pedestal.

- Lorule Overworld changes to Lorule Overworld 2 when you have 7 crystals.

- ALBW has five increasingly intense versions of the Lorule Castle theme, depending on
  the number of sections you've completed. On the OST and here, they're combined into
  one big track that plays them in order of intensity. I make it loop by going back to
  the 3rd version (so that the drumbeat doesn't suddenly drop out). So the loop goes
  1 2 3 4 5 5 3 4 5 5 ...

- Misery Mire is not a dungeon in ALBW, so in this pack, I use Hilda's theme (Princess
  Hilda Appears) for it.

- ALBW has a lot of battle themes for different situations, and I was able to use them to
  give almost every boss in ALttP a unique theme, with the Lorule boss theme used twice.


# Improvements over previous versions

Version 1.0 of this pack (from January 4, 2021) relied on the 3DS audio rips of the
soundtrack that could be found on KHInsider and YouTube. The biggest problem with these
was that they included game noises over the music, or cut off the beginnings of tracks.

To make this version, I purchased and ripped the official Japanese soundtrack CD, giving
me pristine versions of the game music, higher-quality recordings, and coverage of more
tracks.

The change from 2.0 to 2.1 is that I renamed the tracks to match the English titles
on the European release, instead of them being my own guesses at a translation from
Japanese. This doesn't change the audio at all, it just makes me feel that I'm no
longer adding to the proliferation of inconsistent, confusing track names.

In version 2.2 I reduced the overall volume level by 3 dB.

In version 3.0, I replaced "Hyrule Castle Battle Theme" with "Peaceful Hyrule Castle",
to avoid bullshit Content-ID claims against the Hyrule Castle theme when publishing
videos on YouTube.



# Track list

These tracks refer to tracks on the game's [OST CD set][ost], using the English titles
from the European release.

[ost]: https://www.discogs.com/Ryo-Nagamatsu-The-Legend-Of-Zelda-A-Link-Between-Worlds-Original-Soundtrack/release/6624211

```
 #  Usage in ALttP          Track on the ALBW OST
------------------------------------------------------------------------------
01  Opening theme           1-03 Title Screen
02  Light World             1-19 Hyrule Theme
03  Rain state              1-37 Restoring Queen Oren (Zora's Domain)
04  Bunny                   1-13 Ravio's Theme
05  Lost Woods              1-38 Lost Woods
06  Prologue                1-02 A Kingdom's Legend
07  Kakariko Village        1-15 Kakariko Village
09  Dark World              2-01 Lorule Theme
10  Pull pedestal           1-40 Master Sword Fanfare
11  File select             1-26 Mother Maiamai's Theme
12  Guards!                 1-07 Seres' Screams
13  Dark Death Mountain     2-02 Scaling Death Mountain
14  Minigame                1-24 Hyrule Hotfoot
15  Skull Woods overworld   1-39 Deeper Into the Lost Woods
16  Hyrule Castle           1-17 Peaceful Hyrule Castle
17  (vanilla) LW dungeon    1-20 The 3 Dungeons of Hyrule
18  Cave 1                  2-16 Dungeon - The Dark Palace
19  Boss victory            1-22 Beating the Boss
20  Sanctuary               1-11 At the Sanctuary
21  (vanilla) Boss          2-17 The Bosses of Lorule
22  (vanilla) DW dungeon    2-08 Dungeon - Thieves' Hideout
23  Shop                    1-23 Venturing Indoors
24  Cave 2                  1-08 Cavern Theme (Going Underground)
25  (vanilla) Zelda Rescue  1-18 Meeting Princess Zelda (with intro)
26  Crystal collected       1-18 Meeting Princess Zelda
27  Fairy fountain          1-04 Selection Screen
28  Agahnim zaps Zelda      1-32 Yuga's Theme
29  Ganon reveals himself   2-25 Ganon Returns
30  Drop in to Ganon        1-47 Ganon Appears
31  Boss: Ganon             2-26 Facing Ganon
32  Triforce room           2-20 Completing the Triforce
33  Triumphant Return       2-32 Credits (edited to fit in 3:49)
34  Credits                 Milk Bar medley: Zelda's Theme / Lorule Theme / Hyrule Theme
35  Eastern Palace          1-20 The 3 Dungeons of Hyrule
36  Desert Palace           2-10 Dungeon - Desert Palace
37  Agahnim's Tower         1-44 Between Worlds
38  Swamp Palace            2-11 Dungeon - Swamp Palace
39  Palace of Darkness      2-15 Sneaking Into the Dark Palace
40  Misery Mire             1-48 Princess Hilda Appears
41  Skull Woods (interior)  2-14 Dungeon - Skull Woods
42  Ice Palace              2-12 Dungeon - Ice Ruins
43  Tower of Hera           1-20 The 3 Dungeons of Hyrule
44  Thieves' Town           2-08 Dungeon - Thieves' Hideout
45  Turtle Rock             2-13 Dungeon - Turtle Rock
46  Ganon's Tower           2-23 Lorule Castle
47  Boss: Armos Knights     1-33 Facing Yuga in the Eastern Palace
48  Boss: Lanmolas          1-21 Hyrule Bosses
49  Boss: Agahnim 1         1-45 Facing Yuga in Hyrule Castle
50  Boss: Arrghus           2-05 Treacherous Tower
51  Boss: Helmasaur King    2-17 The Bosses of Lorule
52  Boss: Vitreous          2-17 The Bosses of Lorule
53  Boss: Mothula           1-49 StreetPass Battle Theme
54  Boss: Kholdstare        1-10 The Ruined Room (Battle Theme)
55  Boss: Moldorm           1-09 The Ruined Room
56  Boss: Blind             2-09 Don't Leave Me Here!
57  Boss: Trinexx           2-28 Final Showdown with Ganon (second half)
58  Boss: Agahnim 2         2-28 Final Showdown with Ganon (first half)
60  LW after pedestal       1-41 Hyrule Theme 2
61  DW after 7 crystals     2-22 Lorule Theme 2
```

Mother Maiamai's Theme (File Select) actually comes from the 3DS audio rip by
helsionium, because it's more complete than track 1-26 on the official OST. The
"Milk Bar Medley" was assembled by me from tracks included in helsionium's rip.

I edited the "Staff Credits" track from the OST, cutting out a section of the
music so it would finish at the length of the ALttP credits. And though in most
cases I appreciated the OST's clean recordings without sound effects, in the case
of the credits, I edited the sound of birds surrounding the pedestal back in.
Birds are nice.


# Previous versions

- Version 2.0: <http://arborelia.net/downloads/albw-msu-v2.0.zip>
- Version 2.2: <http://arborelia.net/downloads/albw-msu-v2.2.zip>


# About me

My Twitch channel is <https://twitch.tv/arborelia>. I play a lot of modes of
ALttPR and many other randomizers. You can follow me on Cohost as [arborelia](https://cohost.org/arborelia).
