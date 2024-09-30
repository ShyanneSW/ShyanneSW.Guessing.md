# ShyanneSW.Guessing.md
# Title: Guessing Game
```Mermaid
flowchart TD
    A[Guess A Number Between 1-50 ] --> B{User Guess}
    B -- Too Low --> C[Guess Again] --> G
    C --> D[Incorrect Again... You Lose!]
    B -- Too High --> E[Guess Again] -->D
    E --> G[Correct!]
```
# Game How - To
Once you have deciced that you want to enter the program and play the game, the program will think of a number from 1-50. You type in your answer, trying to guess the correct number. The program will give you hints if your guess is either too high or too low. You then will have another chance to guess the number. If your second choice is also incorrect, you lose the game!