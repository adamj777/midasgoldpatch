midasgoldpatch
==============

mIDasGold Patch.txt File

To help convert a Tekkit Classic v3.1.2 server to Tekkit Lite v0.5.7 server. 
Tested with mIDasGold v0.2.4

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

I inserted 1:1 relationships (no change to the block ID) where I was uncertain if a change was 
necessary and could not test. So, if you see one of these entries, it is purposeful and might be 
a place to focus on finding a suitable replacement value.

KNOWN BUGS:
I still have not figured out how to get Buildcraft Pipes to translate. After converting, my server 
exhibits symptoms of the infamous "invisible pipes" syndrome. I believe this is because pipes 
employ a little more sophistication than simply adding/changing block/item IDs. I can see what is
happening with NBT Explorer but i do not know where to address the problem. It may be something 
that darkhoernchen can address in the mIDasGold java program but i am not a programmer by trade so 
I couldn't say. It looks like a generic block ID is used for all pipes and then a "PipeID" field is
used to specify the type of pipe. The IDs that are exported in the Dump file for Tekkit Lite are 
accurate but they do not appear be block IDs. They are in the PipeID field.

Hope this is useful to some of you... Enjoy!

Adam
