---

**Obviously, there's been no activity here since initial start. Like many of my aspirations, this got sidelined quickly as I focused on other things. I'm leaving this here as a sort of tombstone/wishlist. Maybe I'll pick this up someday, but probably not in the same form.**

---

# Javascript a game
Make a game to learn how to code in javascript.

---

## Overview

### Goals
1. Learn how to code in Javascript.
2. Use my learning experience to help others learn.
3. Create something that others can use for their projects if they want to.

### Concept
Create a simple, stage-based beat-'em-up-style game with RPG elements. Enemies come in waves, and each stage must be cleared before moving on to the next.

### Philosophy
1. Create a modular system that encourages customization and extensibility. Allow people to use elements from the game engine inpdependently or create their own modules to extend the game.
2. Document everything as best I can.

### Limitations/Scope
- *No audio :(* - I'd love to be able to do some killer audio, but since this is a side project, I don't think I'll ever have the time or resources to pursue that realistically.
- *Infrequent updates* - This is a side project, so I don't have a production schedule and probably wouldn't be able to follow it even if I did. I'll churn through my backlog bit by bit.

---

## Contents
- [Roadmap](#Roadmap)
- [Feature wishlist](#Wishlist)
- [Reference](#Reference)

---

## <a name="Roadmap"></a>Roadmap

### Minimum viable product - Hello world

*Coding*
- Randomizer - based on 2 6-sided sice?
- Calculator for attack and hit points
- Player HP and attack
- 1 type of enemy with HP and attack
- Begin/end scenarios
- Time clock
- Game loop

*Graphics*
- 1 isometric tile 
 - Maybe just a diamond; to give the player and enemy graphics a place to stand and face one another.
 - No movement yet, so this is really just version zero
- Player hero facing right - simple shape graphics (fancy lighting etc. comes later)
- Enemy facing left - simple shape graphics
- 1 player attack animation
- 1 enemy attack animation

### MVP +1 - Put it on the map

- Wave counter/generator
- Isometric map
- Movement
- Collision detection
- Basic pathfinding for AI?

### MVP +2 - More than one thing

- Additional enemy type(s)
- Special attack(s)
- Experience tracking system
- Cash/loot system

---

## <a name="Wishlist"></a>Feature wishlist

- Interactive objects
- Stealing/looting weapons
- Bosses
- Puzzle elements
- Custom map creator UI

---

## <a name="Reference"></a>Reference

- Message bus - I found an [interesting article](http://www.gamasutra.com/blogs/MichaelKissner/20151027/257369/Writing_a_Game_Engine_from_Scratch__Part_1_Messaging.php "Writing a Game Engine from Scratch - Part 1: Messaging by Michael Kissner") about game engine architecture on Gamasutra. I'm thinking about incorporating a message bus. 
