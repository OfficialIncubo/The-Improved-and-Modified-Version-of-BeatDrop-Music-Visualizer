# The improved visualizer is here!
In this repo will fix the bug, adding new features and more stuff to BeatDrop Music Visualizer.

Things fixed:
* The y/n decision bug
* Keyboard function changes (F4: Show Preset Info, F5: Show FPS, F6: Show Rating, F1: Help)
* Help text changes
* Unlimited FPS, nTexSize to Auto, nCanvasStretch to 100 and more...

Features to be added:
* Always On Top Feature (Milkdrop2077 just helped me to implement this feature, this can be done now)
* Toggle 3D Support
* AI Transparency Mode (when turned on, it uses chroma key on the black screen (only without comp shader)).
* Getting BeatDrop's Song Title data from Windows Playback
* Spout Support ([Look DrO's Spout Addition for WACUP](https://github.com/WACUP/vis_milk2/commit/8bc232a670442c79713a15881504bf2813ef8554), [leadedge's Spout Version of BeatDrop](https://github.com/leadedge/BeatDrop))

Things that will be fixed:
* Doing a preset mashup will cause an error message on Windows 11.

---------------------------------------------------------------------------------------------------------------------------------------------

# BeatDrop Music Visualizer

BeatDrop is a stand-alone implementation of the amazing Milkdrop2 Winamp plug-in.

It lets you experience the stunning visual 2D effects with your music player of choice. No additional configuration steps needed! Just start BeatDrop and play your music.

Use BeatDrop with your favourite

* Music player:
  [foobar2000](https://www.foobar2000.org/),
  [VLC media player](https://www.videolan.org/vlc/index.html),
  [Clementine](https://www.clementine-player.org/),
  [AIMP](https://www.aimp.ru/),
  ...

* Web-based player:
  [SoundCloud](https://soundcloud.com/),
  [YouTube](https://www.youtube.com/),
  [Vimeo](https://vimeo.com/),
  ...

* Internet Radio station:
  [SomaFM](https://somafm.com/),
  [DI.FM](https://www.di.fm/),
  [RauteMusik.FM](https://www.rm.fm/),
  ...

## System Requirements
* Windows 11, Windows 10, Windows 8.1 or Windows 7 SP1

* WASAPI-compatible sound card

* DirectX 9 or higher - compatible GPU

* DirectX End-User [Runtimes](https://www.microsoft.com/en-us/download/details.aspx?id=8109) (also included in the installer) contains the required 32-bit helper libraries d3dx9_43.dll and d3dx9_31.dll

## Acknowledgements
Special thanks to:

* Ryan Geiss and Rovastar (John Baker) [official Milkdrop2 source code](https://sourceforge.net/projects/milkdrop2/)

* oO-MrC-Oo [XBMC plugin](https://github.com/oO-MrC-Oo/Milkdrop2-XBMC)

* Casey Langen [milkdrop2-musikcube](https://github.com/clangen/milkdrop2-musikcube)

* Matthew van Eerde [loopback-capture](https://github.com/mvaneerde/blog)

* and all the preset authors!

## License

[license]: #license

This repository is licensed under the 3-Clause BSD License ([LICENSE](LICENSE) or [https://opensource.org/licenses/BSD-3-Clause](https://opensource.org/licenses/BSD-3-Clause)) with the exception of where otherwise noted.

Although the original Matthew van Eerde's [loopback-capture](https://github.com/mvaneerde/blog) project didn't explicitly state the license, the author has been kind enough to provide the [license clarification](
https://blogs.msdn.microsoft.com/matthew_van_eerde/2014/11/05/draining-the-wasapi-capture-buffer-fully/)

> ### Sunny March 29, 2015 at 11:06 pm
> Hi. Just wondering is this open source? I'm looking for something like this for my school project.
>
> ### Maurits [MSFT] March 30, 2015 at 8:35 am
> @Sunny do with the source as you like.

All changes in this repository to the original Matthew's code are published either under the terms of BSD license or the license provided by original author.

## Contributions

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, shall be licensed as above.
