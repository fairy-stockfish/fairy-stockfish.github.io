---
layout: page
title: Graphical User Interfaces
toc: true
permalink: /gui/
---

For offline usage of Fairy-Stockfish you need to [download Fairy-Stockfish](/download/) as well as a compatible graphical user interface (GUI). If you want to first try it online out without any downloads, you can have a look at the [websites using Fairy-Stockfish](/online/).

You can use one of the GUIs listed below or any other chess variant GUI that is compatible with the supported protocols (UCI, UCCI, USI, UCI-cyclone, CECP/xboard). For documentation about protocols used for chess variants, see the [chess variant standards page](/chess-variant-standards/).

## Overview
There are several chess variant GUIs with different strengths and weaknesses, so please check which one best suits your use case. If you want to do analysis for common chess variants, [LiGround](#liground) and [PyChess](#pychess) should be good options for easy to use GUIs. If you are more interested in running engine matches, [cutechess](#cutechess) is a very good choice. For custom variants and the most feature-rich GUI you can use [WinBoard/XBoard](#xboardwinboard), which however is less stable than the other options. If none of these GUIs supports the variant you want to use, then you can resort to [Fairyground](/online/) online, which by design should support almost all variants Fairy-Stockfish can support but maybe does not have the most intuitive and polished UI.

## LiGround
[LiGround](https://ml-research.github.io/liground.github.io/) is a modern cross-platform chess variant GUI. It supports all lichess variants as well as all major regional variants (Xiangqi, Shogi, Janggi, Makruk). Precompiled versions for each OS can be downloaded from the [releases](https://github.com/ml-research/liground/releases).

Its game logic uses the Fairy-Stockfish based ffishjs library, therefore it is very well compatible with Fairy-Stockfish.

## Cutechess
[Cutechess](https://github.com/cutechess/cutechess) supports many of the built-in variants supported by Fairy-Stockfish. It is very well suited for playing games (engine/human), but analysis functionality is very limited.

Engines can be added via `Tools`>`Settings`. Select the `Engines` tab, click on `+` and select the engine executable via the `Browse` dialog.

## PyChess
[PyChess](https://pychess.github.io/download/) also supports some of the variants, including Crazyhouse, Losers, Giveaway, Three-check, King of the Hill, ASEAN, Makruk, and Sittuyin.

## XBoard/WinBoard
Fairy-Stockfish also supports the CECP/XBoard protocol, so it can easily be used in [XBoard/WinBoard](http://hgm.nubati.net). WinBoard/XBoard is the most feature rich GUI in this list, but a bit older and less stable. On Windows, it is recommended to use an [up-to-date WinBoard version](http://hgm.nubati.net/WinBoard-AA.zip).

### Setup steps on Windows
1. Download the Fairy-Stockfish executable from the [latest release](https://github.com/fairy-stockfish/Fairy-Stockfish/releases).
2. Download [WinBoard](http://hgm.nubati.net/WinBoard-AA.zip) and extract the zip archive.
3. Open the Winboard folder and double click the winboard.exe.
4. Click on `Engines`>`Edit Engine List...`
5. Add one line similar to `"Fairy-SF" /variant=janggi -fcp "C:\fairy-stockfish-largeboard_x86-64.exe"` (adjust the path to where you put the .exe in step 1, and replace `janggi` by the default variant of your choice). Click on `commit changes` and `OK`.
6. Click on `Engines`>`Load New 1st Engine...` and double click on Fairy-SF.
7. The default variant you entered in step 5 should now be loaded automatically.

#### Troubleshooting
* If an engine-defined variant uses special moves or adjudication like, e.g., Janggi, `Test Legality` under `Options`>`General...` needs to be disabled or otherwise Winboard/XBoard might reject some engine moves or win claims.
* You can select other variants via `File`>`New Variant...`, or if the variant you are looking for is not in the list (as not all supported variants are displayed in the list) then you can enforce the variant by changing the default variant in the engine command from step 5 and redoing step 6. If you do this frequently, you can also copy&paste the entry in the variant list and create multiple entries for your favorite variants.

### Setup steps on Linux
See this guide to [compile XBoard on Linux](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Setting-up-Fairy-Stockfish-on-FICS#linux). You can skip the `--enable-zippy` flag if you do not intend to use XBoard to run an engine on ICS/FICS.

## Xiangqi GUIs (UCCI/UCI-compatible)
Fairy-Stockfish can be used in Xiangqi GUIs by adding it as a UCCI or UCI engine. In case of problems make sure that you downloaded the large-board version (`fairy-stockfish-largeboard...`), and that you are using a recent version, at least Fairy-Stockfish 13.

## Janggi / 장기 GUIs
For Janggi there is a [youtube video (신경망 이 장착 된 스톡 피쉬 장기 엔진 및 GUI 비교)](https://www.youtube.com/watch?v=nFr8E-vmlww) explaining the installation process in Korean for multiple GUIs, namely [LiGround](https://github.com/ml-research/liground), [WinBoard](http://hgm.nubati.net/WinBoard-AA.zip), and [Gulbi](https://gulbijanggi.com/).

## Shogi GUIs (USI-compatible)
Fairy-Stockfish can be used in USI compatible GUIs to play Shogi by adding it as a USI engine. In case of problems make sure in the engine configuration that the options `Protocol` and `UCI_Variant` are set to their defaults for the USI protocol, namely `usi` and `shogi`, respectively, and that you downloaded the large-board version (`fairy-stockfish-largeboard...`).

Fairy-Stockfish also has basic support for byoyomi time controls that are supported by some Shogi GUIs.
