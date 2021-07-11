# Note about this list
This isn't meant to be a replacement for ProtonDB or any site that measures performance under specific games. This is meant solely to show my experiences on getting a game working. I will update this list as I either experiment more, or try different games out.

# The Elder Scrolls V: Skyrim Special Edition
Game will run fine under Proton, but don't expect to get mods working. 

# Doom (2016)
Game works right out of the box (it's whitelisted with Proton), just go into settings and change the renderer to Vulkan.

# Battlefield 1
This is about the same as Battlefield V, in the sense that you have to play through maps to get DXVK shader cache going, otherwise it works perfectly fine.

# Call of Duty: Black Ops III
This game works okay with Proton, however you will need to rename (or delete, your call) any video folders for the game in order to do anything; this also applies for Workshop content. Game runs fairly well.

# Project Project Dxxx
This is a Project Diva sim, for those who don't know. You will get a "failed to load video" error when selecting a song, which in turn, prevents you from playing any song. Game isn't working on any version of Wine because of this error, and unfortunately, I'm not aware of any fixes at the time of writing this.

# Pandemic Love
This is the only VN on this list, since I ended up playing it on stream. Works right out of the box with Proton, no issues.

# Trailmakers
I've played a few hours of this with my girlfriend on latest Proton; zero performance issues, runs fine.

# SoulWorker
Anticheat throws an error using Wine. Yeah, not happening. ;3;

# Genshin Impact
Launcher runs, although you do have to install the game in the container folders; I couldn't store it on my storage drive. Game will be tested as soon as it's downloaded. Game does not launch from launcher, presuming due to some anticheat stuff. I'll come back to this another time, but it seems borked.

# Overcooked! All You Can Eat
This works perfectly out of the box with Proton; played it with my girlfriend for about an hour or so with absolutely no problems. 

# Etterna
There's a native Linux build you can compile yourself on your respective distro; I'm using Arch, and there does happen to be an AUR package that is maintained, but needs updating as it is borked at the moment. Currently if you build using the etterna package, you will get this:
![image](https://user-images.githubusercontent.com/83994731/118196140-1c2c2c00-b412-11eb-81e3-5aa6a72960a6.png)

AUR build is fixed for any Arch users; otherwise you will have to compile it yourself.

# Roblox
At the request of SleepyZaddo, I took a look at Roblox. Due to some anticheat measures they have in the client, Roblox Player will not open. Roblox Studio will, though. All in an attempt to get Robeats working :^)

Update: As of this writing (20th of June 2021) there has been a patch merged into Wine 6.11 that now allows you to use Roblox Player. It's not perfect, but it runs now. I don't have the details, but for more info please check out Roblox on Linux wiki page. It's an easy search, and I'm not embedding the link at the moment.

Update 2: After running through tests, the best way to run this is to use Grapejuice with Wine 6.11. For the best performance, go into the FFlag editor and enable "FFlagDebugGraphicsPreferVulkan" which will force the game to run under Vulkan. For the FPS unlocker, download the executable for it, and open Wine Explorer and run it through there. Game is working now.

# Call of Duty: WWII
This game has been really iffy. Using GloriousEggroll versions of Proton, I still can't get the game to boot; splash screen and then crashes, sometimes just nothing. Disabling ESync and FSync doesn't help in this case. However, I was able to get the game to boot using the WineSteam runner in Lutris under Wine-staging 6.7. No further testing has been done.

Update: the game has booted using Proton 6.8-GE-1. After selecting an option in the menu, the game will be stuck on a loading screen. No further testing yet done. (16th of May, 2021)

Update #2: Disabling Esync allows you to get through the menus. Loaded into a private match and was some stutter; although shader caching was turned off in game. More testing needs to be done, but looks promising.

# Final Fantasy XIV
The normal launcher boots under the first Lutris installer script; you have to be in legacy, or else the launcher will be stuck on the game logo. Haven't tested the game yet. Open-source fast launcher encounters a rundll32 error, and will crash after some time downloading the game. No further testing or tweaks done; all on Lutris 6.2 x64

# osu!
This runs fine; changed Wine version to 6.7-staging and still runs okay; has some random crashes here and there, but is still very playable. DXVK and FSync recommended; having ThePoon's audio latency patch helps as well. Offset is all up to the PC, but usually negative helps; audio compatibility mode doesn't seem needed for me, although I have yet to further test to see if it stops the crashes. Input latency is much lower here. If you're going to use a tablet, OpenTabletDriver is your best bet; tested on a Gaomon S620, a XP-Pen G640 rev B, and a Wacom CTH-680. If you're on a high refresh rate monitor, make sure you disable compositing in your DE so the game will not cap the visual framerate.

# Overwatch
Lutris script installs Battle.net, which has some weird graphical issues I haven't really sorted out. DXVK and FSync used; game installs fine. You have to let the game generate shader cache to get it to run properly; otherwise, game works perfectly fine for me.

# Battlefield V 
Lutris script does the trick; installs Origin, and you have to download the game yourself. The game will stutter on first map load for caching. After that's taken care of, should run fine. Essentially, it's like DX12 in Windows 10. Just leave it in DX11; you'll save a headache, and a performance increase. Game runs better in Linux than Windows from my testing, and plays very well. I will not be testing this game any further. In memory of Devin.

# Path of Exile
Runs right out of the box on latest Proton version; nothing else to be said. Vulkan is probably ideal since you'll be translating DX to Vulkan under DX11.

# Cyberpunk 2077
Got to the menu on this; haven't tested further. Menu feels fine so far, although I do know that ray tracing will not work under DXVK, be warned. Was going to install control tweaks before I tested further; will update later.

# Puyo Puyo Tetris 2
Game runs fine; although I had some issues with text on my first launch. A reboot fixed the issue. Latest Proton.

# uno!
Ubisoft's launcher makes this a royal pain in the ass; their servers were having issues at the time, but I have yet to test the game. Will update when I have more.

UPDATE: You can run this if you install Ubisoft Connect (UPlay, whatever) but if you go into a multiplayer game, you will crash your game and freeze everyone else's games. (Sorry, Matt.)

# Call of Duty: Infinite Warfare
I used Glorious Eggroll's Proton 6. Cancel shader caching; you'll be there all fucking night, and it won't do much from my testing. Only have tested Zombies in Spaceland, but it ran fine after the map was loaded in for a minute or so. Still more to test.

# Among Us
This runs fine. No tweaks needed.

# Call of Duty 4: Modern Warfare
It ran fine, only issue I had was that I needed CoD4x to play just about any server. Haven't installed it to try it out, there should be some servers that will auto install it for you.

UPDATE: If you connect to a server running CoD4x, you will get an error telling you to log into Steam before connecting. So, in this case, the game is kinda borked.

# Call of Duty: World at War
Game wouldn't let me make a profile to play, so there isn't much testing I've done. May try it under WineSteam to see how it runs. 

UPDATE: will need to try Plutonium, as apparently this is the best way.

# Battlefield 4
Game works fine using the installer under Lutris for Origin and DXVK setup (using default Lutris-6.1 prefix). You will need to run the following commands to get ping working in game, otherwise you will get kicked from any server with Punkbuster:

    sudo setcap cap_net_raw=epi /path/to/lutris/wine-preloader

    sudo setcap cap_net_raw=epi /path/to/lutris/wine64-preloader

    sudo setcap cap_net_raw=epi /path/to/lutris/wineserver
    
If you're using a custom Wine version (staging or wine-tkg in my case), you can fine the preloaders and wineserver in /usr/bin

To boot the game via Battlelog, you have to spoof your active user agent in your web browser to be that of a Windows version, otherwise, Battlelog will say that you do not have the game installed. 

# Heroes and Generals
No matter what Proton or Wine version you use, upon starting the game, you will receive an error, stating: "Please start the game through Steam." This isn't anything new, and has been going on for over two years. This isn't working, and I saw that it uses BattleEye, which probably explains this.

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
- TERA
These games may be removed from the list in the future depending on if I either made a mistake on adding them, or if there's some new discoveries.

# Games I installed that I need to test:

- Ni No Kuni: Wrath of the White Witch Remastered
- Fe
- Tales of Berseria
- Battlefield: Bad Company 2

# Games I may test in the future:
- Battlefield Hardline
- Horizon Zero Dawn
- I am Bread (god help me now)
- Metal Gear Rising: Revengeance
- NieR:Automata
- Quake Champions
- Secret World Legends
- The Elder Scrolls IV: Oblivion
- Touhou Endless Dream
- Call of Duty: Black Ops II
- AdventureQuest 3D

# If there's any games you'd like to see me test, please DM me on Twitter @katja_iikosu
