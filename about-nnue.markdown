---
layout: page
title: About NNUE
permalink: /about-nnue/
---

By default Fairy-Stockfish uses a handcrafted evaluation function to evaluate chess variant positions. In order to improve playing strength compared to the handcrafted evaluation, variant-specific NNUE (efficiently updatable neural network) evaluation files can be used. If you want to directly jump to the download, see the [NNUE download](/nnue/).

## What is NNUE?
NNUE are efficiently updateable neural networks, which were first applied to shogi, then later ported to [Stockfish](https://stockfishchess.org/), the engine that Fairy-Stockfish is based on. From there they made their way into Fairy-Stockfish. Several generalizations have been applied to the architecture of the neural network so that it can be used for different board sizes, arbitrary piece types, variants without kings, as well as variants with piece drops. See the [wiki of the NNUE training code](https://github.com/fairy-stockfish/variant-nnue-pytorch/wiki/Technical-details#variant-nnue-halfkav2-architecture) for technical details on these generalizations.

An overview over NNUE in general (not specific to variants or Fairy-Stockfish) can be found in the [chessprogramming wiki](https://www.chessprogramming.org/Stockfish_NNUE) as well as in the [documentation of the training code](https://github.com/fairy-stockfish/variant-nnue-pytorch/blob/master/docs/nnue.md).

## How strong is it?
In most variants NNUE is several hundred Elo stronger than the handcrafted evaluation, despite the latter usually already being on a high level. With NNUE Fairy-Stockfish plays on a superhuman and top engine level in almost all supported variants. See the [NNUE list](/nnue/) for details on how much stronger NNUE is in each variant compared to classical evaluation.

## How to use it?
In Fairy-Stockfish NNUE evaluation parameters can either be loaded at runtime from a file or included into the binary at compile-time. There is no functional difference between the two ways of loading them, it is just about convenience and file size. In order to use NNUE evaluation for chess variants in Fairy-Stockfish, you can either download a release with built-in NNUE, see the [download page](/download/), if you are very specifically interested in Xiangqi, Janggi, or Makruk, or follow the below steps to load NNUE networks at runtime for arbitrary variants:
* Download the NNUE evaluation file you want to use from the [NNUE download](/nnue/#current-best-nnue-networks).
* [Download Fairy-Stockfish](/download/).
* Set the path of the downloaded NNUE file in the `EvalFile` parameter in your GUI. Make sure that the name of the NNUE file starts with the name of the variant, as the file name is used to detect whether an NNUE file should be used for a given variant. For further details, see the [wiki](https://github.com/fairy-stockfish/Fairy-Stockfish/wiki/Settings#evalfile).
* When you select a variant for which an NNUE file was defined in the `EvalFile`, it will start using NNUE automatically.

## How is it trained?
Variant NNUE evaluation files for Fairy-Stockfish are trained using a fork of the [training code for official Stockfish](https://github.com/glinscott/nnue-pytorch) which contains many generalizations for variants with respect to board size, piece types, etc.
* Variant NNUE training code: [Visit on GitHub](https://github.com/fairy-stockfish/variant-nnue-pytorch)
* Fairy-Stockfish based training data generation: [Visit on GitHub](https://github.com/fairy-stockfish/variant-nnue-tools)

Documentation about the data generation and training process is available in its [wiki](https://github.com/fairy-stockfish/variant-nnue-pytorch/wiki). Trained networks can be uploaded using a [google form](https://forms.gle/8Am9LTqXQJo43ps79) and are then available for download at [google drive](https://drive.google.com/drive/folders/1m5PpiI3Kjzk_ow7F5RkwKnbO0Td-qb9J?usp=sharing). The below list of networks will be updated accordingly after a new strongest network has been uploaded.
