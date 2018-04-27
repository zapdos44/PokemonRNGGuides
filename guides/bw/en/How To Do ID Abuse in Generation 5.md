# How To Do ID Abuse in Generation 5 (EmuAbuse)

#### Things To Download
- [Latest Build of RNG Reporter](https://ci.appveyor.com/project/Admiral-Fish/rngreporter/build/artifacts)
- [DeSmuMe Dev Build](https://sourceforge.net/projects/desmume/files/desmume/0.9.11/desmume-0.9.11-win32-dev.zip/download)
- Lua .dlls
  - [x86 .dlls](https://www.dropbox.com/s/2o4hdphn7j9z349/lua-dll-x86.zip?dl=0)
  - [x64 .dlls](https://www.dropbox.com/s/t8yttukleqserzp/lua-dll-x64.rar?dl=0)
- Pokemon BW or BW2 .nds files (You can dump the carts yourself using a CFW 3DS with Godmode9)
- [The Lua Scripts corresponding to your rom's language](http://pokerng.forumcommunity.net/?t=56443955)
- [RunAsDate (Optional)](https://runasdate.en.softonic.com/)

#### Things To Know
ID Abuse is **NOT** manditory for Generation 5 RNG. Typically, it is used for Roamers/Stationary Pokemon to get better spreads quicker and/or for novelty. 

#### The RNG Process
1. Pandora's Box
- Open RNG reporter and go to Pandora's Box. Add the details you want and hit Search.
- I recommend that you hit "Search Entire Month" if you are looking for more than 1 thing. Since I want a specific PID to be Shiny and a TID, I will check that box.

![example](https://snag.gy/4CZfHc.jpg)

2. Hitting the Seed
 - Open runasdate and input the time listed in Pandora's Box. 
 - Hit "Run" and hold down the needed Keypresses. Ensure that you have hit your target seed.
    
3. Advancing Frames
- Similar to Generations 6 and 7, you will be advancing frames by constantly ~~having an identity crisis~~ saying "no" to the professor. Make a save state a few frames before your target.

![NO](https://snag.gy/kmCW2v.jpg)

- Advance frames until you get to your target, then mash A until you can check your TID. Chances are, you will get the wrong TID. If you do, proceed to the next step.

4. Finding your delay
- Similar to Generation 3 and 4, you will need to find your delay. Go back to Pandora's Box and fill in the needed infrmation on Seed Finder. Since I got the TID 50727, I will put 50727 in Pandora's Box and set the date you used. Hit "Find Seed Hit" and find out how far off you were from your ID. 
- My ID was on Frame 51, but I hit Frame 49, so I will hit A on Frame 53. 
![Frame](https://snag.gy/vdRQFU.jpg)

5. Advancing Frames (Again)
- Use your Save State and advance as many frames as needed. If your Save State is too late or early, you will need to re-advance all your frames. 

6. Enjoy your TID!
- An example of a successful ID Abuse:
![:D](https://snag.gy/JSBplD.jpg)
