# Super-Robot-Wars-3-Randomizer-AGTP-2.0-patch
Creating a randomizer in javascript for Super Robot Wars 3. 

I am renewing interest in programming and likely going in well over my head :)

The goal of this randomizer is to eventually randomize almost everything that can occur in Super Robot wars.

First goal is basic; Which pilots and robots you have access to, enemy pilots for the map, enemy robots, and their positions on the map.  I already have a rather hefty notepad file filled with various important bits of the ASM code ( disorganized as thats how I am ) to do the above.
Second goal is creating the website and javascript that can take the patched file and create a new SNES file that can be opened by an emulator or loaded onto a flash cart.  Please note I do not own a flash cart.  I can't troubleshoot should you try to put the rom on one.

Once I get a working basic randomizer, I will start adding options for pilot statistic randomization, possibly creating a flow of which robots become first available, having enemy pilots scale with scenario ( So you aren't forced to fight Judau-basically superdodgy with high power-, for example, on scenario 1 with characters like Ryuu who have some of the worst stats in the game ), possibly creating interesting scenarios where sometimes enemies just don't act the way they should, how quickly enemy pilots activate, what weapons the robots have access to, the base stats each robot has access to, possible leave/join flags being played with, free roam of pilots ( or tightening up existing restrictions ), Cash generation, experience generation, amount of exp per level, perhaps even changing up how the maps themselves work, how strong defensive tiles are vs. open terrain, spirit cost and which pilots have access to which spirits, and lastly ... the most important modern features Super Robot Wars has; the ability to refuse to commit to an attack!

If I manage to get a good number of my plans realized, I will also try to look into making cursor movement and some other things faster.  This may not be an easy thing however as this would require restructuring inefficient ASM code.  Trust me, I've looked and dealt with the data in there already.  Some things just plainly do not make sense.
