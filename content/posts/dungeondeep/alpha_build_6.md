+++
title = "Dungeons Deep - Alpha Build 6"
date = 2023-05-25T12:00:00-05:00
draft = true

# Tags: can be used for filtering projects.
# Example: `tags: ["machine-learning", "deep-learning"]`
tags = ["game", "godot", "devlog", "dungeonsdeep"]

# Project summary to display on homepage.
summary = "Bug fixes galore!"

# Optional image to display on homepage.
image_preview = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use source code highlighting?
highlight = true
+++

This is the first version of the game that uses version control.

Alpha Build 6 of Dungeons Deep introduced a handful of new features:

- Leveling Up
- Inventory Infrastructure
- Passive Healing

You won't notice any of these changes visually. They will only become apparent once the UI for them is fleshed out. The only one you might loosely see is passive healing, as you wouldn't die so often anymore.

There were also many bugfixes implemented:
- Enemies no longer disappear on save/load
  - Fixed `match(c_enemy.enemy_type:)` cases
- Enemies can no longer occupy the same space in the world
  - Make the move function return when blocked
- Enemies can no longer spawn inside the player
  - Check for the player's position in `gen_enemy_position`
- Enemies can no longer spawn inside other enemies
  - Check for other enemies' positions in `gen_enemy_position`

This build is broken. Players cannot move past character selection. I found this out when I tried to show it to my dad.