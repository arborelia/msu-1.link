---
date: 2021-12-20
slug: help
title: How to use MSU-1
type: text
---

[MSU-1][] is a custom co-processor for the SNES that allows it to play CD-quality audio. It was designed long after the SNES era, so it never existed in an official game cartridge, but it's implemented in modern SNES interfaces such as sd2snes, and emulators such as [Snes9x][].

[MSU-1]: https://www.zeldix.net/t1607-msu1-getting-started-guide
[Snes9x]: https://github.com/gocha/snes9x-rr/releases

The packs on this site replace the music in an ALttP Randomizer game with a different soundtrack.

# Getting started on Snes9x

- Download and install [Snes9x][] 1.60 or later. (Earlier versions don't support MSU well or at all. If your music is extremely choppy, you have an old version.)

- Download and extract one of the packs from this site.

- Some MSU packs require you to set them up by copying your purchased soundtrack into the folder and running a script. Follow the directions for setting up the MSU pack.

- The MSU folder contains an empty file called `pack_name.msu` (for some `pack_name`). Put your ROM from the ALttP Randomizer next to it, named `pack_name.sfc`.

- Play the ROM with your up-to-date Snes9x. It should have the replaced music just because files with the appropriate names are next to it!

You can also use a vanilla ROM of ALttP if you apply its MSU patch. However, the vanilla game doesn't support unique music per dungeon.

If you see directions telling you to disable music in the randomizer settings, those directions are old and won't work. Music should be _enabled_. If you disable music you just won't have any music.
