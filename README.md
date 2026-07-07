# Rock Paper Scissors Game

## Overview

This is a simple **Rock, Paper, Scissors** game written in Java. The program allows a user to play one round against the computer. The computer randomly selects Rock, Paper, or Scissors, and the program determines the winner based on the standard game rules.

## Features

* Accepts user input from the keyboard.
* Validates user input.
* Generates a random computer choice.
* Determines the winner according to the game rules.
* Displays the game result.

## Technologies Used

* Java
* `Scanner` for user input
* `Random` for generating the computer's move

## How to Run

1. Clone or download this project.
2. Open the project in your preferred Java IDE (such as Eclipse, IntelliJ IDEA, or VS Code).
3. Compile and run the `RockPaperScissorsGame.java` file.
4. Enter one of the following numbers when prompted:

| Number | Choice   |
| ------ | -------- |
| 0      | Rock     |
| 1      | Paper    |
| 2      | Scissors |

## Example Output

```text
Welcome to the Rock, Paper, Scissor Game!

Enter your choice
0: Rock, 1: Paper, 2: Scissors
1

Computer chose: 0

You win! - Congratulations
```

## Game Rules

* Rock beats Scissors.
* Scissors beats Paper.
* Paper beats Rock.
* If both the player and the computer choose the same option, the game ends in a tie.

## Project Structure

```text
day4/
└── RockPaperScissorsGame.java
```

## Possible Improvements

* Display the words "Rock", "Paper", and "Scissors" instead of numbers.
* Allow the player to play multiple rounds.
* Keep track of wins, losses, and ties.
* Add input validation that continues prompting until a valid choice is entered.
* Create separate methods to improve code organization.
* Add a graphical user interface (GUI).

## Author

Created as a Java practice project to demonstrate:

* User input
* Conditional statements
* Random number generation
* Basic game logic

One small note about your code: there's a syntax error in the invalid-input message. This line:

```java
System.out.println("Invalid choice. Please run the program again and enter 0, 1 or 2.);");
```

should be:

```java
System.out.println("Invalid choice. Please run the program again and enter 0, 1, or 2.");

