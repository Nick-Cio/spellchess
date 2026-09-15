# Spellchess

Chess, plus a deck of 15 spell cards. Play: https://nick-cio.github.io/spellchess/

## Setup
- Normal chess board and rules.
- Deck: 15 cards, 3 each of Jump, Rage, Speed, Earth, Parasite. Shuffled.
- Each player is dealt 3 cards, kept secret.
- 2 cards are flipped face up from the deck at the start, and 1 more every 4 full moves. These are public information only; nobody gets them.
- Used cards go face up on the discard pile.

## Your turn
1. Optionally cast **one** spell from your hand.
2. Make a normal chess move.

## The spells
- **Jump** (green): pick any piece except a king. This turn it doesn't exist for you: your sliding pieces pass through it, and any of your pieces next to it may leap straight over it to the far side.
- **Rage** (red): one of your pieces, not a pawn or king, moves like a queen this turn.
- **Speed** (yellow): the piece you move this turn moves a second time right after. The first move may pass through check as long as the second move gets you out.
- **Earth** (brown): place a rock on an empty square. Nothing can move through, onto, or capture it. It vanishes at the start of your next turn.
- **Parasite** (black): secretly infect any piece except a king, yours or theirs. Whoever captures that piece switches to the other color. A king capturing it is immune. Your opponent sees that you played a Parasite, but not which piece.

## Kings and winning
- The king can never be captured. You win by checkmate, as in chess.
- You may not end your move with your own king in check. Spells can create check; they can't ignore it.
- **Mate exception:** if your turn starts in check with no legal move, you may cast up to 2 spells that turn to try to escape. If you still have no move, it's checkmate.
- Stalemate is a draw.

## Reading the table
- Your hand shows what you can cast.
- "Opponent could hold" shows all 15 cards, greying out any you can account for (your hand, revealed, discarded). The rest are what your opponent might have.
