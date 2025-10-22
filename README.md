**Overview**

The Blackjack Console Game is a Python implementation of the classic casino card game — Blackjack (21).
In this game, the player competes against the computer to get as close to 21 as possible without exceeding it. The game dynamically tracks scores, evaluates win/loss conditions, and offers a realistic gameplay experience right in the terminal.

This project reflects a significant step in my Python learning journey — moving from simple scripts to structured, logic-heavy, and replayable applications.

Learning Objectives & Technical Implementation

Through this project, I explored a variety of intermediate-to-advanced Python programming concepts:

**Concept	& Description**

1. Functions & Modular Design - Used multiple helper functions (deal_card(), calculate_score(), compare(), etc.) to maintain organized and reusable code.
2. Randomization (random.choice)	- Implemented a pseudo-random card selection mechanism to mimic real card draws.
3. Control Flow & Game Logic	- Designed a turn-based flow for player and computer moves, with conditions to check for Blackjack, busts, and draws.
4. Score Calculation & Logic Handling - Managed edge cases like treating Ace (11) as 1 when total exceeds 21.
5. While Loops & Replay Option -	Enabled continuous gameplay until the player chooses to exit, demonstrating control structure handling.
6. Comparative Conditions - Built custom comparison logic in the compare() function to determine game outcomes.
7. Use of External Modules -	Imported a custom art module for game logo display, improving user experience in the console.

This project improved my understanding of algorithmic thinking, logical sequencing, and real-world problem simulation using Python

**Example Gameplay**

Welcome to Blackjack!
Your cards: [10, 7], current score: 17
Computer's first card: 9
Type 'y' to get another card, type 'n' to pass: y
Your cards: [10, 7, 4], current score: 21
Computer's final hand: [9, 10], final score: 19
You win 😃
