# Sand Simulation

This project implements a simple sand simulation using p5.js. The simulation allows you to interact with the sand particles, creating patterns and observing their behavior as they respond to gravity.

## Features

- **Sand Creation**: Click and drag the mouse to create areas of sand particles on the canvas.
- **Color Variation**: The color of the sand particles changes over time, creating a visually dynamic simulation.
- **Gravity Effect**: Sand particles respond to gravity, simulating a realistic flow and settling behavior.

## Usage

1. Open the `index.html` file in a web browser to view the simulation.
2. Click and drag the mouse to interact with the sand particles.
3. Observe the gravity effect and color variation over time.

## Code Overview

The code is written in JavaScript using the p5.js library. It consists of a 2D array implementation for handling the grid of sand particles. The `make2DArray` function is used to create the initial grid.

The simulation updates in the `draw` function, where the sand particles respond to gravity and interact with the mouse input.

## Dependencies

- [p5.js](https://p5js.org/): A JavaScript library for creative coding.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to experiment with the code and adapt it to your own projects! If you have any questions or suggestions, please create an issue or pull request.
