---
layout: post
title:  "Fairy-Stockfish 14.0.1 XQ"
categories: release
---
A new version of Fairy-Stockfish is available, see the [release notes](https://github.com/fairy-stockfish/Fairy-Stockfish/releases/tag/fairy_sf_14_0_1).

This release is specifically for providing built-in [NNUE](https://en.wikipedia.org/wiki/Efficiently_updatable_neural_network) networks for Xiangqi and Janggi, so that the NNUE evaluation can be used without the need for any additional downloads or configuration. This release of course still supports all other variants, but for those you can also use the smaller standard releases without built-in NNUE.

With NNUE evaluation, playing strength for Xiangqi and Janggi is far surpassing classical Fairy-Stockfish, and reaching super-human level. See the test results below for comparison against Fairy-Stockfish without NNUE.

#### Xiangqi

STC (10''+0.1'')
```
ELO: 541.10 +-95.1 (95%) LOS: 100.0%
Total: 200 W: 184 L: 1 D: 15
```
LTC (30''+0.3'')
```
ELO: 541.10 +-107.7 (95%) LOS: 100.0%
Total: 200 W: 186 L: 3 D: 11
```

#### Janggi

STC (10''+0.1'')
```
ELO: 350.27 +-73.4 (95%) LOS: 100.0%
Total: 200 W: 172 L: 19 D: 9
```
LTC (30''+0.3'')
```
ELO: 297.95 +-67.2 (95%) LOS: 100.0%
Total: 200 W: 167 L: 28 D: 5
```

### Files of the release
* The `.nnue` files do **not** need to be downloaded. They are only included in the release so that the build can be reproduced from source if desired.
* `.exe` are Windows executables, the files without extensions are Linux binaries.
* Use `bmi2` versions for best performance on modern hardware, or [fairy-stockfish-largeboard_x86-64.exe](https://github.com/fairy-stockfish/Fairy-Stockfish/releases/latest/download/fairy-stockfish-largeboard_x86-64.exe) for best compatibility.
* This release does not contain non-largeboard binaries, since they would not support Xiangqi and Janggi.
