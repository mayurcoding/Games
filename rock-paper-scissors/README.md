# Rock Paper Scissors Game

## Detailed Theory

The **Rock Paper Scissors** game is a classic example of a zero-sum, non-transitive game in game theory. In this context, "zero-sum" means that one player's gain is exactly balanced by the other player's loss. "Non-transitive" refers to the fact that no single choice is superior to the others; each option can be beaten by another in a cyclical manner.

### Game Theory Perspective

- **Players:** Two participants (in this project, the user and the computer).
- **Strategies:** Each player simultaneously chooses one of three possible moves: Rock, Paper, or Scissors.
- **Payoff Matrix:** The outcome is determined by the combination of choices:
    - Rock beats Scissors (Rock wins)
    - Scissors beats Paper (Scissors wins)
    - Paper beats Rock (Paper wins)
    - Identical choices result in a tie

This cyclical dominance ensures that no strategy is always superior, encouraging unpredictability and fairness.

### Randomness and Fairness

In this implementation, the computer's choice is generated randomly, simulating an unbiased opponent. This randomness is crucial for fairness, as it prevents the user from predicting the computer's moves and ensures each round is independent.

### User Interaction and Feedback

The game provides immediate feedback after each round, displaying both choices and the result. This real-time interaction helps users understand the rules and outcomes, reinforcing the cyclical nature of the game.

### Educational Value

This project demonstrates several key programming and theoretical concepts:
- **Conditional Logic:** Determining the winner based on user and computer choices.
- **Random Number Generation:** Simulating the computer's unpredictable moves.
- **State Management:** Tracking and updating scores.
- **User Interface Design:** Presenting information clearly and interactively.

### Applications

Beyond entertainment, Rock Paper Scissors is often used in decision-making, probability studies, and as an introductory example in computer science and game theory due to its simple yet rich structure.

