# Survivor Sprint 🎮

A thrilling 3D competitive game built with Three.js where two players must survive as long as possible while dodging incoming obstacles. The last player standing wins!

## Project Information
- **Course**: Minor Project (6th Semester)
- **Program**: B.Tech in Computer Science and Engineering
- **Institution**: Kalinga Institute of Industrial Technology

## Team Members
- Abhik Samanta (22052610)
- Bhaswar Chowdhury (22052549)
- Agnibho Saha (22052527)
- Aditya Ranjan Sinha (22052699)
- Devjit Mondal (22052550)

## Features 🌟

- Smooth 3D graphics powered by Three.js
- Two-player competitive gameplay
- Dynamic obstacle spawning with increasing difficulty
- Survival time tracking
- Player-to-player collisions with physics
- Responsive camera that follows both players
- Background music with toggle option
- Modern UI with responsive design
- Shadow and lighting effects
- Game over screen with winner announcement and restart functionality

## Controls 🎮
- **Player 1 (Blue)**:
  - **A**: Move left
  - **D**: Move right
- **Player 2 (Red)**:
  - **←**: Move left
  - **→**: Move right
- **R**: Restart game (when game over)
- **Any key**: Start game (from start screen)

## Technical Features 💻

### Graphics and Rendering
- Three.js for 3D rendering
- Perspective camera that dynamically adjusts to follow both players
- Soft shadow mapping
- Ambient and directional lighting
- Grid helper for visual reference
- Anti-aliasing enabled

### Game Mechanics
- Object-oriented game object system
- Multiple collision detection systems (box-to-box and sphere-to-sphere)
- Player-to-player collision physics
- Dynamic difficulty scaling with increased obstacle speed over time
- Survival time system
- Gravity and physics simulation
- Responsive window resizing

### UI Elements
- Survival time display
- Player control instructions
- Game start overlay
- Sound toggle controls
- Game over screen with winner announcement
- Modern, minimalist design with blur effects and backdrop filters
- Responsive layout

## Technologies Used 🛠️

- HTML5
- CSS3
- JavaScript (ES6+)
- Three.js
- ES Module Shims
- Web Audio API

## Game Objects

### Players
- Two spherical characters (Blue and Red) with physics-based movement
- Shadow casting
- Collision detection between players
- Smooth movement controls

### Obstacles
- Randomly generated with varying positions and colors
- Increasing speed based on survival time
- Physics-based movement with acceleration
- Collision detection with players

### Environment
- Large ground plane with shadow receiving
- Grid helper for spatial reference
- Ambient and directional lighting
- Responsive camera system that adjusts to keep both players in view

## Game Rules

1. Both players start on opposite sides of the track
2. Control your player to avoid incoming obstacles
3. Players can collide with each other, potentially pushing opponents into dangers
4. The last player standing wins!
5. A player is eliminated by:
   - Falling off the track
   - Colliding with an obstacle

## Performance Features ⚡

- Efficient rendering with Three.js
- Optimized collision detection
- Hardware-accelerated rendering
- Smooth animation frame handling

## Future Improvements 🔮

- High score system
- Multiple character options
- Power-ups and special abilities
- Mobile touch controls
- Multiple difficulty levels
- Visual effects and particles
- Additional sound effects for actions

## Credits 🙏

Special thanks to:
- Three.js community for the 3D graphics library
- Our project mentor, Ajay Anand Sir
- Friends for testing and feedback

## License

This project is created as an educational project for KIIT University.

---
© 2025 Survivor Sprint Team. All Rights Reserved.