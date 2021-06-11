# KotW-DIM-Wislist

## How to use:
### DIM
1. In DIM, open settings
2. Copy the raw.githubusercontent URL: 
	1. `https://raw.githubusercontent.com/J-Eisen/KotW-DIM-Wislist/main/wishlist`
3. Paste the raw link in your DIM wishlist
	1. If you want to keep other premade wish lists, separate them with a pipe "|".
  2. ![DIM Example](https://user-images.githubusercontent.com/30454448/120940746-cd11a800-c6ec-11eb-912b-c6585287b5e4.png)
4. Done!
### Little Light
1. Go to settings
2. Tap "Add Wishlist"
3. Copy the raw.githubusercontent URL: 
	1. `https://raw.githubusercontent.com/J-Eisen/KotW-DIM-Wislist/main/wishlist`
4. Give it a name & description
5. Tap "Add Wishlist"
6. Done!


## How to edit:
### Basics
1. You can edit the file directly by using the pencil icon in the upper right.
2. Grab your weapon rolls and add them in.
	1. [D2 Gunsmith](https://d2gunsmith.com/) allows you to create specific rolls & copy the DIM query to your clipboard. In this case, just copy and paste each roll you want.
	3. [Destinysets](https://data.destinysets.com/) gives weapon hash & a complete roll. You'll want to copy the portion of the url of the roll that starts with `dimwishlist:item=`
	4. [48klocs](https://48klocs.github.io/wish-list-magic-wand/fingerwave.html) will generate as many rolls as you'd like with comments. You will need the weapon and perk hashes, which you can get from Destinysets.
3. In the commit, add a quick summary of what you did. Like:
	1. Added Succession rolls for GMs -DeathByKttn
	2. Updated AA rolls on Deafing Whisper. AA works now. -DeathByKttn
	4. Made a really good sandwich -DbK
5. Done!

### Style Guide
#### Adding a New Item
Follow the following format:
`// Item Name
//notes:your_name (PvE/PvP/PvP&PvE/whatever) "Your specific comments go here." Reccomended MW: Masterwork
Item Rolls Go Here, One per line`
#### Adding Rolls to a new item
Add a space after the rolls that already exist, then:
`//notes:your_name (PvE/PvP/PvP&PvE/whatever) "Your specific comments go here." Reccomended MW: Masterwork
Item Rolls Go Here, One per line`
#### Adding a Note to an Item
`RollYouWantToAddANoteTo#notes:your_name (PvE/PvP/PvP&PvE/whatever) "Your specific comments go here." Reccomended MW: Masterwork`
Specific notes will override batch notes, so your note will appear.

## Websites
- [D2 Gunsmith](https://d2gunsmith.com/)
- [Destinysets](https://data.destinysets.com/)
- [48klocs](https://48klocs.github.io/wish-list-magic-wand/fingerwave.html)
