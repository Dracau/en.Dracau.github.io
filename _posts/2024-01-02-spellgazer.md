---
title: "Spellgazer"
excerpt: >

classes: wide
header:
  overlay_color: "#5e616c"
  overlay_image: 
  overlay_filter: 0.3
---

![](../assets/images/spellgazer-learning-spell.gif)

The Game program at Rubika ends with a year dedicated entirely to a single game project, in my case, it's SpellGazer.

SpellGazer is a single-player exploration and observation game where the player must discover hidden constellations in the environment and trace them to learn spells. With these spells, they can manipulate what they find around them...

The main challenge of this project lies in the interactions between various elements of the game, which are numerous and often have special cases:

For example, with the "Expand" spell, the player can enlarge certain objects. However, when some objects grow, their behavior changes drastically. For instance, stars start burning their surroundings, leading objects exposed to heat to alter their behavior, and so on.

This project is a collaboration with a team of 10 people, including Game Artists, Designers, and Programmers.

![](../assets/images/spellgazer-burn.gif)

For this project, I took on the role of Unreal gameplay and tool developer.

I primarily work on different spells; since the game is highly systemic, the architecture must be as efficient as possible.

As a tool developer, I also created a tool that allows easy integration of constellations from the editor, in the same way than in the game. This tool saves a significant amount of time for the team, as without it, one would have to enter coordinates point by point for the trace.

![](../assets/images/spellgazer-constellation-forger.gif)

This tool is based on the same code as the in-game constellations, meaning that the tool will automatically evolve if we modify the way constellations work in the game.
