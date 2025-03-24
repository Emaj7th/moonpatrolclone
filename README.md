# moonpatrolclone
 
<h1 align="center">Moon Patrol Clone</h1>

  <p align="center">
    A Moon Patrol clone created using the Phaser framework and Claude AI.
    <br />
     <a href="https://github.com/emaj7th/moonpatrolclone">github.com/emaj7th/moonpatrolclone</a>
  </p>
</div>

 
## Table of Contents

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#key-features">Key Features</a></li>
      </ul>
    </li>
    <li><a href="#architecture">Architecture</a></li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About The Project

This project is a clone of the classic arcade game Moon Patrol, developed using the Phaser 3 framework. The game features a side-scrolling environment where the player controls a vehicle, navigating through varied terrain, shooting obstacles, and avoiding hazards. The game incorporates procedurally generated terrain, UFO enemies, and a scoring system.

### Key Features

- **Side-scrolling gameplay:** Experience classic Moon Patrol-style action.
- **Procedurally generated terrain:** The ground, mountains, and cityscapes are dynamically generated.
- **UFO enemies:** Engage with enemy UFOs that shoot projectiles.
- **Vehicle controls:** Jump and shoot to avoid obstacles and defeat enemies.
- **Score and lives:** Track your score and remaining lives.
- **Mobile and Keyboard Controls:** Playable on both desktop and mobile devices.
- **Sound Effects:** Includes background music, explosions, and weapon sounds.

## Architecture

The game is built using the Phaser 3 JavaScript framework. The core logic resides within the `GameScene` class in `index.html`.

- **Phaser 3:** Used for game development, rendering, and input handling.
- **HTML/CSS:** Provides the structure and styling for the game page.
- **JavaScript:** Implements the game logic, including object creation, movement, collision detection, and scoring.
- **Sound Files:** MP3 files are used for background music and sound effects.

The game elements are drawn using Phaser's graphics objects, including:

-   `this.backgroundMountains`
-   `this.backgroundCity`
-   `this.ground`
-   `this.vehicle`
-   `this.bulletsGraphics`
-   `this.rocksGraphics`
-   `this.explosionsGraphics`
-   `this.ufosGraphics`
-   `this.ufoProjectilesGraphics`

## Getting Started

To play the game locally, follow these steps:

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, etc.)
- A local web server (optional, but recommended for sound to work correctly)

### Installation

1.  **Clone the repository:**

    ```sh
    git clone https://github.com/emaj7th/moonpatrolclone.git
    ```
2.  **Navigate to the project directory:**

    ```sh
    cd moonpatrolclone
    ```
3.  **Open `index.html` in your web browser:**

    -   You can directly open the `index.html` file in your browser, but some browsers may restrict the loading of local audio files due to security reasons.
    -   For the best experience, use a local web server. Python provides a simple way to do this:

        ```sh
        python -m http.server
        ```

        Then, navigate to `http://localhost:8000` in your browser.

## Acknowledgments

- This README was created using [gitreadme.dev](https://gitreadme.dev) — an AI tool that looks at your entire codebase to instantly generate high-quality README files.
- This game was created with the help of Claude AI.
