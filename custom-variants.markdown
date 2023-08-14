---
layout: page
title: Custom Variants
permalink: /custom-variants/
---

Fairy-Stockfish already has many variants built in but can be extended by an even much larger variety of custom user-defined variants using a variant configuration file.

User-defined variants can be added via an INI-style configuration file and be loaded at runtime without needing to recompile the program. See the [variants.ini](https://github.com/fairy-stockfish/Fairy-Stockfish/blob/master/src/variants.ini) in the repository for documentation and examples of variant configuration.

# Example

Let's say we want to replace the bishops in chess with knight+bishop compound pieces, also referred to as archbishops. The configuration could look as follows:

```
# we name our variant "ourtestvariant" and let it inherit all the rules from "chess"
[ourtestvariant:chess]
# now we add the archbishop and assign it "a" as an abbreviation
archbishop = a
# since bishops are obsolete now, we remove them. This isn't strictly required, but recommended.
bishop = -
# we also need to update the promotion rules accordingly
promotionPieceTypes = nrqa
# and now let's define the new starting position
startFen = rnaqkanr/pppppppp/8/8/8/8/PPPPPPPP/RNAQKANR w KQkq - 0 1
```

And that's already it. We can now e.g. go to the [Fairy-Stockfish playground](https://fairyground.vercel.app/) to test it directly in the browser. Just paste the above configuration to a file and load that file in the `variants.ini` section. After selecting `ourtestvariant` you should be able to play the variant against the Fairy-Stockfish or let it play against itself.
