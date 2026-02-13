---
title: Core Mechanics
parent: "[[GRIMOIRE - Index]]"
tags: [grimoire, mechanics, action-mode, turn-based, combat]
---

← Back to [[GRIMOIRE - Index]]

# Core Mechanics

The game alternates between two combat modes, each using the same deck of [[GRIMOIRE - Word System|Words]] differently.

---

## Action Mode (Real-Time Combat)

### Perspective
Top-down 2D pixel art (Isaac-style)

### Movement
Free 8-directional movement

### Shooting System

**Active Cards**
- The **top 3 cards** of the deck are active
- Each card:
  - Represents a [[GRIMOIRE - Word System|Word]]
  - Acts as a weapon
  - Has limited duration or ammo
  - After expiration → Discard pile
  - has a link to its turn-based counterpart (e.g. A card that deal damage to multiple enemy in turn based, will have a large AOE)

**Reload Mechanic**
- When deck is empty:
  - Player must **Reload**
  - Movement lock (TBD tuning)

---

## Switching to Turn-Based

### Trigger Conditions

**Automatic Triggers**
- Contact with enemy body

**Manual Triggers**
- Player button press

**Advantage Trigger** 🎯
- Sweet spot / damage threshold
- If advantage condition met:
  - Player enters turn-based mode with bonus
  - Bonus type TBD: extra action? first strike bonus?

### Transition Effects
- All enemies currently in the room enter turn-based combat
- Projectiles are cleared on transition

---

## Turn-Based Mode

### Structure
```
Player Turn → Enemy Turn (repeat)
```

### Player Turn

**Hand & Deck**
- Base Hand size: **3 cards**
- Starting deck size: **8–10 cards** (TBD exact)

**Action Points System**
- [[GRIMOIRE - Word System|Words]] can cost Action Points
- Action Points refresh each turn

**Mana System**
- [[GRIMOIRE - Word System|Words]] can cost Mana
- Mana is flat at the start of the biome and a ressource that is hard to recover

**Card Effects**
Cards played affect:
- Deal Damage
- Afflicts debuff
- Buff yourself
- Manipulate your deck
- Shield/heal
- Have effect on the action mode

### Enemy Turn
All enemies act after the player's turn

Enemy indicates their action beforehand to let the player act accordingly

---

## Exit Conditions

### Leaving Turn-Based Mode

**Minimum Requirement**
- Player cannot leave until **at least one enemy is defeated**

**Exit Cost** (TBD)
- After first kill, player may exit **at a cost**
- Cost depends on:
  - Character archetype
  - Current build

### Returning to Action
- Enemies return to original positions
- Projectiles cleared
  or
- Possible short invulnerability window (TBD)

---

## Design Goals

- Both modes must feel powerful
- Switching should feel strategic, not punishing
- [[GRIMOIRE - Word System|Deck management]] matters in both modes
- High skill expression in mode transitions

---

## Related Sections

- [[GRIMOIRE - Word System]] - The shared arsenal
- [[GRIMOIRE - Genre System]] - How archetypes affect mode preference
- [[GRIMOIRE - Bosses & Difficulty]] - How bosses use mode switching

---

#combat-system #action-mode #turn-based #mode-switching #deck-management
