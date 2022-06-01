---
layout: page
title: Variants
permalink: /variants/
---

User-defined variants can be added via an INI-style configuration file and be loaded at runtime without needing to recompile the program. See the [variants.ini](https://github.com/ianfab/Fairy-Stockfish/blob/master/src/variants.ini) in the repository for documentation and examples of variant configuration.

## Loading variant configuration
You can either provide the configuration file at startup, e.g., `stockfish.exe load variants.ini`/`./stockfish load variants.ini` (Windows/Unix), or you can load it at runtime by setting the `VariantPath` UCI option to the path of your configuration file. For usage in GUIs the former option is recommended, because variants need to be known to the GUI at engine startup.

## Validation
In order to validate your variants.ini, run `stockfish.exe check variants.ini`/`./stockfish check variants.ini` on the command line, which should point you to potentially problematic parts of your configuration. Alternatively you can load your variant configuration file at https://fairy-stockfish-nnue-wasm.vercel.app/ in order to run the validation directly in your browser.

## Graphical user interface
If you want to test your variant in a GUI, you can use [FairyFishGUI](https://github.com/ianfab/FairyFishGUI), which can also load variants.ini files. Alternatively you can use [fairyground](https://fairyground.vercel.app/) for testing it in a browser.
