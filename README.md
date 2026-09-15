# Spellchess

Chess, plus a deck of 15 spell cards. Play: https://nick-cio.github.io/spellchess/

## Setup
- Normal chess board and rules.
- Deck: 15 cards, 3 each of Jump, Rage, Speed, Earth, Parasite. Shuffled.
- Each player is dealt 3 cards, kept secret.
- 2 cards are flipped face up from the deck at the start, and 1 more every 4 full moves, but the last 3 cards of the deck are never revealed. Revealed cards are public information only; nobody gets them.
- Used cards go face up on the discard pile.
- **Opening swap:** before the first move, each player may secretly swap one card from their hand for a random one from the deck (the swapped card is shuffled back in). Both choose at the same time; the initial reveal happens after.

## Your turn
1. Optionally cast **one** spell from your hand.
2. Make a normal chess move.

## The spells
- **Jump** (green): pick any piece except a king. This turn it doesn't exist for you: your sliding pieces pass through it, and any of your pieces next to it may leap straight over it to the far side.
- **Rage** (red): one of your pieces, not a pawn, moves like a queen this turn. The king is allowed.
- **Speed** (yellow): the piece you move this turn moves a second time right after. The second move cannot capture. The first move may pass through check as long as the second move gets you out.
- **Earth** (brown): petrify any square except a king's. An empty square becomes a rock nothing can cross or land on. A piece there is locked in stone: it cannot move, be captured, or give check. Wears off at the start of your next turn.
- **Parasite** (black): secretly infect any piece except a king, yours or theirs. For the next 3 opponent turns, whoever captures that piece switches to the other color. A king capturing it is immune. You see a 3-dot countdown above the piece; your opponent only sees that a Parasite was played.

## Kings and winning
- The king can never be captured. You win by checkmate, as in chess.
- You may not end your move with your own king in check. Spells can create check; they can't ignore it.
- If your turn starts in check with no legal move, a spell may still save you. If no card in your hand can produce a legal move, it's checkmate immediately.
- Pawns promote to a piece of your choice.
- Stalemate is a draw.

## Reading the table
- Your hand shows what you can cast.
- "Opponent could hold" shows all 15 cards, greying out any you can account for (your hand, revealed, discarded). The rest are what your opponent might have.
