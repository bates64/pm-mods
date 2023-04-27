# Skip developer logos

Simple package that skips the developer logos when starting the game.

## How it works

This feature already exists in the game, but it's turned off.

This mod changes `state_init_logos` to set `gGameStatus.bSkipIntro` to true, instead of false.
