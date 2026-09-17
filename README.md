# Spellchess

Chess, plus a hand of spells. Play: https://nick-cio.github.io/spellchess/

Every turn you may cast a spell, then make a normal chess move. The king can never be captured: you win by checkmate, and spells can create check but never ignore it. Two modes.

## Original
- 15-card deck, 3 of each spell. Each player is dealt 3 face down and may swap one back for a random card before the first move. 2 cards are revealed from the deck at the start and 1 more every 4 full moves; the last 3 stay hidden.
- One spell per turn. Spells can take material.
- **Jump**: one of your pieces may pass over one piece in its path, or leap over an adjacent piece to the square behind it.
- **Rage**: a non-pawn piece (king allowed) moves like a queen this turn.
- **Speed**: the piece you move moves again. The second move cannot capture; the first may pass through check if the second gets you out.
- **Earth**: petrify any non-king square until your next turn. An empty square becomes a rock; a piece there cannot move, be captured or give check.
- **Parasite**: secretly infect a non-king piece. Dormant one turn, then whoever captures it during the opponent's next turn switches sides. Kings immune.
- In check with no legal move, a spell may save you; if none can, it's checkmate. Stalemate is a draw. Promotion is your choice.

## Draft
- Same spells, but they can never take material: Speed and Rage can't capture, Jump can't capture on the far side, Earth only on empty squares or your own pieces. Parasite unchanged.
- Up to 2 spells per turn.
- Hands are drafted: each player privately sees 3 pairs of different cards, one pair at a time, keeps one and gives the other to the opponent. 6 cards each. Both hands are face up once the draft ends. No swap, no reveals.

Optional chess clock, default 5+3.
