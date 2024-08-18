---
title: Card Game Patch Notes 5-21-2024
enableToc: 
tags:
---
I may make some pretty major changes to the resource/energy/mana system, as the mental load induced by the current one I'm starting to think is a major issue.

To explain a bit, currently channeling 1 card from your hand = 1 energy. This is all well and good, but it also means that each card you play is -1 energy you otherwise would have access to. So if you have 4 cards in your hand, you can play one 3 cost card, or two 1 cost cards. This creates an environment where when you look at your hand, it becomes much more complex to parse which cards you want to play, as which cards you are playing affects how much mana you have. It seems to require way too much mental gymnastics, so I'm suspecting we should just get rid of it in favor of something else. What that something else would be, I have some ideas, but we're going to have to test a number of them probably to see what works. I've kind of retroactively identified this problem as my biggest issue in our tests, even though I couldn't quite put my finger on it at the time.

Note: the changes shouldn't significantly impact software, at least with what I currently have in mind

---
After some testing on my own, I have updated the rules document in accordance with the above. 

This is how the rules doc is updated now, but it's again subject to change
-  Channeling cards no longer produces energy, and is only for source requirements & shipping cards you don't want.
- The game will give you an amount of energy each round, similar to hearthstone/lor. We are however keeping the cards such as claims/starting locations which give you more energy counters (mana crystals, haven't come up with a name yet).
- If you do not meet the source requirement for a card, you simply cannot play it. This is in contrast to how it was before, where if you did not meet the full numerical requirement you just had to pay energy equal to the difference. This is changed for the same reason as channeling for energy was changed, as described in the previous message.
- Channeling cards face up / face down has been reworked to work better with the now hard limits on whether you meet a source requirement. Now, you may channel a card face up as normal, and it will count to source requirements of it's source, but you may instead channel a card face down as a kind of wild card, that will count towards requirements for all sources. The cost is that cards channeled face down will not replace themselves at the end of the round (explained differently, you draw 1 fewer card at the end of the round for each face down channeled card).
