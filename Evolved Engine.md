
# Evolved Engine

## Overview

- **Purpose**: 2.5D slider multiplayer engine
- **Target Audience**: Indie devs focused on the specific game genre stated above
- **Key Objectives**: Windows, low-level language, Hack-and-Slash specific, light-weight, coding-heavy, intense-documentation

# Core Features

## Rendering (Edgar)

*Graphics APIs, shader support, lighting models, post-processing effects.*
- **Graphics APIs**: OpenGL
- **Shader support**: No shaders supported, must use personal sprites or tiles
- **Animation Support**: Allow frame-based animation using sprites
- **Lighting models**: No actual lighting handled, fully managed by sprites/tiles
- **Post-processing effects**: None for now, unless ideas come up
- **Special Effects:**
	- **Particle Effect**: Particle effect system very important for game
	- **parallax scrolling**: Multiple background layers
- **Text Rendering:** Must have for game like this
- **Window & Viewport Management:** Movable windows and stuff

## Physics (David)

*100% needed in order for it combine components together*
- **Collision detection**: of course, items, characters, walls, etc…
- **physics engine**: Gravity, momentum
- **rigidbody/dynamics systems**: immovable vs. movable
- **third-party library integration**: Mix of personal code and libraries

## Audio (David)

- **Sound Playback**: Sounds, hits, music
- **Audio Resource Management**: libraries or APIs
	- handles volume, pitch, and channel management

## Input Handling (David)

- **Device support**: Keyboard, gamepad, etc…
- **Event-Driven Systems**: User presses button, button does
	- **Event Processing**: Button does event

## Scripting (Edgar)

- **coding-heavy**: Most of the engine is handled through coding, with minimal UI elements
- **Low-level Language**: Similar to Java or C#, syntax handled with brackets and semi-colons

## AI (TBD)

- **Enemy pathing and decision-making** will be handled by the game dev, and not in the game engine

## Networking (Edgar)

- **Multiplayer architecture**: client-server for co-op
	- synchronization
	- latency compensation
