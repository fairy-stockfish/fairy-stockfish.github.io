---
layout: post
title:  "Fairy-Stockfish 14"
categories: release
---
A new version of Fairy-Stockfish is available, see the [release notes](https://github.com/ianfab/Fairy-Stockfish/releases/tag/fairy_sf_14).

This release significantly enhances support for [NNUE](https://en.wikipedia.org/wiki/Efficiently_updatable_neural_network) evaluation, switching to a new network architecture and enabling to use it for much more variants including all major regional variants (Xiangqi, Shogi, Janggi, Makruk). As of the time of this release only a few networks are available yet, but many more are about to come. Also see the [NNUE overview](https://docs.google.com/spreadsheets/d/1fgGvBKleUOI1wZZbiNhpT98qhQ7mYuQ5kar1lTQ9g3w/edit?usp=sharing) and [patreon](https://www.patreon.com/ianfab).

### New
* NNUE generalizations in order to support most variants
	* Basically works with any piece types, board size, and pieces in hand
	* Only remaining limitation is that both sides need to have exactly one king each
* Variants
	* Sho Shogi
	* Opulent

### Improvements
* Merged new stronger NNUE architecture from official Stockfish (HalfKP->HalfKAv2).
* Extended range for UCI_Elo, so weaker levels can be selected.

### Fixes
* Fixed evaluation bug for extinction variants with piece drops

### Files of the release
* `.exe` are Windows executables, the files without extensions are Linux binaries.
* Versions containing `largeboard` have support for board sizes >8x8 (e.g., Xiangqi, Shogi), the others are faster but have only variants <=8x8.
* Use `bmi2` versions for best performance on modern hardware, or [fairy-stockfish-largeboard_x86-64.exe](https://github.com/ianfab/Fairy-Stockfish/releases/latest/download/fairy-stockfish-largeboard_x86-64.exe) for best compatibility.
* The `variants.ini` contains documentation and examples how to configure user-defined variants and pieces.

*Thanks to all [code contributors](https://github.com/ianfab/Fairy-Stockfish/blob/master/AUTHORS), [fishtest contributors](http://www.variantfishtest.org:6543/users), and supporters for their contributions to this release.*
