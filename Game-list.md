# Note about this list
This isn't meant to be a replacement for ProtonDB or any site that measures performance under specific games. This is meant solely to show my experiences on getting a game working. I will update this list as I either experiment more, or try different games out.


# Call of Duty: WWII
This game has been really iffy. Using GloriousEggroll versions of Proton, I still can't get the game to boot; splash screen and then crashes, sometimes just nothing. Disabling ESync and FSync doesn't help in this case. However, I was able to get the game to boot using the WineSteam runner in Lutris under Wine-staging 6.7. No further testing has been done.

# Final Fantasy XIV
The normal launcher boots under the first Lutris installer script; you have to be in legacy, or else the launcher will be stuck on the game logo. Haven't tested the game yet. Open-source fast launcher encounters a rundll32 error, and will crash after some time downloading the game. No further testing or tweaks done; all on Lutris 6.2 x64

# osu!
This runs fine; changed Wine version to 6.7-staging and still runs okay; has some random crashes here and there, but is still very playable. DXVK and FSync recommended; having ThePoon's audio latency patch helps as well. Offset is all up to the PC, but usually negative helps; audio compatibility mode doesn't seem needed for me, although I have yet to further test to see if it stops the crashes. Input latency is much lower here.

# Overwatch
Lutris script installs Battle.net, which has some weird graphical issues I haven't really sorted out. DXVK and FSync used; game installs fine. You have to let the game generate shader cache to get it to run properly; otherwise, game works perfectly fine for me.

# Battlefield V 
Lutris script does the trick; installs Origin, and you have to download the game yourself. The game will stutter on first map load for caching. After that's taken care of, should run fine. Essentially, it's like DX12 in Windows 10. Just leave it in DX11; you'll save a headache, and a performance increase. Game runs better in Linux than Windows from my testing, and plays very well. 

# Path of Exile
Runs right out of the box on latest Proton version; nothing else to be said. Vulkan is probably ideal since you'll be translating DX to Vulkan under DX11.

# Cyberpunk 2077
Got to the menu on this; haven't tested further. Menu feels fine so far, although I do know that ray tracing will not work under DXVK, be warned. Was going to install control tweaks before I tested further; will update later.

# Puyo Puyo Tetris 2
Game runs fine; although I had some issues with text on my first launch. A reboot fixed the issue. Latest Proton.

# uno!
Ubisoft's launcher makes this a royal pain in the ass; their servers were having issues at the time, but I have yet to test the game. Will update when I have more.

# Call of Duty: Infinite Warfare
I used Glorious Eggroll's Proton 6. Cancel shader caching; you'll be there all fucking night, and it won't do much from my testing. Only have tested Zombies in Spaceland, but it ran fine after the map was loaded in for a minute or so. Still more to test.

# Among Us
This runs fine. No tweaks needed.

# Call of Duty 4: Modern Warfare
It ran fine, only issue I had was that I needed CoD4x to play just about any server. Haven't installed it to try it out, there should be some servers that will auto install it for you.

# Call of Duty: World at War
Game wouldn't let me make a profile to play, so there isn't much testing I've done. May try it under WineSteam to see how it runs.

# Games that I know will not work due to anticheat or other odd dependencies (will update):
- MapleStory
- Phantasy Star Online 2
- Destiny 2
- Planetside 2
- Tom Clancy's Rainbow Six Siege
- Vindictus
- Elsword
- Dragon Nest
- Black Desert Online
- Apex Legends
- Fortnite (I'm not testing this, don't even bother asking)
- Paladins
- Realm Royale
- Call of Duty: Warzone (Modern Warfare 2019 included)
- Call of Duty: Black Ops Cold War
- Ring of Elysium
- SoulWorker
- TERA

These games may be removed from the list in the future depending on if I either made a mistake on adding them, or if there's some new discoveries.

# Games I installed that I need to test:

- Battlefield 1
- Battlefield 4
- Ni No Kuni: Wrath of the White Witch Remastered
- Fe
- Tales of Berseria
- Battlefield: Bad Company 2

# Games I may test in the future:
- Battlefield Hardline
- DOOM (2016)
- Horizon Zero Dawn
- I am Bread (god help me now)
- Metal Gear Rising: Revengeance
- NieR:Automata
- Quake Champions
- Secret World Legends
- The Elder Scrolls IV: Oblivion
- The Elder Scrolls V: Skyrim Special Edition
- Touhou Endless Dream
- Call of Duty: Black Ops II
- Call of Duty: Black Ops III
- AdventureQuest 3D

# If there's any games you'd like to see me test, please DM me on Twitter @katja_iikosu