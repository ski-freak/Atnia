---
title: Card Game Testing Info
tags: 
aliases: 
enableToc:
---
Info on current testing method
1. Download [Cockatrice](https://cockatrice.github.io/) and install it (I used the portable install)
2. Go to the [Delta Cockatrice Repo](https://github.com/ski-freak/Delta_Cockatrice_Repo/tree/main). Here you can grab the latest set file and deck files.
	1. Grab the Delta_Set1.xml file and drop it in `Cockatrice\data\customsets` 
	2. Decks go in `Cockatrice\data\decks` 
3. If you haven't before, in Cockatrice, go to Card Database -> Manage Sets, disable all, then enable Delta_Set1.
4. Connect to the cockatrice rooster ranges server in the menu Cockatrice -> Connect. You may need to create an account first (Cockatrice -> Register to Server, you only need to enter username, email, and password).

Note: When cards are updated, you will need to go to Cockatrice -> Card Sources -> Delete Downloaded Images in the menus for them to refresh on your client.

If you make your own decks, you can send them to @skifreak to be added to the repo.