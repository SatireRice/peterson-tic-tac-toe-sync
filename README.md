# peterson-tic-tac-toe-sync
This GitHub repository hosts an implementation of Peterson's Algorithm for mutual exclusion in a concurrent Tic Tac Toe game simulation. The project demonstrates the practical application of synchronization techniques in operating systems through a terminal-based interface. The implementation ensures thread safety and prevents race conditions, allowing users to interactively observe how mutual exclusion guarantees data integrity in multi-threaded environments.
# Table of Contents
- [peterson-tic-tac-toe-sync](#peterson-tic-tac-toe-sync)
    - [Getting Started](#getting-started)
    - [Usage](#usage)
    - [Contributing](#contributing)
    - [License](#license)
- [Project Overview](#project-overview)
    - [Objectives](#objectives)
    - [Methodology](#methodology)
- [How the game will work](#how-the-game-will-work)

### Getting Started
To get started with the Peterson's Tic Tac Toe Sync project, follow these steps:
1. Clone the repository to your local machine:
        ```
        git clone https://github.com/satirerice/peterson-tic-tac-toe-sync.git
        ```
2. Navigate to the project directory:
        ```
        cd peterson-tic-tac-toe-sync
        ```
3. Install the necessary dependencies:
        ```
        npm install
        ```
4. Run the application:
        ```
        npm start
        ```

### Usage
Once the application is running, you can interact with the Tic Tac Toe game through the terminal interface. Follow the on-screen instructions to make your moves and play against another player.

### Contributing
Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

### License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Project Overview
The project focuses on implementing Peterson's Algorithm to manage access to shared resources within a Tic Tac Toe game simulation. The demonstration will run through a terminal interface, showcasing how synchronization mechanisms prevent race conditions and ensure thread safety in multi-threaded environments.

### Objectives
1. To provide a clear and interactive demonstration of Peterson's Algorithm in action.
2. Applying the synchronization concept to a real-world scenario, a tic tac toe game.
3. To present the project through terminal interactions, emphasizing simplicity and accessibility.

### Methodology
- Algorithm Implementation
        - Code Peterson's Algorithm in a suitable programming language (e.g., Python).
- Terminal Interface
        - Develop a user-friendly command-line interface (CLI) for the Tic Tac Toe game.
- Concurrency Simulation
        - Simulate concurrent access to the game state using multiple threads, demonstrating mutual exclusion and synchronization.
- Interactive demonstration
        - Users can observe and interact directly with the algorithm's behavior through terminal commands.

### How the game will work
- Scenario: Players engaging in a game of Tic Tac Toe.
- Shared Resource: Game board state (e.g., current player turn, cell occupancy).
- Implementation: Utilize Peterson's Algorithm to ensure that only one player can make a move at a time, maintaining game integrity and avoiding conflicts.