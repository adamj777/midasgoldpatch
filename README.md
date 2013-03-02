midasgoldpatch
==============

mIDasGold Patch.txt File

To help convert a Tekkit Classic v3.1.2 server to Tekkit Lite v0.5.7 server. 
Tested with mIDasGold v0.2.4 with Additional BuildCraft Pipes Fix Plugin by havocx42

mIDasGold:
https://code.google.com/p/midas-gold/downloads/list

Invisible BuildCraft Pipes Fix (A mIDasGold Plugin):
http://forums.technicpack.net/threads/how-to-convert-tekkit-classic-world-to-tekkit-lite.34915/page-7#post-326855

I created this file because I found none of the patch.txt files linked on the forum thread to be 
sufficiently effective. Since I am running "out-of-the-box" versions of Tekkit Classic server and 
Tekkit Lite server, I thought the community could benefit from this as well.

The file has been hand-crafted to cover as much of the two server applications' content as 
possible. I have tested it against my test servers and made tweaks where I found them. Of course,
my world does not use every possible block and I don't have time to test all functions of all 
plugins included in Tekkit Lite. So, I hope folks will contribute when they find additional items 
to be included in the file.

Where items were removed from the game, in some cases, I replaced the item with an item of similar 
utility and value. (i.e. Dark Matter Hammer becomes Diamond Hammer.) I was not thorough with this 
so, feel free to make your own suggestions.

Some items have been removed from overworld and placed in the Nether. And some new ores have been 
added. Ferrous ore is found in the world but Lead ore drops from smelting Silver ingots. Sapphire
and Nikolite have been restricted to the Nether. So, I translate Nikolite ore to Silver ore in 
the Overworld and Sapphire to Ferrous ore. (More silver is needed for Factorization's Lead items. 
Ferrous ore would otherwise not appear in the Overworld until new chunks were generated. While
the quantities may not be accurate, this at least gives you a start from your existing world.

The changes in the previous paragraph work well for my server because we had not ventured far into 
the Nether. So, I am regenerating the whole world, which will give us access to all the new ores in 
their appropriate proportions. If you have an extensive Nether world, the above changes may need to 
be further tweaked. You may also want to take a closer look at all the Nether ore values between 
Classic and Lite to see if any custom changes can be made there as well.

I inserted 1:1 relationships (no change to the block ID) where I was uncertain if a change was 
necessary and could not test. So, if you see one of these entries, it is purposeful and might be 
a place to focus on finding a suitable replacement value.

Hope this is useful to some of you... Enjoy!

Adam
