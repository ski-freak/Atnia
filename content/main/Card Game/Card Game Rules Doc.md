---
title: Card Game Rules Doc
enableToc: "true"
tags:
---
# Project Gamma Card Game Rules Document

- *This information is a work in progress*
- Project Gamma is a temporary name. The project is being merged/using the world/setting of birdsandbees' tabletop rpg project. Project Delta is the overarching 'group' that is creating project gamma among other things.
- See [[Card & TTRPG Outline & Plans]] and [[Card Game Onboarding]] for more general information.


>This is a 1v1 card game, within the gameplay genre of trading card games (not necessarily the distribution model). The rules will support draft and constructed. We intend on making a reusable draft format for 2 players and one for more players. You win the game by reducing your opponent's life total to 0.

The game takes place in Atnia, the setting of Ciaban's Tabletop RPG. A short briefing on it can be found here: [[Atnia Introduction]]. 

# Rules for playing the game:

### Shared Round
During each round players will take turns playing cards and taking actions. These actions include:
- Pass - When both players pass, if cards are being played, all cards resolve, and if no cards are being played, move onto the next step/phase of the round. Everything basically revolves around this double pass system, both players pass, then everything resolves and/or you move to the next step/phase.
- Play a Card or Ability - See "Playing Cards".
- Attack / Enter Combat - See "Combat".

### Round Phases:
1. - Round Start (unflip, beginning step)
	- Each player gets 1 energy for each of their energy counters.
	- Each player unflips all their flipped cards.
	- If an effect refers to the start of the round, it happens here.
2. Main phase
	- Players take turns taking actions.
3. - Round End
	- If an effect refers to the end of the round, it happens here.
	- Each player gets an energy counter.
	- Do end of turn things, then discard down to max hand size and start the next round.

### Combat:
During the main phase while you have priority and there are no unresolved effects, you may start an attack by declaring your attackers. You may only attack twice per round.

Combat phase outline:
1. Step 1 - Combat begins with the active player declaring one or more attackers. After attackers are declared, all triggers created are put on the stack/dream, however, no player is given priority and only triggers at {infinite} speed are resolved. Then move to step 2.
2. Step 2 - Defending player declares up to one blocking unit for each attacking unit. After defenders are declared, all triggers created are put on the stack/dream, however, no player is given priority and only triggers at {infinite} speed are resolved. Then move to step 3.
3. Step 3 - The attacking player is given priority. After a double pass occurs, the stack/dream is resolved. Then all battling units deal damage equal to their offense value to the unit blocking/being blocked by them, and if they are attacking unblocked, to the defending player.
- End of combat.
Notes:
- Both attacking and blocking causes units to flip, and you cannot attack or block with flipped units.
- After combat, the game returns to the main phase and the player who was defending is given priority.
- By attacking, the attacking player becomes the first player for the remainder of the round / until the other player attacks.
- During combat, the floor to speed is 0, any negative speed cards must be accelerated to 0 to be played during combat.

### Zones:
- Deck - Your deck of cards.
- Hand - Your hand.
- Reality - The main playing area / board. All cards that are currently in play live here.
- Memory - When cards are destroyed or discarded, they go here. It's the discard pile.
- Dream / The stack - Zone for cards currently being played and not resolved yet.
- Void - Zone used for some things.
- Channeled cards zone - Zone cards go after being channeled.

### Sources 
Similar to the colors in magic. Currently they are: Arca, Eminus, Material, Old World, and Zelor (although some of these names may be subject to change.)

### Card Types:
There are multiple card types:
- Unit - Units have offense stat in addition to their defense stat, and can attack and block.
- Claim - The first claim you play each round costs 2 energy less.
- Item - Items cost 1 energy less for each round that has passed (1 less on round 2, 2 less on round 3, and so on.) 
- Spell - Spells do their thing on resolution, then are put into memory, unlike other cards which resolve to reality.
- Starting Location - A deck may have one starting location card. It begins the game face up in void, and can be put into hand at any time throughout the game at `<speed%>` by putting a card from your hand on the bottom of your deck. 
(Some cards will also have subtypes, but these do not necessarily have any rules significance)

All cards have a numerical energy cost, Source requirement(s), and Speed value, as well as a Defense stat.

### Playing Cards:
To play a card, you must meet it's source requirement and pay it's costs. The card is then put onto the stack/dream, and priority is given to your opponent to either respond to it with their own card, or pass. Any new cards put into dream/the stack are put on top of other cards already there. Once both players pass, all cards in dream/the stack (unresolved cards) are resolved in order of top to bottom. When resolving, units, claims, and items are put onto the board, and spells are put into memory. To reiterate, you pay a cards cost to play it, and only when it is resolved it does it's effect and/or enters play. When all cards are resolved, priority is given to the player who did not begin the stack.

Cards with a given speed number can only be played if there are that many or fewer cards and/or abilities currently in dream/the stack. You may however pay 3 life per number accelerated to speed up your card and be able to play it in response to other cards. 
- Note: if there are no cards currently being played / in dream/the stack, cards with negative speed values may be played without needing to be accelerated.

Cards may have one or more source requirements, indicating how many cards of that source you must have total/combined face up among your channeled and allied claims of that source in play. For each source (number) you are missing, the card costs 1 energy more to play.

