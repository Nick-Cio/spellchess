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
- **Jump** (green): pick one of your pieces. This turn it may pass over one piece in its path (rooks, bishops, queens) or leap over an adjacent piece to the square beyond (any piece; pawns only forward).
- **Rage** (red): one of your pieces, not a pawn, moves like a queen this turn. The king is allowed.
- **Speed** (yellow): the piece you move this turn moves a second time right after. The second move cannot capture. The first move may pass through check as long as the second move gets you out.
- **Earth** (brown): petrify any square except a king's. An empty square becomes a rock nothing can cross or land on. A piece there is locked in stone: it cannot move, be captured, or give check. Wears off at the start of your next turn.
- **Parasite** (black): secretly infect any piece except a king, yours or theirs. It lies dormant for one turn, then awakens at the start of your next turn. During the opponent's following turn, whoever captures that piece switches to the other color. A king capturing it is immune. You see a countdown above the piece; your opponent only sees that a Parasite was played.

## Kings and winning
- The king can never be captured. You win by checkmate, as in chess.
- You may not end your move with your own king in check. Spells can create check; they can't ignore it.
- If your turn starts in check with no legal move, a spell may still save you. If no card in your hand can produce a legal move, it's checkmate immediately.
- Pawns promote to a piece of your choice.
- Stalemate is a draw.

## Reading the table
- Your hand shows what you can cast.
- "Opponent could hold" shows all 15 cards, greying out any you can account for (your hand, revealed, discarded). The rest are what your opponent might have.

## Pacifist mode (experimental)
Same game, but spells can never take material, and you may cast up to 2 spells per turn. Chosen when creating a game.
- Deck of 20 (4 of each spell). Each player is dealt 6 and may swap 1.
- No hidden information: both hands are face up and nothing is revealed from the deck.
- **Speed**: neither move may capture.
- **Rage**: the raged piece may not capture.
- **Earth**: may only be placed on an empty square or one of your own pieces.
- **Jump**: no capturing on the far side of the jump.
- **Parasite**: unchanged.

## Draft mode (experimental)
Pacifist rules, but hands are built by a draft instead of being dealt.
- Each player privately gets 3 pairs of different cards and keeps one from each pair. The other card of each pair goes to the opponent face up.
- So everyone ends with 6 cards: 3 they chose (private) and 3 they were given (public to both). The opponent's public cards are shown; their private ones show as card backs.
- No swap, no deck reveals.
