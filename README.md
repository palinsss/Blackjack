# Blackjack

Java project simulating the card game Blackjack as part of a simplified casino simulation (university assignment, TU Wien).

## Features
- Card game logic for Blackjack (21) with standard rules:
  - Goal: reach 21 points without exceeding it
  - Player competes directly against the bank (dealer)
  - Blackjack with two cards (Ace + 10-value card) automatically wins
  - Actions: hit (draw card), stay, automatic draw for dealer
  - Busted (value > 21) results in immediate loss
- Classes for cards, hands, deck, dealer, and players
- Exception handling for special cases (invalid decks, no more cards, illegal operations)
- Simulation of game flow via `Application.main()`

## Technologies
- Java 17
- IntelliJ IDEA
- Git / GitHub

## Project Structure
- `BJCard.java` — representation of a single playing card  
- `BJHand.java` — represents the cards held by a player or dealer  
- `BJDeck.java` — deck of 52 standard cards, with shuffle and deal functionality  
- `BJDealer.java` — dealer logic and game supervision  
- `BJPlayer.java` — player logic  
- `Application.java` — main entry point, connects all components  
- `BadDeckException.java`, `IllegalOperationException.java`, `OutOfCardsException.java` — error handling  
- `Interfaces/` — provided interface definitions  
- `Provided/` — additional given code  

## License
This project is licensed under the MIT License.
