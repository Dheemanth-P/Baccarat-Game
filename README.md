# 🎴 Virtual Baccarat Game (C++)

A terminal-based Baccarat game written in C++ where you can bet on the **Banker** or **Player**, and watch as virtual cards are drawn and totals calculated. Try your luck with ₹10,000 virtual currency!

## 📌 Features

- Simple Baccarat rules implementation
- Bet on Banker or Player
- Natural win (8 or 9) handling
- Third card rule simulation
- ASCII-style card graphics
- Balance tracking across rounds

## 🖥️ Demo

```text
==============================
WELCOME TO VIRTUAL BACCARAT
==============================
Current balance: 10000
1-BANKER 
2-PLAYER 
Choose your bet: 1
Place your bet, Betting amount: 500

==============================
      = BANKER'S CARDS =
  ==============================
========
|      |
|   7  |
|      |
========
First Card: 7
========
|      |
|   2  |
|      |
========
Second Card: 2
========
|      |
|   1  |
|      |
========
Total: 0  
Extra Card: 1

...

BANKER WINS
YOU WIN!
Current Money: 10500

```
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


2. Compile the code using `g++`:

   ```bash
   g++ -o baccarat baccarat.cpp
   

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

