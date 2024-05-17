---
title: Card Game Info Dump Doc
enableToc: "true"
tags:
---
# Project Gamma Drafting Card Game / Custom Cube

- *This information is a work in progress*
- Some information in this document may be inconsistent or outdated as the project is actively being worked on.
- Anything in {curly brackets} is a temporary name. The vocabulary is kind of a mess currently as the direction of the project remains uncertain.
- This project currently exists in a sort of limbo between it's own game and a custom cube with it's own cards and rules.
- Project Gamma is a temporary name. The project is being merged/using the world/setting of birdsandbees' tabletop rpg project.
- You can find the card design spreadsheet [here](https://docs.google.com/spreadsheets/d/1RDuqokq3RVDQv1vOBgSlnQbRpQ1KFyX1tBaPVvDhRUk/edit#gid=1942849584).
- This is likely going to be first and foremost focused on creating basically a cube for drafting, since then only one person needs to have the cards for multiple people to be able to play the game, which is particularly important considering this will end up just being a print and play thing.

Project Gamma is a drafting and deck building card game for 2-8 players with a focus on varied, open ended deckbuilding, player agency, and interactive back and forth gameplay. It can be played as either a cube draft or constructed with decks made by players before the game.

In games you will play units and attack your opponent to reduce their life to 0 (starting at 20), but within this there is a lot of room for different strategies! The game is played in a dynamic shared round system, and seeks to reduce non-games to a minimum. You will look to leverage hidden information, tempo, and card advantage to overcome your opponent and win the game.

The game takes place in Atnia, the setting of birdsandbees' Tabletop RPG. A very short briefing on it is [here](https://ski-freak.github.io/Atnia/main/World-Info/Google-Docs/Misc/Bits/Atnia-One-Pager). 

# Rules for playing the game:

### Shared Round
During each round players will take turns playing cards and taking actions. These actions include:
- Pass - When both players pass, if cards are being played, all cards resolve, and if no cards are being played, move onto the next step/phase of the round. Everything basically revolves around this double pass system, both players pass, then everything resolves and/or you move to the next step/phase.
- Play a Card or Ability - See "Playing Cards".
- Attack / Enter Combat - See "Combat".

### Round Phases:
1 - Round Start (unflip, beginning step)
- Unflip all your cards in play.
- If an effect refers to the start of the round, it happens here.
2 - Main phase
- Players take turns taking actions.
3 - Round End
- If an effect refers to the end of the round, it happens here.
- Do end of turn things, then discard down to max hand size and start the next round.

### Combat:
During the main phase while you have priority and there are no unresolved effects, you may start an attack by declaring your attackers. You may only attack twice per round.

Combat phase outline:
- Step 1 - Combat begins with the active player declaring one or more attackers. After attackers are declared, all triggers created are put on the stack/dream, however, no player is given priority and only triggers at {infinite} speed are resolved. Then move to step 2.
- Step 2 - Defending player declares up to one blocking unit for each attacking unit. After defenders are declared, all triggers created are put on the stack/dream, however, no player is given priority and only triggers at {infinite} speed are resolved. Then move to step 3.
- Step 3 - The attacking player is given priority. After a double pass occurs, the stack/dream is resolved. Then all battling units deal damage equal to their offense value to the unit blocking/being blocked by them, and if they are attacking unblocked, to the defending player.
- End of combat.
Notes:
- Both attacking and blocking causes units to flip, and you cannot attack or block with flipped units.
- After combat, the game returns to the main phase and the player who was defending is given priority.
- By attacking, the attacking player becomes the first player for the remainder of the round / until the other player attacks.

### Zones:
- Deck - Your deck of cards.
- Hand - Your hand.
- {board/battlefield?} - All cards that are currently in play live here.
- Memory - When cards are destroyed or discarded, they go here. It's the discard pile.
- Void - Zone used for some things.
- Dream / The stack - Zone for cards currently being played and not resolved yet.
- Channeled cards zone - Zone cards go after being channeled.

### Sources 
Similar to the colors in magic. Currently they are: Arca, Eminus, Material, Old World, and Zelor (although some of these names may be subject to change.)

### Card Types:
There are multiple card types:
- Unit - Units have offense stat in addition to their defense stat, and can attack and block.
- Claim - The first claim you play each round costs 0. All claims have `"<speed%> Arrive<board> and Round Start: +<resource1>"`.
- Item - Items cost `<resource1>` less to play for each of your claims. 
- Spell - Spells do their thing on resolution, then are put into memory.
(Some cards will also have subtypes, but these do not necessarily have any rules significance)

All cards have a numerical Resource cost, Source requirement(s), and Speed value, as well as a Defense stat.

### Playing Cards:
To play a card, you must meet it's source requirement (for each source (number) you are missing, the card costs `<resource1>` more to play), and pay it's resource cost. The card is then put onto the stack/dream, and priority is given to your opponent to either respond to it with their own card, or pass. Any new cards put into dream/the stack are put on top of other cards already there. Once both players pass, all cards in dream/the stack (unresolved cards) are resolved in order of top to bottom. When resolving, units, claims, and items are put onto the board, and spells are put into memory. To reiterate, you pay a cards cost to play it, and only when it is resolved it does it's effect and/or enters play. When all cards are resolved, priority is given to the player who did not begin the stack. 

Cards with a given speed number can only be played if there are that many or fewer cards and/or abilities currently in dream/the stack. You may however pay 3 life per number accelerated to speed up your card and be able to play it in response to other cards. 
- Note: if there are no cards currently being played / in dream/the stack, cards with negative speed values may be played without needing to be accelerated.

Notes on timing and dream/the stack:
- All `<speed%>` (infinite speed) speed effects are resolved before any others, cannot be responded to by any player, and do not affect who has priority.
- All effects trigger simultaneously are put onto the stack/dream all at once, from top to bottom in order of:
	- Effects from the first player in the round above effects from other players. 
	- Top to bottom: Cards on the left side of a players board to cards on the right side of their board board (units, then items, then claims).  
- All combat strikes are processed left to right (from the attacker's pov). All new cards arrive in play on the right side of their area. Attacking and blocking does rearrange unit order, and at end of combat all attacking/blocking units return to the main play area on the left side, in the same arrangement they were in combat.
- If during stack resolution one or more new cards or effects are put onto the stack that are not at `<speed%>` speed, stack resolution stops, and priority is given to the player not in control of the new top most card/effect.

### Resource & main card draw system:
- All cards in hand can be channeled into the channel zone to produce 1 resource.
- At the end of the round the following steps are carried out:
	- Each player may put any number of cards from their hand into their channel zone. The number of cards in a players hand and channel zone + 2, (up to 10) becomes that players' maximum hand size for the round round.
	- Each player puts all cards from their channel zone on the top and/or bottom of their deck in any order/combination
	- Players draw up to their maximum hand size.
- Note: Channeling cards is done at `<speed%>` (infinite speed) (it cannot be responded to, but you may still only do it when you have priority).

### Starting the game:
To start the game, randomly determine the first player. Each player then shuffles their deck, (reveals their starting claim if the format has one), and draws 8 cards, keeping 5 and putting the rest on the top and/or bottom of their deck in any order. After both players have finished drafting their hands, begin the first round of the game, Priority starting with the first player as randomly determined. At each round start (before any steps or phases happen), the player with the highest total/combined offense of their units becomes the first player. If it is tied, the player who began as the second player in the previous round becomes the first player.

## Extra Notes:
- Cards can take damage when in dream or in play. When a card receives damage greater than it's defense stat, it is put into memory.
- 

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
Limited format for 2 players where you draft your cards for each round. Both players begin the game with an identical preconstructed deck of cards (one being the red deck and the other the blue deck). Different sources of resources don't exist in this format. Each deck is a kind of mini cube, with support for a variety of strategies.

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

---
# Old section explaining the reasoning for some of the things

it's incredibly outdated for the most part though, only part I can garauntee doesnt have old stuff or things I disagree with is the resource and draw system part.

In the second portion of this document, I will outline the reasons why everything is the way it is at the moment. This will essentially be an information dump on the game design side of things, rather than the information needed to play the game. This may be a bit of a mess unfortunately because there are a lot of thoughts and I haven't organized them before. If you have questions on anything here or absent, I have probably just forgotten to write it down in this markdown document so I'll be happy to fish out my reasoning from the past discord messages and supply it.

#### Resource system & pitching cards.
some reasons why this could be very cool:
- dead cards can be cycled without it being an arbitrary ability you can activate.
- similar to rummage draw it has the basic concept of skill by card selection, except here it's probably a lot cooler even. You throw out the cards you aren't using this turn in order to play the cards you do want to use this turn. Within that there is also a nice sequencing aspect if you end up playing multiple cards in the shared round, as you will want to hang onto some in case you need them depending on what your opponent does.
- you can have more consistency to your draws, such as hitting your claim drops since if you have more than one claim you can use your extra claim for mana by pitching it, then throw it on top of your deck to have again next turn.
- Alternatively if you really need to dig for some kind of card you can just throw all or a large amount of your pitched cards on the bottom, for a nice risk/reward.
- there is a cool hidden and available information aspect, since the cards you pitch for mana are revealed to your opponent obviously, and then you can put them on the top or bottom of your deck, so you will be able to kind of guess at what may or may not be in your opponent's hand still going into the next turn. You can even hang onto cards in your hand without pitching them to keep them completely hidden. All of this on top of being interesting to play around also has great potential for mindgames and bluffing, since you can purposely reveal a card, then throw it on the bottom and do something else for example. If this system increases bluffing in general compared to the rather minimal amount that exists in mtg and most of the other similar card games, that would be very cool.
- Theoretically by drawing more full hands / cards in general, your opening hand is less important, and so there will be fewer non games. You will be less likely to get unlucky with your hand multiple times in a row, than just getting an unlucky opener in mtg for example and then only having 1 draw a turn to get out of it. With a higher percentage of the deck drawn (or at least you have the option to) each game by each player, you're just more likely to get an average draw.

#### The shared round
The core of the shared round vs normal turn system is a simple trade off: the decision to hold up mana for your opponent's turn, or attempting to create a more dynamic turn system with more back and forth between players. We chose the latter. Ideally through this we can also create a dynamic where sometimes you want to be getting your important cards down early to make your play or attack before your opponent, or you may want to stall a bit, take some non committal actions, and see what your opponent does before committing to something. I believe this could be more interesting than just holding up mana for your opponent's turn. It also leads to more often having resources available during combat and when your opponent is doing things. As a side note, the decision to hold up mana or not is very all or nothing in magic usually, with a shared round, waiting a bit longer will be more of a granular decision, as the board state and information constantly shift it becomes a slightly better or worse decision to have waited.

Also gets rid of play/draw diff (mostly, hopefully) lol

#### Split cards
A large amount of cards are going to be split cards, basically anything that doesn't have too much text will be a split between two cards that are relatively simple (edit: anything that is very complex will probably just be split with a basic land). This allows for more choices and makes it easier to force decks into playing the kind of cards that make the game better and more interesting (namely different types of interaction). For example, you can include small interaction for the memory or stack, so that you don't need silver bullets. You can include combat tricks so that they will still be available even if they aren't powerful on their own. You can include interaction so that decks will incidentally have access to it even if they don't desire it as highly as cheap aggressive dudes or accelerants for a combo.

Split cards also could be a huge boon to cube/draft. I am sadly not very experienced in building cubes, but I believe having a critical mass of support for different kinds of strategies is important, which means making cards that are useful in multiple different kinds of decks. Split cards could be an *amazing* way to do this. A cube with say, 50-70% split cards, I would imagine could support more unique decks/archetypes and possibilities than one without them. One of the issues that more synergy heavy cubes run into is having to include cards that only work in one deck, we can solve that by designing cards to work in multiple areas and be more open ended, as well as by simply having 2 cards on each card 4head.

Split cards can also help limit cards that are very polarizing, and extremely powerful in some situations and useless in others, by giving them a sort of floor. They can also lead to interesting design spaces, such as one half being the same effect a bit better but only sorcery speed.

Split cards also can fill the role of many mechanics, for example kicker, flashback, basically 90% of magic mechanics can be templated as a split card, which in the context of a game that doesn't have a million sets yet that need to be themed around different things, is good.

#### Lands and resource inconsistency
The following is outdated, however, starting claim + the pitch/resource system fills the same role.

Lands in magic were a huge culprit for non games, however, lands are such a boon to deckbuilding that I think removing them and replacing them with a static track of mana is kinda boring. If you want to go for a system where you have the same amount of resources each round from the start or something, and then you get them in some other way, for example ashes uses dice and then you can change the dice for a small cost etc so it's pretty consistent, that's fine, but I wasn't really interested in doing that. Anyway as far as lands go, they make deckbuilding much better, they allow you as the deckbuilder to choose how you go into the different card colors/realms in a very granular way. I thought that fixing the mana screw aspect was very doable, and I am pretty sure I was correct. I ran the numbers on combining the starting claim with extra cycles/rummages, and if you have a deck of 1/3 lands, without spending any mana to dig you are something like 94% to hit your 3rd land drop even if you never mulligan, and 89% for 4th. This is in contrast to magic where under the same conditions even if you do mulligan 0, 1, and 2 land hands down to 5 card hands you are 88% t3, and 66% t4. I didn't do the actual math on if you were to mulligan a bit with the project gamma system, but making a quick judgment on the mtg numbers I would predict it would be about 98% t3 and 94% t4, assuming you don't spend any mana to cycle further. So yeah I consider the resource inconsistency issue fixed.

#### Hidden information
We think hidden information is a pretty core part of what makes these card games interesting. It goes beyond the obvious, creating information asymmetry is in a way why brainstorm is such a cool card. This is kind of why we wanted to make face down cards more of a core element.

#### Silver bullets.
Are very very very bad. horrible. they suck. The core problem that leads to needing silver bullets is balancing archetypes around being very powerful but using a weird resource like the memory. Combo has a similar issue, where often decks cannot interact with it. Basically, everything needs to be interactable from most decks in some capacity, so you aren't required to play silver bullets and pray, or just hope you win first and play solitaire.

#### Interaction
Every deck needs to be a combination of proactive and and interactive. Having aggro and combo decks that play 0 interaction gets old pretty fast imo, and we kind of need to force them into playing a combination of the two. I have spoken in the past about how LoR has a sort of midrange shift. This idea of this archetype shift concept is that most decks all just feel a bit more like midrange than you would expect, even if they aren't really midrange in the context of the game. I named it after this https://en.wikipedia.org/wiki/Redshift. Anyway this focus on interaction may lead to a sort of tempo shift, at least by some definitions of the archetype, which honestly I am pretty ok with. This interaction stuff is more relevant to constructed probably.

#### Combat
So, we wanted to make combat more dynamic and interesting. The combat system described above is what I came up with. It allows for combat to be a more back and forth endeavor, with decisions being made as the phase moves along rather than all at once from the attacker then defender. Overall the system as written right now gives the attacker a notable advantage, since you can send in your big guy and then if the opponent blocks it send in your little guys, but on the flip side the defender gets to leverage hidden information more significantly, for example by not blocking, letting the attacker finalize the attacks, then using a removal spell on their one big attacker. Also applies to other kinds of combat tricks and things, lots of niche interactions probably, hard to think through them all, but I would imagine it all works out in a similar fashion. Mostly just wanted to make combat more interesting and dynamic, so yeah.

#### Speaking of interaction: instant speed tricks / combat tricks
Combat tricks, whether they are buffs or just direct damage or other instant speed tricks, are kind of the core of what makes combat interesting in magic. Without this aspect of hidden information, combat becomes a simple math problem and deciding what will be best for you long term (the latter of which is meaningful to be fair). Thing is, tricks tend to just not be that powerful in magic and often you don't have many resources available during your opponent's combat (this is obviously different in the case of a shared round!).

#### The highlander ft. mid match drafting format
Something I wanted to attempt from the beginning is bringing the deckbuiding aspect into playing constructed. I already gave my thoughts on this when I first brought it up in the rules/information section, but yeah I think this is a really really good way of doing that. It could also be quite interesting as a high level format, as the best decks and strategies will shift slightly as the card pool constantly rotates. I think this is a really cool format idea, and if we do constructed at some point this is going to be the first way we do it probably, because I think it's really unique.

#### The realms and lore
So basically the lore is that you are some guy maybe a wizard or smth, and there are these different realms, right. Now in universe point of fighting isn't really a war, because that doesn't really make a ton of sense when you run into the same realm you are playing, but the idea is that there is some mcguffin that everyone in this world is after. (As a bonus, you could make the mcguffin as a physcal pin you hand out to people at the end of events like fnm for winning, could be a fun little way of tying a physical object into the universe. For more real life / lore crossover chatting, see birdsandbees' L5R opinions.) Anyway you will basically be playing claims from different realms, claiming the areas, giving you access to play cards from those realms. A more tangible flavor than mtg lands, I think. The realms as of the moment at least, are:

- You know what just look at the damn spreadsheet for this, it's easier [here](https://docs.google.com/spreadsheets/d/1RDuqokq3RVDQv1vOBgSlnQbRpQ1KFyX1tBaPVvDhRUk/edit#gid=1942849584)****.
- Anyhow the potential lore for the beginning of the lore could be that the monk realm held onto the mcguffin but then it got stolen and now it's out in the world and everyone is trying to get it. All of this lore stuff I kinda threw together to have something to work with, it's all pretty basic and I am not very good with lore, but it works well enough for now.

#### Card types
What I find interesting about the card type sand why i chose the ones to keep is pretty simple:
- Claims represent places
- units represent people/living things
- non units represent objects
- spells represent... spells
- You can also fit other things into this, for example legendaries represent unique characters.

#### Cube Draft design
Pasting the recent text blob I wrote in discord:

"With 7 realms we need to not spread the draft pool too thin for cubes. Having cards that span across multiple archetypes, and interesting cards that you can pick to shift the direction of your deck on their own may go a long way to giving a variety of options.

We could go a few directions, for example we could give each 2 realm pair a main direction to go in, and then have different cards or packages outside those realms that you can pick up to support or augment your strategy to your liking. It is worth noting that I would expect most decks to be aiming for 3 realms, or 2 + a splash, since there are more realms than magic colors, so either this idea will work particularly well or we should focus on 3 color pairs more. Assuming it does work, I think it could be quite nice. I really want the first and possibly main/only cube to have a variety of directions you can go, without spreading itself too thin, this would hopefully be a way to do that. I don't *really* want to just have everything be goodstuff but I also don't want it to be just picking a realm/archetype and going. We can also put build arounds in single colors or throw in dedicated 3 color strategies here and there if it fits.

Perhaps split cards can also help with this goal? They kind of let you include more cards within the cube, and go extremely far into the sort of cross polination of archetype support. Anyway fixing probably needs to be quite good, maybe we should even consider giving out some free duals or tris along with your allotted basics? if not we would need to put in some quite powerful lands."

Not sure if we should do 360 card cube or 540, probably we should make 360 to start with and then if the project survives past that make a 540 later.

#### Some stuff on the game as a whole
- We are overall trying to keep the vocabulary of everything fairly self explanatory. There are some more mechanics floating around than magic, but the goal is to make all the mechanics of the game and names of things as accessible as possible. Players should be able to be taught what something means, understand it, and then when the word is brought up again it intuitively references the learned concept. What this means in practice is things like simplifying the resolution of cards on the stack, and naming the memory the memory instead of the graveyard, for example (it removes one referential step, rather than going graveyard -> memory -> does what a memory does, you go memory -> ah yes i know what this means).
- The visual design of everything is going to be relatively minimal, clear, and concise compared to other card games. These mtg proxies I would say are pretty good examples of what I mean [exhibit a](https://cdn.discordapp.com/attachments/1056772454971871232/1132087283168850000/image.png) [exhibit b](https://cdn.discordapp.com/attachments/1056772454971871232/1132087266676850789/image.png). And ashes has a more stylized borderless look which is also interesting. [exhibit c](https://cdn.discordapp.com/attachments/1056772454971871232/1132602008835215380/image.png). That said, for the time being we are probably going to go for some simple drawings, and avoid any kind of border for easy printing and cutting out of cards.
- The stack is still overall a very good system for determining outcomes in complex situations.
- A rules support/question channel in a public discord would be nice, for people playing the game anywhere in the world to have a designated place to get clarifications on what things do.
- I wrote a whole thing on card distribution. You can find it [here](https://github.com/That-Ski-Freak/MarkdownPublic/blob/main/card%20game%20distribution.md).
- I don't view making this into an actual game (publishing it) as a reasonable possibility at least in the foreseeable future. It would be nice, but probably won't happen. What I plan on doing is releasing it on a website or something, having some amount of social media presence, and making it available to print. The ideal outcome would be if people just enjoy playing it as a cube, and people know about it even if I haven't told them directly, so it's not just people I know who play the game xd. 
- A really cool idea I had that would never work in an unpublished print and play game is this: each realm has a different art style for it's cards. I think this would be so cool.


#### Quick fire card design opinions
- Limit snowball. Having early cards that you always want to play asap and hope they stick and give a huge advantage is kind of questionable most of the time. Being able to play 1 and 2 drops in magic that draw cards or create resources every turn is kind of absurd.
- It's possible that everything could function on a sort of design system where you either get resource efficiency or card advantage, but not both on one card, and that could limit the snowball aspect. 
- activated abilities are kinda nice I think. mtg kind of drifted away from them over time, but I think they are still kind of interesting. They allow for on board tricks that change the 'rules' of the game in a way, are nice mana sinks, and overall require you to put more effort to get outcomes than just getting something every turn.
- Board clears will probably be somewhat limited compared to magic (they are a form of silver bullet, in a way), not much 'just destroy everything'. Things like pyroclasm or settle the wreckage are chill, but not supreme verdict.
- Overall I think we will move no questions asked interaction further up the curve, and leave more room for mana efficient interaction that actually cares about the text on the opposing cards. 1 mana will be niche or small interaction, 2-3 mana interaction will be a pretty common spot, and at 4 mana you can just yeet things (which is pretty costly, but in the end you will just more often end up using cheaper interaction instead unless you really need this which is fine).
- All realms need access to non board / stack interaction, even if it's not just counterspells. This could mean hand attack, other ways of interacting with cards being played, instant speed protection spells, etc.
- Combo decks are probably going to need to be a+b+c combo or engine combo, a+b is probably too consistent to get in this game. Again needs to be reasonably interactable as well.
- Formats like legacy and canlander are, I think, where magic as a game system really shines relative to other games. Having lots of stuff going on and cheap cards being played, but at least in fair matchups relatively long games, I think is very very nice. The main issue with formats like legacy though tends to be that unfair strategies are unbelievably powerful, and must be stopped with silver bullets.
- I think we could make legendary cards designed in a more similar way to how they are in lor than magic, where you can't play a second one if you have one in play, but they come with a spell you can play instead only when you have another copy on the board. Meshes well with the split card theming and removes confusion with the legend rule.
- The way mtg handles the color pie with primary secondary and tertiary mechanics is pretty good.




---
The following is outdated:
#### Cycling as a global mechanic
This came from both resource consistency and a choice making perspective. It began as simply replacing the draw step with a discard 1 draw 2, but was later changed to be an action when we moved to a shared round system. Being able to control the cards in your hand and rummage them away is a fairly relevant choice often, deciding which card is the least useful in your hand. You can also just dig for more claims or ship your extra ones to not flood (although I think non basic claims will mostly have split effects anyway, they will probably be relatively small though).

#### banking mana/resources
Something I really liked about lor that is often absent in magic is that you sometimes just want to do nothing. Banking mana also allows you to not be punished super hard for stumbling on your curve slightly, and also allows you to strategically do nothing to do more the next turn.

It also changes the balance of spell costs.
When it comes to being able to bank 2 resources, it kind of changes the balance of spells in an interesting way. Like if you start the game with 1, then you bank 1 on turn 1, then on turn 2 you can play a 4 cost spell. You've time walked yourself to ramp because you've banked the mana of course, but you did get to play a 4 cost spell. Now for a lot of spells that don't have a huge board impact this is kind of fine, like being able to play your 4 mana card draw spell on turn 2 if you do nothing isn't broken, but that isn't necessarily the case for more proactive spells. More expensive spells that are proactive would probably need to cost more relative to units, but it's kind of made up for by the fact that you can bank resources for them to get them down earlier, which I think is a nice dynamic. It also doesn't affect cheaper spells as much, which means they will probably be a little more mana efficient which I like.
#### Temporary memory
You my have noticed that cards only last in the memory a couple of rounds. This makes it a sort of recently played pile, and also should make it easier to stop graveyard related things. If you can prevent them from happening for a couple turns you don't have to worry about it anymore, rather than having to deal with anything in there as a forever looming resource. This also allows you to track only recently played cards in an easy way, for example a card could see if you have 3 or more spells in your memory. Not a hugely impactful change, but it's kind of interesting, I think.

### Banked resources:
You may bank up to 2 {mana} at a time. This mana may only be used to play spells. (not sure if we should allow any floating mana to just be added to the bank at the end of the round or not, in the end it's just whatever is simplest). The realm/color of the mana is preserved in the bank, it doesn't become realmless or wild card mana or whatever.


## face down cards

Another common theme on project gamma cards is that they can be played face down and then flipped later for an effect. It's morph.

- You may play cards with {morph} face down for 2 mana as a 2/2
- You may flip cards with morph in play at n time/speed by paying the morph/flip cost
- Cards exist that may allow you to put any card face down as a 2/2 (manifest)
- Cards without morph may be turned face up at n time/speed for their mana cost
- If a non permanent card would be turned face up, instead it is placed on the stack / non permanent cards are *played* from face down rather than flipped

face down cards leaving play are revealed as they leave play, and they have to be revealed at the end of the game if they are still in play as well, to prevent cheating