<img src=Portfolio.png></img>


# My Portfolio Website

## Overview

This simple portfolio site is designed as an interactive 2D game, leveraging HTML and CSS for its interactive elements and Kaboom.js for the gaming aspects. The project is bootstrapped using Vite, a modern front-end build tool that optimizes JavaScript for the browser.

## Technologies Used

- **HTML & CSS**: For structuring and styling the interactive elements of the page.
- **Kaboom.js**: A lightweight, easy-to-use library for creating 2D games in the browser.
- **Vite**: A build tool that provides fast development server and optimized builds for production.
- **Tiled**: A level editor tool used for creating the room that you move around.

## Project Setup

### Prerequisites

Ensure you have Node.js installed on your system. You can download it from [Node.js official website](https://nodejs.org).

### Installation

1. Clone this repository to your local machine.
``` bash
git clone https://github.com/BRArjun/MyPortfolio_WebDev.git
```
2. Move into the directory
``` bash
cd MyPortfolio_WebDev
```
3. Install dependencies
``` bash
npm install
```
4. Run the developmental build
```bash
npm run dev
```

## Configuration

### Vite Configuration

The `vite.config.js` file specifies the base directory of the project, enabling hosting services to locate the root directory correctly. It uses Terser for minification instead of the default ESBuild due to compatibility issues with Kaboom.js.

### Kaboom.js Usage

Kaboom.js utilizes a sprite sheet for efficient rendering. Instead of drawing tiles individually (which is more performance-intensive), we use a tile editor to create levels and export them as images. This approach 'bakes' the tiles, optimizing performance.

Animations are managed through the `anims` parameter, where you define the sprite numbers for different animations. These animations loop through individual sprites based on the specified range and speed, controlling the frames per second (fps) of the animation.

See the [documentation](https://kaboomjs.com/doc/intro) for more details.
## License

This project is licensed under the MIT License.

