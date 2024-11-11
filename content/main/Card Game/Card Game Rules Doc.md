---
title: Card Game Rules Doc
enableToc: "true"
tags:
---
# Project Gamma Card Game Rules Document

- If you have not seen it, watch the [intro video](https://www.youtube.com/watch?v=cFHSIH5-CRY) 
- This information / rules document is a work in progress
- See [[Card & TTRPG Outline & Plans]] and [[Card Game Onboarding]] for more general information.
- For info on setting up software for testing, see [[Card Game Testing Info]].
- This [Google Sheet](https://docs.google.com/spreadsheets/d/1v2kB2lh71D9G-9cLPd3Aqkp0UxqjCQWOMH--ha0lmy0/edit?gid=289416360#gid=289416360) displays all of the cards.
- Join the [Discord](https://discord.gg/xTdT2DpEwB) if you haven't yet.


>This is a 1v1 card game, within the gameplay genre of trading card games (not necessarily the distribution model). The rules will support draft and constructed. We intend on making a reusable draft format for 2 players and one for more players. The game rules are being made to work both in paper and as a video game. You begin the game at 20 life and win the game by reducing your opponent's life total to 0.

The game takes place in Atnia, the setting of Ciaban's Tabletop RPG. A short briefing on the world can be found here: [[Atnia Introduction]]. 

# Rules for playing the game:

## Shared Round
During each round players will take turns taking actions (mainly playing cards!). Only one player is the active player at a time, and only the active player can take actions. These actions include:
- Play a card or ability of a card - See "Playing Cards"
- Take universal actions such as passing, channeling cards, or attacking.
	- Pass - By passing, the other player becomes the active player.

---
## Zones
- Deck - Your deck of cards.
- Hand - Your hand.
- Reality - The main playing area / board. All cards that are currently in play live here.
- Memory - When cards are destroyed or discarded, they go here. It's the discard pile.
- Dream - Zone for cards & effects currently being played and not resolved yet. (stack)
- Void - Zone used for some things.
- Channel zone - Zone cards go after being channeled.
- Location zone - Zone locations go to after being played.
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

![[Pasted image 20240830204450.png|500]]

---
## Energy System
There is a single (numerical) energy pool for each player, the maximum energy you can have at any given time is 10. At round end, players retain up to 3 energy and any excess is discarded (banked energy limit of 3 is separate from the main 10 energy limit). Players begin the game with 3 energy counters and gain an additional one after each round (maximum is also 10). Each round, players get 1 energy for each of their energy counters.

---
## Power Sources
Sources are the main categorization of cards & affect which cards you will likely have in your deck, as to play cards from a source you must also have other cards of that source to meet it's source requirement (appears as a number of symbols for given sources). The power sources are diegetic concepts people in Atnia value, they represent the ways you can rally new allies to your side and do magical feats. The 5 sources are: 
- Arca - A chaotic and wild energy that has expanded throughout Atnia after the apocalypse. Highly magical, both destructive and creative, to many it is symbolic of the new world.
- Eminus - Your reputation among others or within a community. Trust built through a shared history or one's reputation is important to those who value Eminus.
- Material - Resources people need and desire in the new world. While the other sources are largely conceptual, Material is grounded in the physical reality of the world. Food, lumber, salt, stuff that has value independent of concepts & social dynamics.
- Old World - Drawing from ancient magics & past civilizations. While also very magical, it is in many ways the opposite of Arca, a romanticization of the past & apposed to the chaotic new world. Strongly connected to the coins/currency of the old Atnian kingdom.
- Zelor - Passion, emotion, storytelling. One who values Zelor may join you if they truly believe in your cause or you give a rousing speech. Zelor magic draws from...

*Source names subject to change, (particularly, Old World & Eminus).*

Different people and factions within Atnia will value the different power sources differently and in varying amounts or combinations. These will determine the vibes of different factions, units, spells, and in general cards that you can include in your deck.

Cards may will often have a source requirement, a number of symbols indicating how much devotion to that source you need to have to play it. Your devotion to a source is equal to the number of individual cards (not the icons on them) of that source you must have total/combined among your channeled cards and allied locations in the reality and dream zones. If you do not meet the source requirement, you cannot play the card.

Currently the source icons are as follows: Arca is a purple ring of magical energy, Eminus is a yellow hand shake, Material is a green plank of wood, Old World is a blue coin, and zelor is a red book.

You can tell what a card's source(s) are by which source icons are on it's source requirement.

---
## Card Types
- Unit - Units have offense stat in addition to their defense stat, and can attack and block. Other card types do not have an offense stat.
- Location - When you play a location it goes to the location zone. Locations count towards source devotion/requirements while in the location zone (as well as the channel zone).
- Item - Items can have different subtypes that give them unique effects
- Spell - Spells do what is indicated by their rules text on resolution, then are put into memory, unlike other cards which resolve to reality.
- Starting Location - A deck may have one starting location card. It begins the game face up in the location zone.

Some cards will also have subtypes, but substyles do not have any universal rules significance

---
## Playing Cards & Dream
To play a card, you must meet it's source requirement and pay it's costs.

When you play a card or ability, it is put onto Dream, and the player who did not play the card becomes the active player, who may then take an action or pass. Any new cards/effects put into dream are placed above other cards/abilities already there. Once a player passes, all cards in Dream (unresolved cards) are resolved in order of top to bottom.

When a card is played, it goes to Dream. When it resolves, it goes to reality if it is a unit or item, and goes to memory if it is a spell. When a card in reality or dream is destroyed (such as by taking damage greater than it's defense stat), it is put into memory. Damage only occurs to cards in dream & reality.

- To reiterate, you pay an ability or card's cost to play it, and only once it resolves it does it's effect and/or enters play. 
- During the main phase, when all cards/abilities resolve, the player who did not begin the stack (by placing the first card in dream) becomes the active player.
- All abilities are placed into dream just as cards are. Universal actions do not go through dream, however.
---
## Speed
Cards have an icon in the top left below the energy cost indicating what speed the card has.

#### Current speeds:
- Slow speed cards cannot be played during combat, and cannot be played while there are other cards/effects already in dream.
- Fast speed cards can be played during combat, and can be played while there are other cards/effects already in dream.
- ∞ speed cards can be played during combat and can be played while there are other cards/effects already in dream. All ∞ speed cards and effects are always placed above and resolved before any non ∞ speed effects. No player can take actions while they are in Dream, and they do not affect which player is or becomes the active player (if you play an ∞, you remain the active player and can continue playing cards).
#### More info:
- Taking any action slower than ∞ speed causes the other player to become the active player.
- You may commit multiple non ∞ speed cards at once, although speed rules still apply, and you must choose an order for the cards to be placed into dream. 
	- When doing this, if there are no cards already in dream, you are able to play a slow speed card as the bottom card, and commit fast speed cards along with it on top of it (the slow speed card must always be on the bottom though, so you cannot play more than one at a time).

---
## Channel System
All cards in hand can be channeled face up into the channel zone at ∞ speed any time you are the active player as a universal action. Channeling cards is primarily for increasing your source devotion to fulfill source requirements, and getting rid of cards you don't want to replace them with new ones at the end of the round.
- During the draw phase, your channeled cards will be recycled

---

## Round Phases
1. Pre round
	1. If it is not the first round of the game, the player with the most cards in hand becomes the first player (tie broken by who has the most total offense among their units, if that is tied, the player who began as the second player in the previous round becomes the first player.)
	2. Each player gets 1 additional energy counter
	3. Each player gets 1 energy for each of their energy counters.
	4. Each player unflips all their flipped cards.
	5. Move to next phase
2. Round Start
	1. If an effect refers to round start, it happens here.
	2. Once all effects are resolved / there are no unresolved effects, move to the next phase.
3. Main phase
	1. The first player becomes the active player (unless otherwise specified).
	2. When both players pass in a row while there are no unresolved effects, move to the next phase.
	- This is the primary phase where players actually play the game, along with combat which players can enter from the main phase.
4. Round End
	1. If an effect refers to round end, it happens here.
	2. Once all effects are resolved / there are no unresolved effects, move to the next phase.
5. Draw Phase
	1. The number of cards total in a player's hand, face up in their channel zone, + 1, (up to 10) becomes that player's maximum hand size for the round.
	2. Each player puts all cards from their channel zone on the top and/or bottom of their deck in any order/combination (which cards go where is not revealed to other players, the quantity of cards put on top & bottom is.).
	3. Players draw up to their maximum hand size.
	4. Begin next round
- Combat phase
	- See "Combat"

If a phase/step does not explicitly make a player the active player, no player is active and therefore players may not take actions (such as playing cards).

---
## Combat
During the main phase, while you are the active player and there are no unresolved effects, as a universal action you may start an attack by declaring your attackers (you attack players, not their cards).

Combat phase outline:
1. Combat begins with the attacking player being active, declaring one or more attackers and committing any desired cards/effects to dream. After attackers are declared, any triggers/effects created are put into dream, however only ∞ speed effects are resolved.
2. Defending player becomes active, declares up to one unit to block each attacking unit, and commits any desired cards/effects to dream. After defenders are declared, any triggers/effects created are put into dream, however only ∞ speed effects are resolved.
3. If the defending player committed any non ∞ speed effects or blocked with one or more units, the attacking player becomes active. Otherwise, or after a player passes, all cards and effects in dream are resolved, then all combating units simultaneously strike (deal damage equal to their offense stat) the unit blocking/being blocked by them, and if they are attacking unblocked, strike the defending player.
4. Combat ends, return to the main phase, and the player who was attacking becomes the active player. 
Notes:
- You may attack up to twice per round.
- Both attacking and blocking causes units to flip.
- You cannot attack or block with flipped units.
- By attacking, the attacking player becomes the first player for the remainder of the round / until another player attacks.

---
## Starting the game
To start the game, randomly determine the first player. Each player shuffles their deck, (reveals & puts their starting location into the location zone if the format has one), and draws 6 cards. Players may put any number of cards from their hand on the bottom of their deck to draw that many cards. After both players have finished drafting their hands, begin the first round of the game.

---
## Card Semantics
See the Naming V2 sheet in the [Atnia Cards Sheet](https://docs.google.com/spreadsheets/d/1v2kB2lh71D9G-9cLPd3Aqkp0UxqjCQWOMH--ha0lmy0/edit?gid=947960253#gid=947960253) for info on words that appear on cards.


Here is some additional info:
- The brown symbols in the text box of cards are zone symbols. A zone icon may indicate which zones a card or effect can target, or which cards in what zones are relevant to it.
	- Reality - Rolling Hills
	- Memory - Tombstone
	- Void - Swirly galaxy thingy
	- Dream - Moon with zzz
	- Hand - Fan of cards
	- Deck - Stack of cards
	- Channel Zone - Hand with a magical swirl


---
## Kinds of game objects
- Card - Cards!
- Ability - Effects created by cards
	- Triggered ability - Occurs automatically when indicated by the card they are on. Is infinite speed unless otherwise noted.
	- Skill - Ability of a card that is activated by the player similar to playing a card.
- Universal Action - Actions such as passing, channeling cards, or entering combat, which are granted to players by the game rules rather than cards.
- Player health / life total
- 
---
## Extra Notes
- Damage dealt to cards in dream/reality is permanent (until they leave). 
	- If a card is given a defense buff, then takes damage, then the buff goes away, the damage is assumed to have been done to the previously buffed defense before the defense the card still has.
- Targets for cards are chosen as you play the card (as it enters dream), not on resolution. Same for abilities. The arrive ability is quite common and has specific rules surrounding it, that targets are chosen as you play the card if possible.
- The reality zone has a limit of 8 non location cards and 8 location cards (for each player). 
	- This is mainly to not have to handle an indefinite number of cards online, the exact number can change a bit. 
	- Online, locations can stack up on top over each other in a corner of the board or something, and not count towards the main board limit.
	- If a card would enter a full board, the player should be prompted to choose a card on the board to replace (in which case the old card is discarded as the new one enters), or allow the new card to be discarded instead.
		- There is not a clear answer for how the exact timing of this should work, and if the board is full whether the new card should enter and then be discarded or simply never enter in the first place. 

### Advanced notes on timing rules and dream:
- If during dream effect resolution one or more new cards/abilities are put into dream that are not at ∞ speed, resolution stops, and the player not in control of the new top most card/effect becomes the active player.
	- Maybe also: If new non infinite speed cards/effects are put into dream by an infinite speed effect and the active player passes, it does not cause them to resolve & instead the other player becomes active.
- If effects would trigger simultaneously, they are put into dream all at once, in order of, from top to bottom:
	- Method A (unsure which method to use):
		- Effects from the first player in the round above effects from other players. 
		- Top to bottom, triggers from cards in: Dream, Reality (combat zone before the rest), Memory.
			- Dream, top to bottom: Cards higher in dream to cards lower in dream.
			- Reality, top to bottom: Cards on the left side of a players reality zone to cards on the right side of their reality zone (units, then items, then locations).
			- Memory, top to bottom: Cards higher in memory to cards lower in memory.
	- Method B (no need for order/location of cards mattering in paper, has issues with multiple copies of the same card):
		- Top to bottom, triggers from cards x before cards y (use each lower bullet as a tie breaker for the one above it if needed):
			- Cards in Dream > Reality > Memory > Void
			- (Cards with) higher base speed > lower base speed
			- First player > 2nd player
			- Spells > Units > Items > locations
			- Higher base cost > lower base cost
			- Higher base defense > lower base defense
			- Higher source requirement > lower source requirement
			- Alphabetical order of card names
- If multiple effects that require targets to be chosen are put into dream simultaneously, targets must be chosen for the bottom most effect(s) first.
- New cards arrive in memory above cards already in memory.
- All new cards arrive in reality to the right of cards already in reality. Attacking and blocking does rearrange unit order, and at end of combat all attacking/blocking units return to the rest of the reality zone on the left of cards already there, in the same arrangement they were in combat.
---
# Some Random Card Examples

![[Pasted image 20240830203602.png|250]]

![[Pasted image 20240830205038.png|250]]

![[Pasted image 20240830205117.png|250]]

![[Pasted image 20240830205142.png|250]]

![[Pasted image 20240830212200.png|250]]

![[Pasted image 20240830205222.png|250]]

![[Pasted image 20240830205252.png|250]]

![[Pasted image 20240830205319.png|250]]

![[Pasted image 20240830205406.png|250]]

![[Pasted image 20240830205600.png|250]]

![[Pasted image 20240830205643.png|250]]

![[Pasted image 20240830205853.png|250]]

![[Pasted image 20240830210033.png|250]]

![[Pasted image 20240830210142.png|250]]

![[Pasted image 20240830210202.png|250]]

![[Pasted image 20240830210744.png|250]]

![[Pasted image 20240830210907.png|250]]

![[Pasted image 20240830211406.png|250]]


## Formats / modes and ways to play the game

These are all just potential ideas. All can be played in best 2/3 or best of one.
- Constructed: 40 total cards, max 2x of each card, 15 card sideboard??
- Draft. Just do a cube draft.
- Highlander: 80 cards, max 1x of each, featuring the *super cool draft pool!* There will be a universal pool of ~30 cards, all with no source requirement. This set of cards can rotate over time, perhaps weekly or monthly, hand picked and brand new cards selected for the pool. At the start of each match, shuffle the 30 card pool and create two {packs} of 10 (numbers not decided yet and must be tested) cards from the top, then draft 5 cards from those packs with your opponent. Do the same thing after game 1 and 2 (if you go to game 3) (no sideboarding) (you are required to put all the cards you draft into your deck) (this may have issues with location count since you are changing the number of non locations, we'll have to figure a solution to that out later). 




# Limited format that lacks a name but is the main one rn

Limited format for 2 players. It shares some characteristics with being given a preconstructed deck, but in practice is closer to drafting from a cube (The card pool in fact may be used for cube draft) as you play the game due to channeling + enhanced card selection, without requiring a lengthy setup or draft before playing.

You begin the game with 15 life instead of 20 in this mode. They also begin with Atnia as their starting location card (a location which counts towards all sources).

Start with 5 decks on the table, one for cards of each source, and randomly determine the first player. Player 1 will choose one of the decks to take 15 cards from, then player 2 will do the same, repeat 2 more times so each player has 45 cards*. The same deck can only be chosen 4 times total across all players*. Players are then given 10* "Explore!" cards, as well as 6* "See Beyond" cards for each different source deck they chose when selecting their 45 cards. Players then shuffle all of their cards (the 45 cards from the source decks, Explore cards, and see beyond cards), which then become that player's deck for the game.

The game then begins and is played as normal.

### Notes:
- The card pool should provide a variety of directions for players to go in archetype wise even within the same sources / combinations. This of course means that cards will be of varying use to players depending on what they are doing, and the existing channel system + see beyond cards should allow them to effectively 'draft' during the game and select for the cards they actually would like to use.
- The explore cards simply give players access to a consistent number of exploration effects to get enough locations. They may at some point be replaced by just having more cards with Exploration text.
- The See Beyond cards when channeled are voided and allow you to look at the top 2 cards of your deck, rearrange them (and put them on the bottom of your deck if you like), then draw a card. This is to emulate the benefit of playing multiple sources in constructed, higher card quality.

### Notes for paper/online:
In paper, after a match has been played, players should go through their cards and separate them back into their original piles. For cards that have multiple sources, they should go in the pile of the source that is on the top left of the card border.

\* These numbers can be adjusted for the video game version as they were selected largely for paper play where there is a limited number of physical cards and the more you use the longer resetting the game takes. Online one player taking cards doesn't need to mean the other player can't have the same card, although the picking process should still be a back and forth thing so one player doesn't have a large information advantage during selection.

For online, I would start with the following numbers:
- 24 cards per pick (72 total, the total number of cards in a single source deck).
- 16 "Explore!" cards.
- 10 "See Beyond" cards for each source deck the player chose to add cards from to their starting deck.


---
# Warning: The following formats are sorta abandoned for being bad.
---
## Source Draft V2
Draft format for 2 players. You will draft your deck during the game (you do not bring your own deck, the format/mode has it's own predefined card pool). You begin the game with 15 life instead of 20 in this mode, and a deck of 5 'Explore' cards.

Begin the game with 5 decks (one for each source) on the table. It is known which deck is which source, but the decks themselves are face down. Randomly determine the first player. Players (beginning with the first player) choose a starting location. Once a starting location is chosen, other players cannot choose the same one.

Each player then takes a number of cards from the source decks, they have the choice of:
1. 10 cards from one deck.
2. 6 cards each from two decks.
3. 5 cards each from three decks.

From these cards players take 6 cards for their hand, and the rest of the cards can be shuffled into their deck (these will be the only cards in their deck for now), or burnt, in any combination of the two. Burnt cards are removed from the game and thrown in a pile.

The game begins and is played as normal, with the following modifications:
- At the end of each round before the draw phase, there is a draft phase. During this phase players take a number of cards from the source decks. They have the choice of:
	1. 8 cards from one deck
	2. 5 cards each from two decks
	3. 4 cards each from three decks. 
	- After taking their cards, players shuffle at least three cards from their draft pool into their deck, and burn the rest.
- The draw phase functions as normal, although players have the additional option to burn their channeled cards along with putting them on the top and/or bottom.

Note: For newer players, it is recommended to just pick a single source deck to draft from for your first game(s) as this reduces the quantity of cards you must look at and simplifies meeting your source requirements to actually play your cards.
## Mirror Format
Limited format for 2 players where you draft your cards for each round. Both players begin the game with an identical preconstructed deck of cards (one being the red deck and the other the blue deck). Each deck is a kind of mini cube, with support for a variety of strategies.

Instead of drawing cards normally at the end of each round and start of the game, players draft cards. Also, in mirror format, cards are channeled face down rather than face up.
## Source Draft / 5 deck thing
Limited/draft format for 2 players. Rather than each player having their own deck, 5 decks are shared by both players. The top card of each of these decks is always face up / revealed. When drawing a card, players may choose which deck to draw from, and can either draw starting with the face up card or skip the face up card and draw from the face down cards (sending the face up one to the bottom of the deck or removing it from the game).

Source requirements
- Option A: Players begin with a reminder card (does not exist in any zone) starting location that counts as 2 for all sources. Written another way: all source requirements are reduced by 2. 
- Option B (unused currently): Players do not have to meet source requirements when paying costs in this format.
	- If using this: Cards with Exploration would serve a different function

When starting the game, players draw their starting hands by drawing 6 cards. The top cards of the source decks are not revealed during mulligan.

Notes:
- If cards would be put on the bottom of a deck, remove them from the game instead **(this includes channeled cards & mulligans!)**.
	- If a source deck has 1 or fewer cards, shuffle in all cards of that source that were removed from the game.
- Whoever started the round as the first player draws first during the draw phase (they draw all their cards at once before the next player).
- If you would draw more than one card from a single deck at once, the cards you draw beyond the first are not revealed. 
- If a card says 'top x cards of your deck', or 'draw a spell', or similar, you may only use a single deck.

Optional / test rules:
- When drawing the starting hand you may only draw up to 3 from a single deck, & during mulligan you must reveal the cards and redraw from the deck of the same source.
- When getting cards with exploration abilities you get access to 10 two source locations instead of 5 single source ones.

### Ski Draft (questionable)
Both players take 10 cards from the top of their deck. Each player picks 1 card to keep, then passes the rest to their opponent. From pick 2 on, each pick players keep an additional card than the previous pick. Continue until all cards are drafted. Note: in this draft format, chosen/drafted cards are revealed as they are drafted.

- At the end of the round the following steps are carried out:
	- Each player may put any number of cards from their hand into their channel zone. The number of cards in a players hand and channel zone + 3, (up to 10) becomes that players' maximum hand size for the round round.
	- Each player puts all cards from their channel zone on the top and/or bottom of their deck in any order/combination
	- The draft is carried out, and all drafted cards are added to players hands. (Mirror format can be played with many draft formats, Ski Draft is recommended for players newer to the format, while [Hausman draft](https://luckypaper.co/resources/formats/housman-draft/) is worth trying at some point. Feel free to invent your own if you like.)
	- Players discard down (to the bottom of their deck) to their maximum hand size.

To begin the game, rather than drawing starting hands normally, start with a draft, with maximum hand size 5.

