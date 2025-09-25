**1. Description**

A Python-based console version of the popular Blackjack card game. The player competes against a computer dealer to reach a score as close to 21 as possible without going over. The rules for Aces, dealer logic, and win/loss conditions follow standard Blackjack gameplay.

**2. How It Works**

1.The program prints a logo at the start of each game round.

2.Both player and dealer are each dealt two cards.

3.The player can choose to draw more cards (hit) or pass (stand).

4.When it's the dealer's turn, the dealer draws until reaching a minimum score of 17.

5.Aces automatically adjust between 11 and 1 as needed.

6.Special "Blackjack" (an Ace and 10-valued card as starting two cards) is handled.

7.The winner is declared based on final hands and scores.

**Operators and Functions Used**

Operators:

1. = (Assignment): Assigning values to variables and lists.

2. +, -, *, /: Used for arithmetic calculations, particularly in score and loop range.

3. []: List indexing and creation (e.g., user_cards and appending cards).

4. ==, !=, >, <, >=, <=: Used for equality and comparison checks throughout flow control.

5. in: Checks membership for handling Aces and prompt choices.


Functions and Methods:

1. print(): Displays game state, prompts, and results.

2. input(): Collects user's choices at various stages.

3. random.choice(): Selects random cards from the deck for both player and dealer.

4. sum(): Totals up the values in a list of cards for score calculation.

5. .append(): Adds new cards to user_cards or computer_cards during play.

6. .remove(): Replaces an Ace value in the player's/dealer's hand when needed.

7. User-defined functions: deal_card(), calculate_score(), compare(), and play_game() encapsulate the main logic and game flow.

8. while and for loops: Used for main game loop, drawing cards, and dealer decision logic.

9. and, or: Used within conditionals to combine multiple logical checks.

10. : Used for list methods like .append() and .remove() as well as string formatting and module referencing.
