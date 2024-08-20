---
title: Card Game Rules Doc - Round Start-End Bak
enableToc: "true"
tags:
---
This fork preserves players being able to take actions during the round start and round end phases. - Created 8/20/2024
# Project Gamma Card Game Rules Document

- If you have not seen it, watch the [intro video](https://www.youtube.com/watch?v=cFHSIH5-CRY) 
- *This information is a work in progress*
- Project Gamma is a temporary name. The project is being merged/using the world/setting of birdsandbees' tabletop rpg project. Project Delta is the overarching 'group' that is creating project gamma among other things.
- See [[Card & TTRPG Outline & Plans]] and [[Card Game Onboarding]] for more general information.


>This is a 1v1 card game, within the gameplay genre of trading card games (not necessarily the distribution model). The rules will support draft and constructed. We intend on making a reusable draft format for 2 players and one for more players. You win the game by reducing your opponent's life total to 0.

The game takes place in Atnia, the setting of Ciaban's Tabletop RPG. A short briefing on the world can be found here: [[Atnia Introduction]]. 

# Rules for playing the game:

## Shared Round
During each round players will take turns taking actions (mainly playing cards!). Only one player is the active player at a time, and you can only take actions while you are the active player. These actions include:
- Play a Card or Ability - When you play a card/ability, the other player becomes the active player. | See "Playing Cards".
- Pass - By passing, the other player becomes the active player. When both players pass, if cards are being played, all cards resolve, and if no cards are being played, move to the next step/phase of the round.
- Attack / Enter Combat - See "Combat".
For more info, see "Round Phases"
---
## Zones
- Deck - Your deck of cards.
- Hand - Your hand.
- Reality - The main playing area / board. All cards that are currently in play live here.
- Memory - When cards are destroyed or discarded, they go here. It's the discard pile.
- Dream - Zone for cards & effects currently being played and not resolved yet. (stack)
- Void - Zone used for some things.
- Channel zone - Zone cards go after being channeled.
---
## Parts of a Card
- **Name**
- **Energy Cost** - To play a card, you must pay energy equal to it's energy cost.
- **Source Requirement(s)** - See "Power Sources"
- **Type** - See "Card Types"
- **Subtype** - See "Card Types"
- **Speed** - See "Playing Cards"
- **Offense/Defense Stats** - See "Card Types" & "Playing Cards"
- **Rules Text** - Explains what a card does. See "Playing Cards"

---
## Energy System
There is a single (numerical) energy pool for each player, the maximum energy you can have at any given time is 10. At round end, players retain up to 3 energy and any excess is discarded (banked energy limit of 3 is separate from the main 10 energy limit). Players begin the game with 2 energy counters and gain an additional 2 after each round (maximum is also 10). Each round, players get 1 energy for each of their energy counters.

---
## Power Sources
Sources are the main categorization of cards & affect which cards you will likely have in your deck, as to play cards from a source you must also have other cards of that source to meet it's source requirement. The power sources are diegetic concepts people in Atnia value, they represent the ways you can rally new allies to your side and do magical feats. The 5 sources are: 
- Arca - A chaotic and wild energy that has expanded throughout Atnia after the apocalypse. Highly magical, both destructive and creative, to many it is symbolic of the new world.
- Eminus - Your reputation among others or within a community. Trust built through a shared history or one's reputation is important to those who value Eminus.
- Material - Resources people need and desire in the new world. While the other sources are largely conceptual, Material is grounded in the physical reality of the world. Food, lumber, salt, stuff that has value independent of concepts & social dynamics.
- Old World - Drawing from ancient magics & past civilizations. While also very magical, it is in many ways the opposite of Arca, a romanticization of the past & apposed to the chaotic new world. Strongly connected to the coins/currency of the old Atnian kingdom.
- Zelor - Passion, emotion, storytelling. One who values Zelor may join you if they truly believe in your cause or you give a rousing speech. Zelor magic draws from sheer power of will.

*Source names subject to change, (particularly, Old World & Eminus).*

Different people and factions within Atnia will value the different power sources differently and in varying amounts or combinations. These will determine the vibes of different factions, units, spells, and in general cards that you can include in your deck.

Cards may have one or more source requirements, indicating how many cards of that source you must have total/combined among your channeled cards and allied claims in the reality zone. If you do not meet the source requirement, you cannot play the card.

---
## Card Types
- Unit - Units have offense stat in addition to their defense stat, and can attack and block. Other card types do not have an offense stat.
- Claim - The first claim you play each round costs 2 energy less.
- Item - Items cost 1 energy less for each round that has passed (1 less on round 2, 2 less on round 3, and so on.) 
- Spell - Spells do what is indicated by their rules text on resolution, then are put into memory, unlike other cards which resolve to reality.
- Starting Location - A deck may have one starting location card. It begins the game face up in void, and can be put into hand at any time throughout the game at `<speed%>` by putting a card from your hand on the bottom of your deck. 

Some cards will also have subtypes, but substyles do not have any universal rules significance

---
## Playing Cards & Dream
To play a card, you must meet it's source requirement and pay it's costs. The card is then put onto Dream, and the player who did not play the card becomes the active player, who may then take an action or pass. Any new cards put into dream are placed above other cards already there. Once both players pass, all cards in dream (unresolved cards) are resolved in order of top to bottom. 

When a card is played, it goes to Dream. When it resolves, it goes to reality (or memory if it is a spell). When a card in reality or dream dies / is destroyed, it is put into memory. When a card takes damage greater than it's defense stat, it is destroyed (damage only occurs to cards in dream & reality).

To reiterate, you pay a card's cost to play it, and only once it resolves it does it's effect and/or enters play. 

When all cards are resolved, and the player who did not begin the stack (by placing the first card in dream) becomes the active player.
## Speed
Cards with a given speed number can only be played if there are that many or fewer cards / abilities currently in dream. You may however pay 3 life per number accelerated to speed up your card and be able to play it in response to other cards. 
- Note: if there are no cards currently in dream, cards with negative speed values may be played without needing to be accelerated.
- All ∞ speed effects are always resolved before any others, cannot be responded to by any player, and do not affect which player is or becomes the active player.

### Advanced notes on timing rules and dream:
- If during dream effect resolution one or more new cards or effects are put into dream that are not at `<speed%>` speed, resolution stops, and the player not in control of the new top most card/effect becomes the active player.
- If effects would trigger simultaneously, they are put into dream all at once, in order of, from top to bottom:
	- Effects from the first player in the round above effects from other players. 
	- Top to bottom, triggers from cards in: Dream, Reality (combat before rest), Memory.
		- Dream, top to bottom: Cards higher in dream to cards lower in dream.
		- Reality, top to bottom: Cards on the left side of a players reality zone to cards on the right side of their reality zone (units, then items, then claims).
		- Memory, top to bottom: Cards higher in memory to cards lower in memory.
- If multiple effects that require targets to be chosen are put into dream simultaneously, targets must be chosen for the bottom most effect(s) first.
- New cards arrive in memory above cards already in memory.
- All new cards arrive in reality to the right of cards already in reality. Attacking and blocking does rearrange unit order, and at end of combat all attacking/blocking units return to the rest of the reality zone on the left of cards already there, in the same arrangement they were in combat.
---
## Card draw & Channel system
All cards in hand can be channeled into the channel zone at ∞ speed any time you are the active player. Channeling cards is primarily for fulfilling source requirements and getting rid of cards you don't want to replace them with new ones at the end of the round.
- You may channel a card face up or face down. Cards channeled face down as wild cards count as being from all sources, but draw 1 fewer card at the end of the round (unless it is done during draw step step 2).
- During the draw phase, 
---

## Round Phases
1. Pre round
	1. If it is not the first round of the game, the player with the highest total/combined offense across their units becomes the first player. If it is tied, the player who began as the second player in the previous round becomes the first player.
	2. Each player gets 2 additional energy counters, then each player gets 1 energy for each of their energy counters.
	3. Each player unflips all their flipped cards.
	4. Move to next phase
	- During the pre round phase, no player ever becomes active and card effects cannot occur.
2. Round Start
	1. If an effect refers to round start, it happens here.
	2. If there are effects, the first player becomes the active player.
	3. Once all effects are resolved / there are no unresolved effects, move to the next phase.
3. Main phase
	1. The first player becomes the active player.
	2. When a double pass occurs while there are no unresolved effects, move to the next phase.
	- This is the primary phase where players actually play the game.
4. Round End
	1. If an effect refers to round end, it happens here.
	2. If there are effects, the first player becomes the active player.
	3. Once all effects are resolved / there are no unresolved effects, move to the next phase.
5. Draw Phase
	1. The number of cards total in a player's hand, face up in their channel zone, + 2, (up to 10) becomes that player's maximum hand size for the round.
	2. Players may channel face down any number of cards from their hand.
	3. Each player puts all cards from their channel zone on the top and/or bottom of their deck in any order/combination (not revealed to other players).
	4. Players draw up to their maximum hand size.
	5. Begin next round
	- During the draw phase, no player ever becomes active and card effects cannot occur.
- Combat phase
	- See "Combat"
---
## Combat
During the main phase, while you are the active player and there are no unresolved effects, you may start an attack by declaring your attackers. You may only attack twice per round.

Combat phase outline:
1. Step 1 - (No player becomes active) Combat begins with the active player declaring one or more attackers. After attackers are declared, any triggers created are put into dream, however only ∞ speed triggers are resolved. Move to step 2.
2. Step 2 - (No player becomes active) Defending player declares up to one blocking unit for each attacking unit. After defenders are declared, any triggers created are put into dream, however only ∞ speed triggers are resolved. Move to step 3.
3. Step 3 - The attacking player becomes the active player. After a double pass occurs, all cards and effects in dream are resolved, then all battling units simultaneously strike (deal damage equal to their offense stat) the unit blocking/being blocked by them, and if they are attacking unblocked, to the defending player.
4. End combat, return to the main phase, and the player who was defending becomes the active player. 
Notes:
- Both attacking and blocking causes units to flip.
- You cannot attack or block with flipped units.
- By attacking, the attacking player becomes the first player for the remainder of the round / until another player attacks.
- During combat, the floor to speed is 0, any negative speed cards must be accelerated to 0 to be played during combat.
---
## Starting the game
To start the game, randomly determine the first player. Each player shuffles their deck, (reveals their starting claim if the format has one), and draws 8 cards, keeping 5 and putting the rest on the top and/or bottom of their deck in any order. After both players have finished drafting their hands, begin the first round of the game.

---
## Extra Notes
- The first player 
- Some cards may have activated abilities, indicated by `<$>` symbol. These abilities can be activated and played similar to cards. Unless otherwise noted, you may only activate abilities of cards in play.

## Card Semantics
Eh see the spreadsheet for this (when I add it). But for now, here's *some* info: 
- There will be symbols for card parameters, as well as each zone. A zone icon may indicate which zones a card or effect can target, or which cards in what zones are relevant to it.
- Keywords will be listed... in the spreadsheet when I get to it.

## Formats and ways to play the game

These are all just potential ideas. All can be played in best 2/3 or best of one.
- Draft. It's cube draft.
- Constructed: 60 total cards, max 3x of each card, 15 card sideboard.
- Highlander: 80 cards, max 1x of each, featuring the *super cool draft pool!* There will be a universal pool of ~30 cards, all realmless. This set of cards can rotate over time, perhaps weekly or monthly, hand picked and brand new cards selected for the pool. At the start of each match, shuffle the 30 card pool and create two {packs} of 10 (numbers not decided yet and must be tested) cards from the top, then draft 5 cards from those packs with your opponent. Do the same thing after game 1 and 2 (if you go to game 3) (no sideboarding) (you are required to put all the cards you draft into your deck) (this may have issues with claim count since you are changing the number of non claims, we'll have to figure a solution to that out later). 
- Mirror Format
- Experimental: fast cycle format. 20 cards, and you cycle through them

## Mirror Format
Limited format for 2 players where you draft your cards for each round. Both players begin the game with an identical preconstructed deck of cards (one being the red deck and the other the blue deck). Each deck is a kind of mini cube, with support for a variety of strategies.

Instead of drawing cards normally at the end of each round and start of the game, players draft cards. Also, in mirror format, cards are channeled face down rather than face up.

## Source Limited
Limited format for 2 players. Rather than each player having their own deck, 5 decks (each one for all cards of a given source) are shared by both players. The top card of each of these decks is always face up / revealed. When drawing a card, players may choose which deck to draw from. When starting the game, players draw their starting hands by taking two cards from each deck, and keeping 5. All cards are channeled face down, and are not recycled into the decks at round end (players will still draw back to their max hand size).

### Ski Draft (questionable)
Both players take 10 cards from the top of their deck. Each player picks 1 card to keep, then passes the rest to their opponent. From pick 2 on, each pick players keep an additional card than the previous pick. Continue until all cards are drafted. Note: in this draft format, chosen/drafted cards are revealed as they are drafted.

- At the end of the round the following steps are carried out:
	- Each player may put any number of cards from their hand into their channel zone. The number of cards in a players hand and channel zone + 3, (up to 10) becomes that players' maximum hand size for the round round.
	- Each player puts all cards from their channel zone on the top and/or bottom of their deck in any order/combination
	- The draft is carried out, and all drafted cards are added to players hands. (Mirror format can be played with many draft formats, Ski Draft is recommended for players newer to the format, while [Hausman draft](https://luckypaper.co/resources/formats/housman-draft/) is worth trying at some point. Feel free to invent your own if you like.)
	- Players discard down (to the bottom of their deck) to their maximum hand size.

To begin the game, rather than drawing starting hands normally, start with a draft, with maximum hand size 5.

