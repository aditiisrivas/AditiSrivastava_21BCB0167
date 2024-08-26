# ChessLikeGame

This project is a browser-based, chess-like game developed using Node.js, Express, and Socket.io. It provides an engaging introduction to real-time web applications and game development, featuring server-side game logic and a simple yet functional front-end.

# Overview
In this two-player game, users take turns moving their pieces on a grid similar to a chessboard. The objective is to outmaneuver the opponent using strategic moves, similar to the mechanics of chess. The game showcases real-time interactions between players, powered by Socket.io, allowing for synchronous gameplay and seamless user experience.

# Key Features
Real-Time Gameplay:

The game leverages Socket.io for real-time communication, ensuring that every move made by a player is instantly reflected on both screens, providing an immersive and responsive gameplay experience.
# Server-Side Game Logic:

All game logic, including move validation, turn management, and game state updates, is handled on the server using Node.js and Express. This setup ensures that the rules of the game are consistently enforced across both players.
Chess-Like Mechanics:

The game features a grid-based board reminiscent of a chessboard. Players control pieces with unique movement patterns, adding depth and strategy to the game.

# Turn-Based Strategy:

Players alternate turns, with the server ensuring that moves are validated and that the game state is updated accurately. This turn-based system emphasizes strategic thinking, as players must anticipate their opponent's moves.
 
# Scalable and Extensible:

The codebase is designed to be easily extensible, allowing for the addition of new features like different piece types, custom board sizes, or advanced game rules.

# Technology Stack
Node.js: Handles server-side logic, game state management, and real-time updates.
Express: Manages routes and serves front-end files.
Socket.io: Facilitates real-time, bidirectional communication between the server and clients.
HTML/CSS/JavaScript: Implements the front-end, providing the chessboard interface and managing user interactions.

# How It Works
# Server Setup:

The server is set up with Express to serve static files and manage Socket.io connections. It processes moves, updates the game state, and broadcasts updates to both players.
Real-Time Interaction:

Each player’s move is sent to the server via Socket.io, which then validates the move based on the game’s rules, updates the game state, and sends the updated state back to both players.
Game Logic:

The game logic is implemented server-side, ensuring that rules are enforced and that the game state remains consistent. This includes handling special moves, piece capture, and win conditions.
Front-End Interface:

The front-end features a grid-based board similar to a chessboard, where players can select and move pieces. The interface is updated in real-time to reflect the current state of the game.

## Getting Started

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. Clone the repository:

    ```bash
    git clone  https://github.com/aditiisrivas/AditiSrivastava_21BCB0167.git
    ```

2. Navigate into the project directory:

    ```bash
    cd ChessLikeGame
    ```

3. Install the dependencies:

    ```bash
    npm install
    ```

### Running the Application

1. Start the server:

    ```bash
    node server.js
    ```

2. Open your web browser and go to:

    ```
    http://localhost:3000
    ```


# Future Enhancements
Advanced AI: Implement AI opponents with different difficulty levels for single-player mode.
Multiplayer Support: Extend the game to support multiple simultaneous matches.
Custom Game Rules: Allow users to create and play with custom rules and board setups.