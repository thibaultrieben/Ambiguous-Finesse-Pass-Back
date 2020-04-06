# Ambiguous-Finesse-Pass-Back

Our conventions so far.

## TODO
- def late game [added by thib]
  - proposition : late by colors or ranks. [added by kko]
- (indiquer trash : jouer le reste sens normal) Late game complements [added by thib]
- cyclic rearrangement: think about and train, eventually with chop focus. [added by kko]
- explicitly eliminate single card focus [added by kko]
- explain layered finesses [added by kko]
---------

## Misancellous
- We play _No Variant_ games on [our platform of preference](Hanabi.live).  
  - 5 colors x (1-1-1) (2-2) (3-3) (4-4) (5) ranks.  
- We were inspired by the [Hyphen-ated Conventions](https://github.com/Zamiell/hanabi-conventions/blob/master/Beginner.md#the-basics) and parts from the [_École Italienne (Alessandro Iraci)_](https://github.com/SashaIr/hanabi-conventions) ones.  
- Color over rank.  
- New cards go on left of the player, shifting the others to the right.
- **Finesse** position: left-most card without clues
- **Chop** position: right-most card without clues.
- **relevant**: eventually playable.  
- **unique**: relevant ant only copy left.  
- **useless**: cannot be played during the rest of the game.  
- **trash**: useless or another copy already clued.  


## Conventions

### No bad touch principle
- Clues must touch only eventually (_delayed_) playable cards.  
  - Supposedly immediately.
- Clues must not touch _already clued_ cards. (Disjoint clue principle)  

### Play order of cards  
**Normal order is left-to-right** (l2r).
- Play left, discard right. Plays in this order, except for the following:  
- 1s from first hands are played in reverse order (RIGTH-to-left). [ITA 9.4]  
  - even if clue given later.  
- 3/4 complement clues on the first round: unclued cards are played in reverse order (RIGHT-to-left).
- If 2 cards of color are clued :
  - rank clue on **lef**tmost => **play** rightmost
  - rank clue on **right**most => **NO** play leftmost  
  - make sure no finesse is involved.  
  - [ITA convention 6.7]  

### Prompt
- Prompt over finesse.  
- If a clued card could be a connecting card, it must be played first instead of the finesse card. (Connection principle)
- Multiple prompt : play all possible connecting cards. The prompt cannot be a lie. [HABeginner](https://github.com/Zamiell/hanabi-conventions/blob/master/Beginner.md#the-prompt)

### Finesses
- Blind play the Connecting card from the Finesse position (left-most unclued).
- usually Prioritary, to resyncronize information.
- Classic: (color) clue on one-away card : finesse for a player placed before the clued player.
- Reverse: (color) clue on one-away card : finesse for any player, even placed after the clued player.
- Multiple: connecting cards can be: Prompts or Bluffs (all cards on left are playable) or finesse then prompts or finesse and prompts and bluffs. [ITA 5.4]
- MultiPlayer : connecting cards spread among multiple players. [ITA 5.5]
- Delayed: (color) clue on a one-away card from the higher already clued and known card : finesse for any player.
- Delayed multi-card: clues on multiple relevant cards but _missing one_: another player has the missing in finesse. [ITA 6.1 partial]
- Layared: A finesse clue is given, but the connecting card is just to the right of the classic finesse position : the finesse position card is another finesse (the one-away card). Two finesses simultanously. [ITA 5.8]

### Bluff
[ITA 5.6] and [HAIntermediate] to compile.
- Classic: (color) clue on one-away card, but instead of the connecting card on the finesse position, another playable card is played. Clued player knows it's the one-away card.
- No "reverse" bluffs.


### Save clues
Clues must indicate cards to play, except when a card needs to ba saved. It's not the _discarder_ responsability.  

##### _Chiffre sur chop_ : Rank touches Chop
A Rank clue on a player's chop is a save clue if an already relevant cards of the same rank is in the discard. Other touched card don't have a specific meaning.


#### Chop move
- A Rank clue on an umplayable card is a save clue on the clued card and on all older cards.
- Look at players Chop cards.
- An usless clue (completed color/rank) is a save clue on older cards. FIXME: not a complement clue ?

### Double Discard Avoidance (DDA)
Until we adapt the complete _italian [ITA 11.1]_ dda for 5 colors and less players, we'll use a simpler _classic_ one.  
- Player cannot discard immediately after a relevant (not played yed, unclued) card was discarded, unless they see it in another hand.

For information : red is 1, yellow is 2, green is 3, blue is 4 and purple is 5, but rainbow is 0.

### Early Game (EG) and First round and First Player
- The first player must clue so at least 2 cards are playable. Finesses and 3/4 complements comply with this convention.  

- 3/4 complement. A 3 or 4 rank clue is a play clue in reverse order (RIGHT-to-left) on the untouched cards.  
  - [ITA 7.2] indicates whole EG but  
  - [ITA 9.3] indicates only first round.  


- Until the first **blind** discard:  
  - clues on unique 2s (colors only seen once) are save clues
  - 5 can be clued to stall.
  - EG should be _extended for as long as reasonably possible_ [HABeginer](https://github.com/Zamiell/hanabi-conventions/blob/master/Beginner.md#the-early-game).

### Discard clues
- No relevant cards on hand / short on clues : discard position of playable card for next player **with no info on what to do**.
