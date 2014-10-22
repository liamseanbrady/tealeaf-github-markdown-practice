# Practice Markdown Project

## Deployment

[on my Github!](github.com/liamseanbrady)

## Design Plan

### Routes Needed

  - get - Name, Hand, Compare, Deck, Cards, About
  - post - Player's inputs -> "Name", "Hit"/"Stay", 
  - post - Dealer Turn -> Hit until >17
  - post - Comparison if both stays & < 21

### Heading - Methods

  - Total
  - Alert message

### UI Specifications

  - Simple
  - Clear Buttons
  - Spacing
  - Easy-To-Follow w/out instruction

### Edge Cases

  1. How would the deck looks like when player or dealer keep hitting, and have many cards on deck?
  2. Potential overrunning the deck edge or buttons ?
  3. What if both players hit blackjack at same time, first player won?


### Strategy for Building the App

  - Separate methods in Helpers to organize
  - Pay attention to the duplication
  - CSS + Bootstrap -> Responsive Design
  - Betting

### Heading - Game Flow:

  - Setup Name
  - Setup Bet amount

  - Deck
  - Cards
  - Deal Cards
    - Player
    - Dealer
  - Total
  - Show Hand
  - Player - Hit or Stay
  - Is busted ?
  - Dealer - Hit until total is more than 17
  - Compare their total
  - Who wins ?
  - Player again or not ?
