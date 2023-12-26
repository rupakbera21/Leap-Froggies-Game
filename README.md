# Frog Leap Puzzle Game
https://github.com/rupakbera21/rupakbera21/assets/154492310/93d3fd98-281f-4837-9a84-c84a08781c95

## Description

The Frog Leap Puzzle Game is a simple console-based game where the player needs to swap the positions of two sets of frogs to win the game. The left set of frogs can only move to the right, and the right set of frogs can only move to the left. Frogs can move one space forward or jump two spaces by leaping over another frog from the opposite side.


## Features

- Simple console-based gameplay.
- Intuitive rules and user-friendly interface.
- Dynamic display of the game board.
- Winning condition checks for an engaging experience.


## How to Play

1. **Initial Display:**
   The game starts with an initial display of frogs on the left ('G') and right ('B') sides, with an empty space denoted by '-':

   ```
   [ 0 ,  1 ,  2 ,  3 ,  4 ,  5 ,  6 ]
   ['G', 'G', 'G', '-', 'B', 'B', 'B']
   ```

2. **Making Moves:**
   - Enter the position of the frog you want to move.
   - The game will display the updated board after each move.

3. **Rules:**
   - The entered position should be between 0 to 6 or 'q' to quit the game.
   - The selected position cannot be the position of the empty space ('-').
   - Frogs can move one space forward or leap two spaces over another frog from the opposite side.

4. **Winning the Game:**

     The puzzle is solved when the two sets of frogs have switched positions:
   
   ```
   [ 0 ,  1 ,  2 ,  3 ,  4 ,  5 ,  6 ]
   ['B', 'B', 'B', '-', 'G', 'G', 'G']
   ```

## How to Run the Game

1. **Requirements:**
   - Python installed on your system.

2. **Installation:**
   Clone this repository to your local machine:

3. **Running the Game:**
   Open a terminal, navigate to the project directory, and run the game script:

   ```bash
   python Frog_Leap_Problem_Statement_solved.py
   ```

   OR

   Click on "Play Game" to redirect to the Colab notebook: 
   [Play Game](https://colab.research.google.com/drive/1_x7UUrJ1OK_mDyUNRlQA165C90W8mmKr?usp=sharing)

5. Follow the on-screen instructions to play the game.


## Contributions

Feel free to contribute to the game by opening issues or submitting pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Special thanks to [PrepInsta](https://prepinstaprime.com/) and our Mentor [Rushikesh](https://github.com/rishikonapure) for inspiration.

Enjoy playing the Frog Leap Puzzle Game!




