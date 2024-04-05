+++
title = "Dungeons Deep - Alpha Build 8"
date = 2024-04-05T15:00:00-04:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags: ["machine-learning", "deep-learning"]`
tags = ["game", "godot", "devlog", "dungeons deep"]

# Project summary to display on homepage.
summary = "Increasing the difficulty"

# Optional image to display on homepage.
image_preview = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use source code highlighting?
highlight = true
+++

A lot of work went into this build and I added quite a lot.

In an upcoming update, I plan to start adding shopkeepers. This means that players needed a way to earn money so enemies now give the player money when they die.

Speaking of the enemies, this build fixed a couple bugs with enemies. They used to attack silently. There was a small omission where `$Voice.stream` was set to the screaming sound, but `$Voice.play()` was never called to make them scream. They also can no longer spawn inside each other. I know, I know. But mythWizard, you said that last build. This time, if there's an enemy in the space, they won't spawn at all instead of trying to find a new space to spawn.

I also implemented a first pass at a difficulty curve. In my playtesting of some of the above features, I found myself absolutely swarmed by enemies on the first floor. Like, reached level 4 by the second room swarmed. So now enemies should spawn fewer at a time near the lower levels and increase in number and strength as you ascend. New types of enemies should also start spawning.

Lastly, this build adds some more to the UI by replacing the menu buttons, changing the game font, and adding clicks to the menus.