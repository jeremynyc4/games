# ABCDaGames

ABCDaGames is the home page for a set of small browser games, with one tile for each game.

## See It

[https://jeremynyc4.github.io/games/](https://jeremynyc4.github.io/games/)

You need a phone or a computer with a web browser. Tap a tile to play that game.

## How It Finds the Games

Each time the page loads, it asks GitHub for this account's public repositories and builds a tile for every one that:

1. Is named `game-`, a number, a hyphen, and the game's name, such as `game-04-help-desk-legends`.
2. Has GitHub Pages turned on.

To add a game to the page, publish a repository like that. Nothing on this page needs to change.

Each tile shows:

1. The game's cover picture, which is the `cover.png` file in the game's repository.
2. The game's name, which is the title of the game's own page.
3. The game's description, which is the description on the game's repository.

A game that is played somewhere else, such as Boombox Bars on claude.ai, is listed inside the page, with its cover picture in the `covers` folder here. Its tile says where it plays.

If GitHub cannot be reached, the page shows the games it knew about when it was last changed.

## Made with

Built with Claude Code in Vibe Coding for Nonprofits, a Whole Whale × Meet the Moment accelerator.
