# Notes

Let's play! You have to return which player won! In case of a draw return Draw!.

Examples(Input1, Input2 --> Output):
"scissors", "paper" --> "Player 1 won!"
"scissors", "rock" --> "Player 2 won!"
"paper", "paper" --> "Draw!"

# Domains

- Score
    - scissors > paper
    - rock > scissors
    - papel > rock

- GAME
    - 2 inputs with players options
    - 1 output with the winner player

**Label**  
✅ done 🚧 WIP ❌ ERROR

TODO:

# Pomodoro 1 🍅:
- initial setup:
    - update README ✅
    - update NOTES ✅

- TDD:
    - Create the first test: " Should return 'Draw!' " ✅
    - Resolve the first test ✅
    - Commit ✅

    - create the second test: "Should return 'Player 1 won!' when only the player 1 send scissors" ✅
    - Resolve the second test ✅
    - Commit ✅

# Pomodoro 2 🍅:
- TDD
    - create the third test: "Should return 'Player 1 won!' when only the player 1 send paper" ✅
    - Resolve the third test ✅
    - Commit ✅

    - create the fourth test: "Should return 'Player 1 won!' when only the player 1 send rock" ✅
    - Resolve the fourth test ✅
    - Commit ✅

    - create the fifth test: "Should return 'Player 1 won!' when only the player 1 send scissors and the player 2 send paper" ❌ 
    - refactor first test to: "Should return 'Player 1 won!' when  player 1 send scissors and the player 2 send paper" ✅ 
    - Commit ✅

    - refactor second test to: "Should return 'Player 2 won!' when player 1 send paper and the player 2 send scissors" ✅
    - Commit ✅

    - refactor third test to: "Should return 'Player 1 won!' when player 1 send rock and the player 2 send scissors" ✅
    - Commit ✅

    - refactor second test to: "Should return 'Player 1 won!' when player 1 send paper and the player 2 send rock" ✅
    - Commit ✅

    - Create the fifth test: "Should return 'Player 2 won!' when only the player 1 send paper and the player 2 send scissors" ✅

    - Create the sixth test: "Should return 'Player 2 won!' when only the player 1 send rock and the player 2 send paper" ✅
    - Test passed ✅

    - Create the seventh test: "Should return 'Player 2 won!' when only the player 1 send scissors and the player 2 send rock" ✅

    - Code Refactored ✅

