---
title: Technical & Prototype
parent: "[[GRIMOIRE - Index]]"
tags: [grimoire, technical, prototype, scope, development]
---

← Back to [[GRIMOIRE - Index]]

# Technical Scope

## Platform & Technology

**Target Platform**
- PC first
- Single player only

**Art Pipeline**
- 2D pixel art
- Tile-based environments
- Sprite-based characters and effects

**System Complexity**
- Moderate complexity
- Core challenge: **smooth state transition system**
- Must handle seamless [[GRIMOIRE - Core Mechanics|mode switching]]

---

## Technical Challenges

### State Management
- Tracking deck state across modes
- Enemy state preservation
- Projectile handling on transitions
- Card tracking (active/hand/deck/discard)

### Performance
- Smooth 60 FPS gameplay
- Instant mode transitions
- No hitching during reload

### Polish Requirements
- Transition animations must feel good
- No jarring mode switches
- Clear visual/audio feedback

---

# Prototype Priority

The first prototype should prove the core concept: **Does mode switching feel powerful, not clunky?**

---

## Phase 1 Prototype

### Scope

**Environment**
- 1 single room
- Basic procedural enemy spawning
- No room transitions yet

**Character**
- 1 [[GRIMOIRE - Genre System|genre]] (Comedy - Arlequin)
- Basic movement and shooting
- Simple passive mechanic

**[[GRIMOIRE - Word System|Words]]**
- 6–8 test Words
- Mix of simple and complex
- Cover both mode archetypes

**Core Systems**
- Basic [[GRIMOIRE - Core Mechanics#Action Mode (Real-Time Combat)|action mode]]
- Basic [[GRIMOIRE - Core Mechanics#Turn-Based Mode|turn-based mode]]
- Mode switching triggers
- Basic reload mechanic

---

## Prototype Goals

### Primary Goal

**Test if switching feels powerful and not clunky**

### Key Questions to Answer
- Does the transition feel good?
- Is reload timing punishing but fair?
- Do Words feel impactful in both modes?
- Is the deck concept clear to players?
- Do players understand when to switch?

### Success Criteria
- Players actively choose to switch modes
- Mode switching feels strategic, not forced
- Core loop is engaging for 5+ minutes
- Concept communicates itself

---

## Phase 1 Priorities

### Must Have
- [ ] Smooth mode transitions
- [ ] Clear UI for both modes
- [ ] Basic deck/discard/reload cycle
- [ ] 3 enemies minimum
- [ ] Hit feedback and damage numbers
- [ ] Basic Word implementation

### Nice to Have
- [ ] Basic enemy AI variance
- [ ] Simple passive for Comedy
- [ ] Visual transition effect
- [ ] Audio feedback

### Explicitly Out of Scope
- Multiple rooms
- Multiple characters
- Bosses
- Meta progression
- Full Word pool
- Relic system
- Story elements

---

## Next Steps After Phase 1

Based on prototype feedback:

1. **Refine core feel** until switching is satisfying
2. **Add complexity** to Word interactions
3. **Expand to multiple rooms** with Isaac-style layout
4. **Add second genre** to test diversity
5. **Implement basic boss** to test multi-phase design
6. **Begin meta progression** hooks

---

## Related Sections

- [[GRIMOIRE - Core Mechanics]] - What needs to be built
- [[GRIMOIRE - Word System]] - Prototype Word needs
- [[GRIMOIRE - Genre System]] - Comedy implementation

---

#technical #prototype #development #scope #phase-1 #testing
