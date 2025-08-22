# Slot Machine Game

A Python-based slot machine simulator that allows players to deposit money, place bets, and spin the reels to try their luck at winning!

## Features

- **Deposit System**: Start by depositing an amount to play with
- **Adjustable Betting**: Choose how many lines to bet on (1-3) and your bet amount per line
- **Visual Display**: See the slot machine results in a formatted grid
- **Winning Calculation**: Automatic calculation of winnings based on symbol values
- **Balance Tracking**: Keep track of your balance throughout the game session

## Game Symbols and Payouts

| Symbol | Count | Value | Payout Multiplier |
|--------|-------|-------|------------------|
| A      | 2     | 5     | 5x bet           |
| B      | 4     | 4     | 4x bet           |
| C      | 6     | 3     | 3x bet           |
| D      | 8     | 2     | 2x bet           |

## How to Play

1. Run the program using Python 3
2. Deposit an initial amount of money
3. Choose how many lines you want to bet on (1-3)
4. Set your bet amount per line ($1-$100)
5. Watch the slot machine spin!
6. Winnings are calculated based on matching symbols across lines
7. Continue playing until you decide to quit

## Winning Conditions

- Win by getting matching symbols across any horizontal line you bet on
- The payout multiplier depends on the symbol value
- Example: If you bet $10 on a line and get three 'A' symbols, you win $50 (5 × $10)

## Requirements

- Python 3.x
- No external dependencies required

## How to Run

```bash
python slot_machine.py
```

## Game Limits

- Maximum bet per line: $100
- Minimum bet per line: $1
- Maximum lines: 3

## Code Structure

The program consists of several main functions:

- `deposit()`: Handles initial money deposit
- `get_number_of_lines()`: Gets the number of lines to bet on
- `get_bet()`: Gets the bet amount per line
- `get_slot_machine_spin()`: Generates the slot machine result
- `check_winnings()`: Calculates wins based on symbols
- `print_slot_machine()`: Displays the slot machine visually
- `spin()`: Manages a single spin round
- `main()`: Controls the game flow

Enjoy the game and good luck!
