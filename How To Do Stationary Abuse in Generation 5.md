# How To Do Stationary Abuse in Generation 5 (EmuAbuse)

#### Things To Download
- [Latest Build of RNG Reporter](https://ci.appveyor.com/project/Admiral-Fish/rngreporter/build/artifacts)
- [DeSmuMe Dev Build](https://sourceforge.net/projects/desmume/files/desmume/0.9.11/desmume-0.9.11-win32-dev.zip/download)
- Lua .dlls
  - [x86 .dlls](https://www.dropbox.com/s/2o4hdphn7j9z349/lua-dll-x86.zip?dl=0)
  - [x64 .dlls](https://www.dropbox.com/s/t8yttukleqserzp/lua-dll-x64.rar?dl=0)
- Pokemon BW or BW2 .nds files (You can dump the carts yourself using a CFW 3DS with Godmode9)
- [The Lua Scripts corresponding to your rom's language](http://pokerng.forumcommunity.net/?t=56443955)
- [RunAsDate (Optional)](https://runasdate.en.softonic.com/)
- A Save

#### Things To Know
You can advance IVRNG Frames by walking 128 steps. (It will advance once for every Pokemon in your party.) PIDRNG Frames are advanced by Chatot Chatters, saving and NPC movement. 

#### The RNG Process
1. Searching for a target
- Open RNG reporter and go to Generation 5 Time Finder. 
- Set your IV Frames from 1 to 6. (Recommended) Also, make sure you set the Method as "IVs Standard Seed." The Encounter Type should be "Stationary Pokemon."
- Set the filters how you want. If you are not searching for a Shiny, setting the nature and/or checking the "Synchronize Frames Only" box will not do anything. 
- Hit Generate when you have set your filters
- If it has a required lead or is a Sync Frame (Indicated by the bold nature), you can put a Sync Lead to get a nature of your choice.

![example](https://snag.gy/JS7VQp.jpg)

2. Hitting the Seed
 - Open runasdate and input the time listed in Time Finder.
 - Hit "Run" and hold down the needed Keypresses. Ensure that you have hit your target seed.
    
3. Advancing Frames
- Similar to Generation 4 RNG, you can advance frames with Chatot's Chatter. Do be careful though, because NPCs will affect your PIDRNG Frame.

- Advance frames until you get to your target, then hit A and enter the battle. If you got your Shiny/target, congrats! If you didn't, proceed to the next step.

4. Finding your delay
- If you missed your frame, you will need to figure out how many frames you missed by. Go to the main RNG Reporter screen and select "Gen 5 PIDRNG." Put your Initial Seed in the "Seed (Hex)" box. Then, put the nature you hit and hit "Generate." If there are multiples of the same nature, you will need to find the PID of the Pokemon you hit. 
- Find out how many frames you missed by. So if you hit A on Frame 99 but got Frame 100, you should hit A 1 Frame early. Once you have done this, you will obtain your target Pokemon! Congrats!

