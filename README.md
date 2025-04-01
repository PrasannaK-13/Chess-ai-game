# Chess AI Game

A web-based chess game where a human player can play against an AI (powered by a selected LLM like Google Gemini, OpenAI GPT, etc.). This project demonstrates a functional chessboard UI, integration with a backend, and the ability to interact with different AI models for playing chess.

## Features

- **Two-Player Mode**: Human vs Human game mode.
- **AI Opponent**: Play against an AI that uses a selected language model (Google Gemini, OpenAI GPT, etc.) to make moves.
- **Difficulty Levels**: Choose the difficulty level for the AI opponent (Easy, Normal, Hard).
- **Move History**: Track and display the sequence of moves in the game.
- **Game Reset**: Option to reset the game and start fresh.

## Tech Stack

- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS, JavaScript
- **AI Model**: Google Gemini API (or another LLM API of your choice)
- **Chess Library**: `python-chess` for move validation and game state management
- **Threading**: For handling AI moves asynchronously

## Installation

### Prerequisites

1. Python 3.x installed on your system.
2. Install the following Python libraries:
    - Flask
    - python-chess
    - (Other libraries as needed)

### Step 1: Clone the Repository

Clone the repository to your local machine:

(
git clone https://github.com/yourusername/chess-ai-game.git
)

### Step 2: Install Dependencies
Navigate to the project folder and install the necessary dependencies:

(
pip install -r requirements.txt
)

### Step 3: Running the App
Start the Flask server by running the following command:

(
python app.py
)

This will launch the application at http://127.0.0.1:5000/. You can access it from your browser.

### Step 4: Set Your Google Gemini API Key
You need a valid API key for Google Gemini (or any other selected LLM API) to interact with the AI. Enter the API key in the frontend interface when prompted.

### Step 5: Enjoy the Game
Once the game is running, you can:
-Select the LLM (Google Gemini or another LLM).
-Choose the difficulty level (Easy, Normal, Hard).
-Start a new game and make moves.
-Track the move history.

## Game Flow
->Start Game: The player starts a new game, selects the LLM (AI opponent), and sets the difficulty level.
->Make Moves: The player makes moves via the frontend, and the backend validates them.
->AI Move: After each player move, the AI makes a move based on the selected difficulty and LLM.
->End Game: The game continues until a checkmate, stalemate, or draw is reached. The history of all moves is available.

##Files
- app.py: The backend code for managing the chess game logic and AI moves.
- index.html: The frontend UI for interacting with the game.
- chess_notebook.ipynb: A Jupyter notebook demonstrating how the AI makes moves (optional for reference).
- chessBlack.jpeg: Background image used in the frontend UI.

#Contributions
Feel free to fork the project and submit pull requests with improvements, new features, or bug fixes.

#License
This project is licensed under the MIT License.

#Steps to Add the README File:
-Create the README.md
In the root directory of your project (where the app.py, index.html, etc., are located), create a new file named README.md.

-Copy the Above Content
Paste the content above into the README.md file.

-Push to GitHub
If you haven't already added the README file to your GitHub repository, use these commands:
(
git add README.md
git commit -m "Added README file"
git push origin master
)
