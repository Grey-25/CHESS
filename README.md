<img width="837" alt="Screenshot 2025-05-05 at 1 23 17 AM" src="https://github.com/user-attachments/assets/e4d4c1da-e68d-4abf-82b1-0a297ecebd8e" />
<img width="836" alt="Screenshot 2025-05-05 at 1 23 00 AM" src="https://github.com/user-attachments/assets/7e9245d9-2b32-4438-a0c1-ea1cbf20a69f" />
CHESS -custom chess game 

## Overview

This project is a local two-player chess game implemented digitally using **JavaScript**. It allows two individuals to play a standard game of chess on the same computer. Additionally, the application provides functionality for up to five other users to spectate the ongoing match in real-time.

## Features

* **Local Two-Player Gameplay:** Enables two users to play a complete game of chess with standard rules.
* **Intuitive Interface:** Provides a user-friendly graphical interface built with web technologies for easy interaction with the chessboard and pieces.
* **Valid Move Enforcement:** The application enforces the rules of chess, ensuring that only legal moves can be made.
* **Special Moves Support:** Implements special chess moves such as castling, en passant, and pawn promotion.
* **Check and Checkmate Detection:** The game automatically detects check and checkmate situations, ending the game appropriately.
* **Spectator Mode (Up to 5):** Allows up to five additional users to connect (likely through a web browser on the same local network) and observe the ongoing game without interfering with the players.
* **Real-time Updates:** Spectators see the board update in real-time as players make their moves, likely using technologies like WebSockets or Server-Sent Events.

## Technologies Used

* **JavaScript:** The primary programming language for game logic and front-end interactions.
* **HTML:** Used for structuring the web page and the game interface.
* **CSS:** Used for styling the visual presentation of the chessboard and pieces.
* **Potentially:**
    * **WebSockets or Server-Sent Events (SSE):** For real-time communication to update spectator views.
    * **A JavaScript framework/library (e.g., React, Vue, Angular):** To structure the user interface and manage application state (if the project is more complex).

## Installation

Since this project utilizes web technologies, the installation process is likely straightforward:

1.  **Download the Project:** Obtain the project files (e.g., by cloning the repository or downloading a zip file).
2.  **Open `index.html`:** Navigate to the project directory in your file explorer and open the `index.html` file in your web browser. This should launch the game for the players.

    * **For Spectators:** There might be a separate HTML file or a specific URL (e.g., `spectate.html` or a URL with a game ID parameter) that spectators need to open in their web browser on the same local network. Instructions for spectators should be provided separately if this is the case.

## How to Run the Game

1.  **Players:** Open the `index.html` file in a web browser. Two players can then interact with the game on this single browser window.
2.  **Spectators:**
    * If there's a specific `spectate.html` file, open it in up to five other web browsers on the same local network.
    * Alternatively, there might be instructions within the game interface for how spectators can join (e.g., a link or a specific action to take).

## Usage

1.  **Launching the Game:** Open the `index.html` file in a web browser.
2.  **Playing:**
    * Two players can interact with the chessboard elements directly within the web page (e.g., by dragging and dropping pieces or clicking to select and move).
    * Players take turns making their moves.
    * The game logic implemented in JavaScript will enforce the rules and detect the end of the game.
3.  **Spectating:**
    * Spectators should open the designated spectator page (if separate) in their web browser.
    * The spectator view will update automatically in real-time as the players make their moves on the main game interface.

## Future Enhancements (Optional)

* Implement an AI opponent for single-player mode.
* Add online multiplayer functionality using more advanced web technologies and backend services.
* Include features like move history, undo/redo, or saving/loading games using local storage or a backend.
* Enhance the user interface and visual design using more advanced CSS or JavaScript libraries.
* Implement different time controls for games.

## Contributing

[Optional: If you want others to contribute, add information about how they can do so (e.g., reporting issues, submitting pull requests).]

## License

[Optional: Specify the license under which the project is distributed.]

## Acknowledgements