Notes on timing and dream/the stack:
- All `<speed%>` (infinite speed) speed effects are resolved before any others, cannot be responded to by any player, and do not affect who has priority.
- All effects trigger simultaneously are put onto the stack/dream all at once, from top to bottom in order of:
	- Effects from the first player in the round above effects from other players. 
	- Top to bottom: Cards on the left side of a players board to cards on the right side of their board board (units, then items, then claims).  
- All combat strikes are processed left to right (from the attacker's pov). All new cards arrive in play on the right side of their area. Attacking and blocking does rearrange unit order, and at end of combat all attacking/blocking units return to the main play area on the left side, in the same arrangement they were in combat.
- If during stack resolution one or more new cards or effects are put onto the stack that are not at `<speed%>` speed, stack resolution stops, and priority is given to the player not in control of the new top most card/effect.

### Channel and main card draw system:
All cards in hand can be channeled into the channel zone to produce 1 energy (cards can be channeled face up or face down). There is a single (numerical) energy pool for each player, there is no maximum/cap to how much energy you can have at any given time. At round end, players retain up to 3 energy and any excess is discarded.
- Note: Channeling cards is done at `<speed%>` (infinite speed) (it cannot be responded to, but you may still only do it when you have priority).

- At the end of the round the following steps are carried out:
	- Each player may put any number of cards from their hand into their channel zone. The number of cards in a players hand and channel zone + 2, (up to 10) becomes that players' maximum hand size for the round round.
	- Each player puts all cards from their channel zone on the top and/or bottom of their deck in any order/combination
	- Players draw up to their maximum hand size.


### Starting the game:
To start the game, randomly determine the first player. Each player then shuffles their deck, (reveals their starting claim if the format has one), and draws 8 cards, keeping 5 and putting the rest on the top and/or bottom of their deck in any order. After both players have finished drafting their hands, begin the first round of the game, priority starting with the first player as randomly determined. At each round start (before any steps or phases happen), the player with the highest total/combined offense of their units becomes the first player. If it is tied, the player who began as the second player in the previous round becomes the first player.

## Extra Notes:
- Cards can take damage when in dream or in play. When a card receives damage greater than it's defense stat, it is put into memory.
- Some cards may have activated abilities, indicated by `<$>` symbol. These abilities can be activated and played similar to cards. Unless otherwise noted, you may only activate abilities of cards in play.

## Card Semantics:
Eh see the spreadsheet for this (when I add it). But for now, here's *some* info: 
- There will be symbols for card parameters, as well as each zone. A zone icon may indicate which zones a card or effect can target, or which cards in what zones are relevant to it.
- Keywords will be listed... in the spreadsheet when I get to it.

## Formats and ways to play the game:

These are all just potential ideas. All can be played in best 2/3 or best of one.
- Draft. It's cube draft.
- Constructed: 60 total cards, max 3x of each card, 15 card sideboard.
- Highlander: 80 cards, max 1x of each, featuring the *super cool draft pool!* There will be a universal pool of ~30 cards, all realmless. This set of cards can rotate over time, perhaps weekly or monthly, hand picked and brand new cards selected for the pool. At the start of each match, shuffle the 30 card pool and create two {packs} of 10 (numbers not decided yet and must be tested) cards from the top, then draft 5 cards from those packs with your opponent. Do the same thing after game 1 and 2 (if you go to game 3) (no sideboarding) (you are required to put all the cards you draft into your deck) (this may have issues with claim count since you are changing the number of non claims, we'll have to figure a solution to that out later). 
- Mirror Format
- Experimental: fast cycle format. 20 cards, and you cycle through them

## Mirror Format:
Limited format for 2 players where you draft your cards for each round. Both players begin the game with an identical preconstructed deck of cards (one being the red deck and the other the blue deck). Each deck is a kind of mini cube, with support for a variety of strategies.

Instead of drawing cards normally at the end of each round and start of the game, players draft cards. Also, in mirror format, cards are channeled face down rather than face up.

## Source Limited
Limited format for 2 players. Rather than each player having their own deck, 5 decks (each one for all cards of a given source) are shared by both players. The top card of each of these decks is always face up / revealed. When drawing a card, players may choose which deck to draw from. When starting the game, players draw their starting hands by taking two cards from each deck, and keeping 5. All cards are channeled face down, and are not recycled into the decks at round end (players will still draw back to their max hand size).

#### Ski Draft:
Both players take 10 cards from the top of their deck. Each player picks 1 card to keep, then passes the rest to their opponent. From pick 2 on, each pick players keep an additional card than the previous pick. Continue until all cards are drafted. Note: in this draft format, chosen/drafted cards are revealed as they are drafted.

- At the end of the round the following steps are carried out:
	- Each player may put any number of cards from their hand into their channel zone. The number of cards in a players hand and channel zone + 3, (up to 10) becomes that players' maximum hand size for the round round.
	- Each player puts all cards from their channel zone on the top and/or bottom of their deck in any order/combination
	- The draft is carried out, and all drafted cards are added to players hands. (Mirror format can be played with many draft formats, Ski Draft is recommended for players newer to the format, while [Hausman draft](https://luckypaper.co/resources/formats/housman-draft/) is worth trying at some point. Feel free to invent your own if you like.)
	- Players discard down (to the bottom of their deck) to their maximum hand size.

To begin the game, rather than drawing starting hands normally, start with a draft, with maximum hand size 5.

