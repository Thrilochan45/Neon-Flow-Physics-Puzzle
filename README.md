# Neon-Flow-Physics-Puzzle
A minimalist, physics-based puzzle game built with HTML5 Canvas and Vanilla JavaScript. Draw lines to guide the glowing ball to the goal while managing ink levels and avoiding obstacles.
# 🌌 Neon Flow: Physics Puzzle

**Neon Flow** is an interactive, physics-based puzzle game set in a vibrant cyberpunk universe. Players must use logic and creativity to draw paths, guiding a gravity affected ball through complex levels filled with obstacles, spikes and portals.

## ✨ Features

-   **Dynamic Drawing Mechanic**: Draw custom lines to create ramps, bridges, and walls.
-   **Physics Engine**: Custom-built vector-based physics system handling gravity, velocity, collision detection and friction.
-   **Resource Management**: limited "Ink" supply challenges players to be efficient with their solutions.
-   **Neon Aesthetic**: Glowing visuals, particle effects, and a dark mode interface using HTML5 Canvas.
-   **Responsive Design**: Fully playable on both Desktop (Mouse) and Mobile (Touch).
-   **Audio Synthesis**: Procedural sound effects generated in real-time using the Web Audio API.

## 🛠️ Technologies Used

-   **Core**: HTML5, JavaScript (ES6+)
-   **Rendering**: HTML5 Canvas API
-   **Styling**: CSS3, Tailwind CSS (via CDN)
-   **Icons**: FontAwesome
-   **Fonts**: Google Fonts (Orbitron, Rajdhani)

## 🚀 How to Run

No build step or server is required! This game is contained entirely within a single file for portability.

1.  **Clone the repository:**
    ```
    git clone [https://github.com/Thrilochan45/Neon-Flow-Physics-Puzzle.git](https://github.com/Thrilochan45/Neon-Flow-Physics-Puzzle.git)
    ```
2.  **Open the game:**
    Simply open the `index.html` file in any modern web browser.

## 🕹️ Controls

| Action | Input (Desktop) | Input (Mobile) |
| :--- | :--- | :--- |
| **Draw Line** | Left Click + Drag | Touch + Drag |
| **Start/Reset** | Click "DROP BALL" | Tap "DROP BALL" |
| **Clear Lines** | Click "Clear Lines" | Tap "Clear Lines" |

## 🧩 Level Design

 The game currently features a progressive level system defined in the `levels` array within the code. Each level supports:
* Start/Goal positions
* Static Obstacles (Walls & Spikes)
* Collectable Stars
* Custom Ink Limits

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
