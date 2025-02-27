# Snake and Ladder Game in Java

## Introduction

This is a simple **Snake and Ladder** game implemented in Java for two players. The game follows the classic rules where players roll a dice to advance their positions on the board. If a player lands on a ladder, they climb up, and if they land on a snake, they slide down. The first player to reach **100** wins!

## How to Play

1. Run the program in a Java-supported environment.
2. Enter the names of both players when prompted.
3. Players take turns rolling the dice by pressing **Enter**.
4. The dice roll determines how many steps a player moves forward.
5. Landing on a **ladder** moves the player **up**.
6. Landing on a **snake** moves the player **down**.
7. The first player to reach **100** wins the game!

## Features

- Two-player turn-based gameplay.
- Randomized dice roll (values from 1 to 6).
- Ladders and snakes implemented based on predefined positions.
- Players cannot exceed **100**, and excess rolls are ignored.
- Simple command-line interface.

## Requirements

- Java Development Kit (JDK) installed (JDK 8 or later recommended).

## How to Run

1. Clone this repository or download the `snake2.java` file.
2. Open a terminal or command prompt.
3. Navigate to the folder containing the file.
4. Compile the program using:
   ```sh
   javac snake2.java
   ```
5. Run the program using:
   ```sh
   java snake2
   ```

## Example Gameplay

```
Enter 1st player name: Prabhat
Enter 2nd player name: mohit

Current Positions:
Prabhat: 0
Mohit: 0

Prabhat's turn. Press Enter to roll the dice...
Prabhat rolled: 5
Prabhat moves to position 5.

Mohit's turn. Press Enter to roll the dice...
Mohit rolled: 3
Mohit moves to position 22 (Ladder found!).

...

🎉 Mohit wins the game! 🎉
```

## Contributing

Feel free to fork this project and enhance it with features like:

- Adding a graphical user interface (GUI).
- Multiplayer mode.
- Saving and loading game progress.

## License

This project is open-source and free to use.
