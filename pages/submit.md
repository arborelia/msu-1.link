---
date: 2021-12-20
slug: submit
title: Submitting packs
type: text
---

This site is run by arborelia, and provides a curated selection of MSU-1 packs, separate from the spreadsheet on the ALttPR Discord which aims to list all packs. On this site, you get a description page, a browseable list of packs you've created, and a nice link like [msu-1.link/celeste](https://msu-1.link/celeste).

If you'd like to add a pack to this site, fill in our **[submission form][]**.

[submission form]: https://forms.gle/8BMSahStGzHxnmst6

# General pack guidelines

The music should be easy to hear and appreciate, but not too loud.

If you're using MSUPCM++, a good starting point is to set its volume normalization to -21 dB for chiptune tracks and -19 dB for orchestrated tracks, but use your judgement. You'll probably need to be more specific about the volume for short tracks. There shouldn't be any tracks that suddenly sound much louder than the others.

Make sure to trim the boss victory fanfare to at most 11 seconds.

# Building packs after the download

If the pack is a "bring your own soundtrack" pack, or if it's built from compressed music like MP3s, provide a way to build the pack that will work for most people.

A common way to do this is:

- Include a copy of qwertymodo's `msupcm.exe` and the JSON file that builds the pack.
- Include a `.bat` file that runs the build with that JSON file.

The batch file can be very simple. Here's what I use:

```batch
msupcm.exe pack.json
pause
```

# Musicians should get paid

We don't want to rip off musicians here. If the music is from a soundtrack that's digitally for sale, then you should make a "bring your own soundtrack" pack, where the user buys the soundtrack and copies it into the pack in order to build it.

It's okay if you need to include extra tracks that aren't directly from the soundtrack, but most of the music should come from the purchased soundtrack.

**[Submit your pack][submission form]**