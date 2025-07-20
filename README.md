# Unreal Engine 5 First Person Shooter Prototype

This is a work-in-progress FPS prototype built using Unreal Engine 5. It follows along with GorkaGames’ tutorial series and focuses on implementing foundational gameplay systems such as character control, AI behavior, weapon handling, and animation using Unreal’s Blueprint system.

## Project Overview

This project recreates core FPS mechanics like player movement, shooting, and enemy AI. It includes basic weapon feedback, AI perception and chase logic, and animation transitions. The implementation is modular and primarily Blueprint-based.

The goal is to understand Unreal Engine’s gameplay framework and AI systems, not to ship a complete game.

## Implemented Features

### Player Systems
- First-person controller with camera smoothing and head bobbing
- Animation blend between arms and body movement
- Weapon attachment via skeletal socket
- Line trace shooting with damage application
- Camera shake and muzzle flash effects
- Basic HUD with crosshair
- Dynamic footstep and gunfire sounds

### Enemy AI
- Behavior Tree and Blackboard-based decision logic
- Patrol and idle state using predefined blueprint paths
- Vision-based player detection
- Chase and melee attack behavior
- Basic health system and ragdoll death on hit

### Technical Systems
- Blueprint-only implementation
- Blend space for movement animation
- Component-based actor setup
- Particle effects for shooting and impact
- Socket-based weapon mounting
- Basic audio variation via Meta Sound

## Tutorial Reference

This project follows the FPS tutorial series by GorkaGames on YouTube:
https://www.youtube.com/watch?v=u30H_7jwjo8

Other minor references include Epic’s documentation and similar community guides.

## Notes

This project is not a complete game. It is a sandbox for learning AI behavior trees, Blueprint scripting, combat logic, and player interaction systems in UE5.

All logic is custom-built but tutorial-driven, and many assets or structural ideas are based on community practices and guides.
