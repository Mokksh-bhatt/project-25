# Paper Toss Simulator

A simple browser-based game where you toss a crumpled paper ball into a dustbin, powered by [p5.js](https://p5js.org/) and [Matter.js](https://brm.io/matter-js/).

## Features

- Realistic physics simulation using Matter.js.
- Interactive controls: press the UP arrow key to launch the paper ball into the dustbin.
- Custom paper and bin sprites for a visually appealing simulation.
- Modular code structure for easy extension and understanding.

## How to Play

1. Open `index.html` in your browser.
2. Press the UP ARROW key to apply a force to the paper and try to throw it into the dustbin.
3. The simulation uses real-world-like gravity, restitution, and friction.

## File Structure

- `index.html`: Entry point for the game.
- `sketch.js`: Main logic, game loop, and rendering.
- `Paper.js`: Paper ball class.
- `Dustbin.js`: Dustbin walls representation (physics).
- `Ground.js`: Ground plane.
- `Images/`: Assets for the paper and dustbin.
- `matter.js`: Physics engine.
- `p5.js`, `p5.dom.min.js`, `p5.play.js`, `p5.sound.min.js`: p5.js libraries for rendering, UI, and sound.

## Setup

No installation required. Just open `index.html` in your browser.

## Screenshot

![Screenshot](Images/example.png) <!-- Put an actual screenshot in Images/ -->

## Credits

- [Matter.js](https://brm.io/matter-js/) for physics
- [p5.js](https://p5js.org/) for graphics

---

**Enjoy tossing papers in a digital bin!**
