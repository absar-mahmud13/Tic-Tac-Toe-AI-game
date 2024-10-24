 #   🎮 Tic-Tac-Toe AI Game

Welcome to the Tic-Tac-Toe AI Game! This implementation utilizes the Minimax algorithm to allow for a challenging gameplay experience against an AI opponent. The game is built using Python's `pygame` library, providing a graphical interface for an engaging user experience.

##🚀 Features

- **AI Opponent**: The AI plays as "O" and uses the Minimax algorithm to make optimal moves.
- **Two Player Options**: Choose to play as either "X" or "O".
- **Graphical Interface**: Enjoy a smooth and interactive gameplay experience.

## Key Concepts

###🧠 Minimax Algorithm
The Minimax algorithm is a decision-making tool used in two-player games, where one player's gain is another's loss. In this game:
- **Maximizer (X)**: Aims to maximize their score (winning).
- **Minimizer (O)**: Aims to minimize the opponent's score (forcing them into losing positions).

### Game States
The game can end in three possible states:
- **Win for X**: Score = 1
- **Win for O**: Score = -1
- **Tie**: Score = 0

### Decision-Making Process
The AI evaluates all possible moves using the following functions:
- **Max_Value**: Evaluates potential moves for the Maximizer (X) to maximize their score.
- **Min_Value**: Evaluates potential moves for the Minimizer (O) to minimize the opponent's score.

## Game Flow

1. **Start the Game**: Choose your player (X or O).
2. **Player's Turn**: Make your move by clicking on the board.
3. **AI's Move**: The AI calculates its optimal move using the Minimax algorithm.
4. **Game Outcome**: The game continues until there’s a win or a tie.

##📦 How to Run

1. Ensure you have Python and the `pygame` library installed. You can install `pygame` using:
   
   pip install pygame


3. Download the game files from the repository.

4. Run the game:
   
   python tic_tac_toe.py

## Output: ##

   ![1](https://github.com/user-attachments/assets/de53ce20-5ae0-42ad-9a06-4b56957d1410)
   
   ![2](https://github.com/user-attachments/assets/8109b447-617d-4013-9134-d052136f11fa)
   
   ![3](https://github.com/user-attachments/assets/45f1c34e-670d-4ff8-90ef-4ef62cbad581)




## Summary

This Tic-Tac-Toe AI Game provides an excellent opportunity to challenge yourself against a well-optimized AI. The Minimax algorithm ensures that the AI makes the best possible moves, resulting in an engaging and competitive experience. Enjoy playing and may the best player win!

##📝 License

This project is licensed under the MIT License. Feel free to modify and share!

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes. Your contributions are welcome!
