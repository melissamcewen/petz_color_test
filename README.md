
# Petz Color Test
![CleanShot 2021-06-11 at 18 30 58@2x](https://user-images.githubusercontent.com/1251094/121757953-0da26480-cae5-11eb-9bf4-68b6e48c9370.jpg)

A way to test color preferences in Petz 4.

[Reflet](https://reflettage.wixsite.com/yabiko/) discovered that there are certain adjectives in .toy files that describe properties like color and flavor. Petz hackers speculate that individual Petz may have color preferences. Like they may prefer red toys or yellow toys. Now here's the important thing: the color the Petz perceive is based on the code, not on the picture of the item. So an item can appear "red" to us, but unless you change the adjective in the code ([see this guide by gyiyg here](https://gyiyg.neocities.org/itemhextut.html), Petz will perceive it as the color of the toy it was created from. For example, I can copy the original tennis ball and replace the default filmstrips with a red ball ([using Tinker](https://www.sherlocksoftware.org/page.php?id=15)], but the pet will still perceive it as a "yellow toy". 

value	color
0	white
1	black
2	red
3	green
4	yellow
5	blue
6	purple
7	pink
8	orange
9	brown
10	grey
11	clear/glossy = the rainbow colored ball



This repository contains tennis balls hexed to be all the different colors both in apperance to us and in the code (so the Petz perceive them as the right color). The idea is you can use them to test your Petz color preferences. Notice there is a new yellow one even though the original tennis ball is yellow. That's because your pet may have been trained with the original tennis ball and have a bias towards it. The new yellow one will be new to them.

To experiment:

1. put out all the colored ballz
2. bring out a pet
3. move your cursor outside the window and do not interact with the pet
4. note which ballz your pet prefers
