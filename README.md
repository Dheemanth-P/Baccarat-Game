
````markdown
# 🎴 Virtual Baccarat Game in C++

This is a console-based implementation of the **Baccarat** card game, written in C++. The game simulates a virtual casino experience where a player can place bets on the **Banker** or the **Player**, and cards are drawn according to Baccarat rules.

## 🕹️ Game Overview

Baccarat is a simple card game where two hands are compared:
- **Banker's hand**
- **Player's hand**

The hand whose total is closest to 9 wins. If the total is 8 or 9 on the first two cards, it's called a **natural win**, and no more cards are drawn. Otherwise, a third card might be drawn based on simple rules.

## 💡 Features

- Simulates a basic Baccarat game in the terminal
- Allows betting on **Banker** or **Player**
- Card values are randomly generated
- Handles natural wins and third card draws
- Win, lose, or tie conditions handled
- Starting balance: ₹10,000
- ASCII-style card display

## 🛠️ Requirements

- C++11 or higher
- A terminal or command-line interface

## 🚀 How to Run

1. Clone the repository or download the code:
   ```bash
   git clone https://github.com/your-username/baccarat-cpp.git
   cd baccarat-cpp
````

2. Compile the code using `g++`:

   ```bash
   g++ -o baccarat baccarat.cpp
   ```

3. Run the game:

   ```bash
   ./baccarat
   ```

## 🎮 Gameplay Instructions

1. Select your bet type:

   * 1 for Banker
   * 2 for Player

2. Enter your bet amount (cannot exceed current balance).

3. Cards are dealt and compared:

   * If the total is 8 or 9, it's a natural win.
   * If not, an extra card is drawn.

4. Winnings are added or subtracted based on the result.

5. Continue playing until you quit or run out of balance.

## 📁 File Structure

```bash
.
├── baccarat.cpp       # Main game source code
└── README.md          # Project documentation
```

## 🧑‍💻 Author

Dheemanth.P
