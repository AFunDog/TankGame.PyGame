

# TankGame

## 📄 Introduction

![](https://img.shields.io/badge/Python%203.12.7-3776AB?style=for-the-badge&logo=python&logoColor=white)

Uses the following `Python` libraries:
- `pygame`
- `pymunk`
- `loguru`

Online multiplayer turned out to be quite unstable, so I've learned an important lesson: Python isn't really suitable for game development. Moving forward, I'll stick to C# and the Godot engine for making games, and stop reinventing the wheel.

## Controls

**Main Player**

- `WASD` to move

- `G` to shoot

**Secondary Player**

- `Arrow Keys` to move

- `[0]` to shoot

## Game Power-Ups

- ### Ghost Weapon Power-Up

    Ghost weapon: bullets pass through walls and accelerate during flight.

- ### Remote-Controlled Missile Power-Up

    Launches a remote-controlled missile. After firing, the tank cannot move; instead, the missile is controlled. Fire again to cancel.

- ### Fragmentation Shell Weapon Power-Up

    Fires fragmentation shells that explode upon hitting a target or after a set time. Any tanks within the blast radius are instantly destroyed.
