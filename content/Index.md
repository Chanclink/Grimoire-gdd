---
title: GRIMOIRE - Game Design Document
version: 1.0
status: First Full Draft
tags: [gdd, grimoire, game-design, roguelike, deckbuilder]
created: 2024
---

# GRIMOIRE

## Quick Navigation

- [[GRIMOIRE - Vision & Core Pillars]]
- [[GRIMOIRE - Core Mechanics]]
- [[GRIMOIRE - Word System]]
- [[GRIMOIRE - Genre System]]
- [[GRIMOIRE - Bosses & Difficulty]]
- [[GRIMOIRE - World & Story]]
- [[GRIMOIRE - Technical & Prototype]]

---

## Vision Statement

**Grimoire** is a roguelike hybrid that mixes real-time top-down action combat with tactical turn-based deckbuilding. Players explore procedurally generated rooms in pixel-art fairytale worlds, switching dynamically between action and turn-based modes, where each mode directly influences the other due to his "Word Deck."

---

## Logline

*A "Storyteller", a tribe that disappeared of the world along all sort of stories, is now back and must discover why stories were banished and discover the remaining ones to spread them*

---

## Gameplay Synopsis

Players explore Isaac-style procedural rooms filled with enemies, secrets, and events. Combat begins in **real-time action mode**. When touched by an enemy or by player input under certain conditions, the game shifts into **turn-based combat**.

### Turn-Based Mode
- Player turn → Enemy turn structure
- Card-based system using Words from a deck
- Tactical resource management like "Action Point" and "Mana"

### Action Mode
- The top 3 cards of the deck become the player's "ammo"
- Each Word acts as a limited-use weapon
- When cards expire, they move to discard
- When deck empties, player must reload (temporary vulnerability window – TBD tuning)

(See Neon White system as reference)

Switching between modes reshapes battlefield momentum.

### Run Duration
- **20–25 minutes** rushing
- **40–60 minutes** exploring
- Meta progression exists through unlocks, not stat inflation

---

## Document Structure

This GDD is split into focused sections for easier navigation:

1. **[[GRIMOIRE - Vision & Core Pillars]]** - Core design philosophy and game structure
2. **[[GRIMOIRE - Core Mechanics]]** - Deep dive into action and turn-based systems
3. **[[GRIMOIRE - Word System]]** - The card/weapon system
4. **[[GRIMOIRE - Genre System]]** - Character archetypes and playstyles
5. **[[GRIMOIRE - Bosses & Difficulty]]** - Challenge design philosophy
6. **[[GRIMOIRE - World & Story]]** - Art direction, narrative, UI, and audio
7. **[[GRIMOIRE - Technical & Prototype]]** - Scope and development priorities

---

## Key Tags

#grimoire #action-roguelike #deckbuilder #dual-combat #word-system #genre-archetypes
