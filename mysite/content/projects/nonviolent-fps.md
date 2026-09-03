---
title: "Summer Research Nonviolent First-Person Shooter"
date: 2026-07-18
draft: false
description: "A Unity-based research project exploring whether the mechanics and progression of a first-person shooter could be recreated in a completely nonviolent game."
tags: ["Unity", "C#", "Game Development", "Game Design", "Research"]
weight: 2
---

## Overview

This summer, I had the opportunity to conduct research in game development using Unity around a central question:

**Is it possible to recreate the experience and mechanics of a violent video game within a completely nonviolent application?**

While the idea initially seemed straightforward, developing a game that could convincingly capture the fun and mechanics of a first-person shooter without introducing violence presented a number of challenges. Because players can have very different perceptions of what constitutes violence, every aspect of the game had to be carefully considered and tested.

I ultimately developed a nonviolent first-person shooter-style puzzle game. Instead of using guns or shooting living targets, the player uses a gauntlet that projects telekinetic beams of light. These beams can interact with and destroy objects such as crates and cameras, providing the point-and-click interaction associated with FPS games without relying on traditional weapons or enemies.

The game combines first-person movement, environmental puzzles, unique movement mechanics, and level-specific abilities. Each level introduces a new mechanic that changes how the player interacts with the environment, creating progression similar to unlocking new weapons or abilities in traditional FPS games.

## Research & Design

The central challenge of the project was maintaining the elements that make FPS games engaging while removing anything that could reasonably be interpreted as violent.

This required continuously experimenting with different mechanics and designs. Ideas that initially seemed acceptable sometimes introduced unintended associations with violence and had to be completely redesigned or removed.

Player testing became one of the most important parts of the research process. Testing allowed me to identify technical bugs while also observing how players interpreted the game. If a mechanic, object, or interaction was perceived as violent, I would return to the design and find a nonviolent alternative.

This iterative process ultimately shaped nearly every aspect of the game.

## Tech Stack

- **Engine:** Unity
- **Language:** C#
- **Development:** Game Development, Level Design, Player Testing
- **Research Focus:** Nonviolent Game Design, FPS Mechanics, Player Perception

## Core Mechanics

### Gauntlet

The traditional FPS weapon was replaced with a gauntlet that fires telekinetic beams of light.

Rather than shooting enemies, the player uses the gauntlet to place markings on and destroy environmental objects. This preserves the precision aiming and point-and-click interaction found in FPS games while removing the traditional weapon and combat systems.

### Crates

Crates replace traditional targets throughout the game.

Instead of being used as enemies or objects associated with combat, crates contain keys and other progression elements. This gives the player a reason to aim at and interact with objects while keeping the interaction completely nonviolent.

### Dropper Levels

Dropper-style rooms require the player to use precise aiming and movement to progress through the level.

These sections were designed to preserve the precision and challenge associated with FPS gameplay without requiring combat.

## Player Progression

A major challenge was recreating the progression found in violent FPS games.

Instead of unlocking new weapons, each level introduces a new ability or mechanic that changes how the player navigates the environment.

### Grappling Hook

The grappling hook provides a new movement mechanic that allows the player to reach areas that were previously inaccessible.

It serves as a nonviolent alternative to the movement and traversal abilities often introduced through progression systems in FPS games.

### Jumping & Sprinting Boots

The jumping and sprinting boots give the player enhanced movement abilities.

These abilities provide the feeling of gaining new equipment and becoming more capable as the game progresses without introducing weapons or combat.

### Teleportation Tool

The teleportation tool gives the player another way to navigate the environment and access areas that would otherwise be unreachable.

### Shrink Formula

The shrink mechanic allows the player to reduce their size and access new areas of the level.

This creates puzzles that require the player to think about the environment differently and provides another form of progression.

## Nonviolent Traps & Obstacles

Another challenge was creating failure conditions without using death.

Traditional games frequently use death as the consequence of failing a platforming section or encountering an obstacle. Instead, this game uses environmental consequences that reset the player's progress.

### Launch Platforms

Launch platforms throw the player backward when activated.

Rather than damaging or killing the player, the mechanic simply interrupts their progress and forces them to attempt the section again.

### Flying Obstacles

Flying obstacles move back and forth through sections of the level.

When they collide with the player, they knock the player from their position. The obstacles can also be destroyed using the gauntlet, giving the player something to aim at and interact with without introducing enemies.

### Quicksand

Quicksand causes the player to sink into the environment.

Instead of killing the player, falling into the quicksand resets them to an earlier point in the level.

### Restart Platforms

If the player falls into the void, they are not killed.

Instead, they are automatically reset to the appropriate location within the level.

### Rolling Boulders

Rolling boulders create timing and avoidance challenges.

Being hit by a boulder does not result in death. Instead, the player is returned to the beginning of the section and must try again.

### Fans

Timed fans push the player backward, requiring them to carefully time their movement through the level.

This creates an environmental challenge without relying on damage or violence.

## Player Testing

Player testing was one of the most important components of the project.

Testing served two purposes: identifying technical problems and evaluating how players perceived the game's mechanics.

Because the research focused specifically on removing violence, I paid particular attention to whether players interpreted any part of the game as violent. This included seemingly minor details such as failure states, environmental objects, and the way the player interacted with targets.

Whenever a mechanic or design element was perceived as violent, I returned to the design and experimented with alternative solutions.

This process resulted in numerous scrapped ideas and redesigns. It also reinforced an important lesson about game development: an idea can work technically while still failing to accomplish the intended experience.

## What I Learned

- Designing game mechanics around a specific research question
- Developing first-person gameplay systems in Unity
- Creating nonviolent alternatives to traditional FPS mechanics
- Designing progression systems without weapons or combat
- Building environmental puzzles around unique player abilities
- Using player testing to evaluate both usability and player perception
- Iterating on designs when an initially successful idea does not meet the project's goals
- Balancing technical implementation with the larger goals of a game design

## Research Question

The project ultimately demonstrated that many of the mechanics associated with violent FPS games do not inherently require violence.

Precision aiming, exploration, progression, movement abilities, environmental interaction, obstacles, and puzzle solving can all be recreated independently of traditional combat systems.

The project explored how separating these mechanics from their violent context can create a game that retains many of the engaging characteristics of an FPS while providing an entirely different player experience.

## Gameplay Video

<!-- Replace VIDEO_URL_HERE with your actual video link -->

[Watch Gameplay Video](VIDEO_URL_HERE)