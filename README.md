# Mega-game



MegaGame 🎰

MegaSpin is a simple Python-based slot machine game where players can deposit money, place bets on multiple lines, and try their luck to win big! Perfect for learning Python basics like loops, functions, randomization, and user input.

📝 Features

Deposit and manage your virtual balance.

Bet on 1 to 3 lines per spin.

Adjustable bet amount per line.

Randomly generated slot machine spins.

Calculates winnings based on matching symbols.

Shows winning lines and total payout.

Easy-to-read terminal interface.

🎮 How to Play

Run the Python script:

python megaspin.py


Deposit an amount to start playing.

Select the number of lines you want to bet on (1–3).

Choose a bet amount per line.

Spin the slot machine.

Check if you won and see your updated balance.

Repeat until you quit (q) or run out of balance.

💰 Symbol Payouts
Symbol	Value
A	5x
B	4x
C	3x
D	2x

The more rare the symbol, the higher the payout!

⚙️ How It Works

The slot machine has 3 rows and 3 columns.

Symbols are randomly chosen based on predefined counts:

symbol_count = {
    "A": 2,
    "B": 4,
    "C": 6,
    "D": 8
}


Players win if symbols match across the lines they bet on.

Winnings are calculated as symbol_value * bet.

📦 Requirements

Python 3.x

No external libraries required

🔧 Usage Example
Current balance: $100
Enter the number of lines to bet on: 2
Enter bet per line: $10
Spin results:
B | C | D
C | C | C
D | A | B
You won $40 on lines: 2

🎯 Goals & Learning

MegaSpin is designed to help Python learners practice:

Loops and nested loops

Functions and modular code

Random number generation

User input validation

Basic game logic

📁 Future Improvements

Add a GUI using Tkinter or Pygame.

Include more symbols and paylines.

Add animations and sound effects.

Implement saving/loading balance.
