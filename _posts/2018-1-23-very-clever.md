---
layout: post
title: Clever one Square Enix.
---

This was actually noted a while ago, but I figured I'd mention it here also.

Final Fantasy 4 (NDS) has quite possibly some of the most clever AP I've seen.
Flashcarts (and at one point, bootstrap) check for whether a rom can be DLDI patched by searching for `Chishm` within the game's executable data.

If it's found, the rom is then patched and ran as homebrew... otherwise, the rom is assumed to be a retail game.


So, if a developer were to, say, throw in `Chishm` into their game, the rom loader would happily assume it was a homebrew, patch out important code, and make the game not run.

...which is exactly what Square Enix did.

Nice one.
