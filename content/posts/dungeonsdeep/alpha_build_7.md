+++
title = "Dungeons Deep - Alpha Build 7"
date = 2023-07-16T20:30:00-04:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags: ["machine-learning", "deep-learning"]`
tags = ["game", "godot", "devlog", "dungeons deep"]

# Project summary to display on homepage.
summary = "So many new enemies!"

# Optional image to display on homepage.
image_preview = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use source code highlighting?
highlight = true
+++

I don't remember which version of the game removed the ability for stronger enemy types to spawn, but at some point I did that in favor of adding a difficulty curve to the game.

This build adds some of the higher tier enemies to the assets and sets up a first pass at stats. They include:
- Gobbos
  - Gobbo Minion
  - Gobbo Archer
- Orcs
  - Orc Minion
  - Orc Barbarian
- Jotunns
  - Jotunn Warrior

I have thoughts to add a Jotunn Mage.

I have plans to implement boss fights further down the line. Perhaps one boss for each enemy type, as the head of the group or so, such as a Jotunn wielding a warhammer, an Orc wielding magic, a Gobbo with a sickle or a scythe.

Other changes include adding the licenses to the tree and a credits screen to attribute properly.

The last new change is a first pass at implementing stat boosts when levelling up. The player still cannot see their level, experience, or stats, but they exist under the hood and become apparent as you start dealing more and more damage to the Skellies.

Lastly, this build fixes the bug mentioned in the [last devlog]({{< ref "/posts/dungeonsdeep/alpha_build_6" >}}) where the game could not be started from the character selection screen and a bug where the player could only take one step.

This build of the game is now available publicly! You can find it here on [itch.io](https://mythwizard.itch.io/dungeons-deep)!
