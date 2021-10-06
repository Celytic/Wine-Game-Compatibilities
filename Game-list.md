# Note
This list exists purely for documentation of getting Windows games (or attempting to get them) to run on Linux using software such as Wine and other dependencies for performance. This is purely my experience, and I may have tips to get things working in this thread.

As of typing this update (6th of October 2021), EAC and Battleye now have Linux compatibility, but has to be enabled on a game-by-game basis. Xigncode3 also may be working soon; no word on nProtect GameGuard or Vanguard. So do be aware that once it's enabled on certain games, I will try to see if they work.

# If you would like me to test a game, submit an issue ticket and I will check the game out.

- [Flash Flash Revolution](#flash-flash-revolution)
- [New World](#new-world)
- [Dark Souls Remastered](#dark-souls-remastered)
- [Guild Wars 2](#guild-wars-2)
- [Swords of Legends Online](#swords-of-legends-online)
- [The Greatest Penguin Heist of All Time](#the-greatest-penguin-heist-of-all-time)
- [Titanfall 2](#titanfall-2)
- [CastleMiner Z](#castleminer-z)
- [The Elder Scrolls V: Skyrim Special Edition](#the-elder-scrolls-v--skyrim-special-edition)
- [Doom (2016)](#doom--2016-)
- [Battlefield 1](#battlefield-1)
- [Call of Duty: Black Ops III](#call-of-duty--black-ops-iii)
- [Project Project Dxxx](#project-project-dxxx)
- [Pandemic Love](#pandemic-love)
- [Trailmakers](#trailmakers)
- [SoulWorker](#soulworker)
- [Genshin Impact](#genshin-impact)
- [Overcooked! All You Can Eat](#overcooked--all-you-can-eat)
- [Etterna](#etterna)
- [Roblox](#roblox)
- [Call of Duty: WWII](#call-of-duty--wwii)
- [Final Fantasy XIV](#final-fantasy-xiv)
- [osu!](#osu-)
- [Overwatch](#overwatch)
- [Battlefield V](#battlefield-v)
- [Path of Exile](#path-of-exile)
- [Cyberpunk 2077](#cyberpunk-2077)
- [Puyo Puyo Tetris 2](#puyo-puyo-tetris-2)
- [uno!](#uno-)
- [Call of Duty: Infinite Warfare](#call-of-duty--infinite-warfare)
- [Among Us](#among-us)
- [Call of Duty 4: Modern Warfare](#call-of-duty-4--modern-warfare)
- [Call of Duty: World at War](#call-of-duty--world-at-war)
- [Battlefield 4](#battlefield-4)
- [Heroes and Generals](#heroes-and-generals)
- [A Dance of Fire and Ice](#a-dance-of-fire-and-ice)
- [Golf It!](#golf-it-)
- [TrackMania Nations Forever](#trackmania-nations-forever)
- [Metro Exodus Enhanced Edition](#metro-exodus-enhanced-edition)
- [Old School Runescape](#old-school-runescape)
- [Current list of games that I'm going to test (will be updated)](#current-list-of-games-that-i-m-going-to-test--will-be-updated-)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


# Flash Flash Revolution
A relic of the mid 2000s; the R3 engine has an exe file that works perfectly out of the box using the newer versions of Wine; currently got it running via 6.16. Plays better than osu!mania and Quaver.

# New World
No idea if EAC will be enabled on this, will update if it is.

# Dark Souls Remastered
I'll be testing this later, so this is to be filled.

# Guild Wars 2
Game plays fine; used Lutris script to install and play. Not a lot of testing, but will do more.

# Swords of Legends Online
To be filled; game boots and goes to main menu.

# The Greatest Penguin Heist of All Time
Penguins. Runs native, game is jank as hell and a lot of fun.

# Titanfall 2
Use the Lutris script to install it and let it cache shaders just like Overwatch; game will work fine and play well.

# CastleMiner Z
Game seems to run without issues; framerate is capped at 60. Not too much to report, game seems to work okay in offline singleplayer; haven't tested it in multiplayer; may add that later.

# The Elder Scrolls V: Skyrim Special Edition
Game will run fine under Proton, but don't expect to get mods working.

# Doom (2016)
Game works right out of the box (it's whitelisted with Proton), just go into settings and change the renderer to Vulkan.

# Battlefield 1
This is about the same as Battlefield V, in the sense that you have to play through maps to get DXVK shader cache going, otherwise it works perfectly fine.

# Call of Duty: Black Ops III
This game works okay with Proton, however you will need to rename (or delete, your call) any video folders for the game in order to do anything; this also applies for Workshop content. Game runs fairly well.
EDIT: Supposedly, 

# Project Project Dxxx
This is a Project Diva sim, for those who don't know. You will get a "failed to load video" error when selecting a song, which in turn, prevents you from playing any song. Game isn't working on any version of Wine because of this error, and unfortunately, I'm not aware of any fixes at the time of writing this.

# Pandemic Love
This is the only VN on this list, since I ended up playing it on stream. Works right out of the box with Proton, no issues.

# Trailmakers
I've played a few hours of this with my girlfriend on latest Proton; zero performance issues, runs fine.

# SoulWorker
Anticheat throws an error using Wine. Yeah, not happening. ;3;

# Genshin Impact
Game doesn't work; however installer works fine.

# Overcooked! All You Can Eat
This works perfectly out of the box with Proton; played it with my girlfriend for about an hour or so with absolutely no problems. 

# Etterna
AUR package. That's all there is to this.

# Roblox
Roblox only works on Wine versions 6.11 or newer, and the best way to configure this is to use a program called Grapejuice, which can be found with a quick search.
To get the most optimal performance, open the Roblox FFlag Editor, and enable FFlagDebugGraphicsPreferVulkan. This will improve performance significantly.

# Call of Duty: WWII
Game is iffy, and isn't really working in Multiplayer the last time I tried it; will need to set stuff up.

# Final Fantasy XIV
Game seems to work under XIVLauncher; official launcher seems to not work unless you use the legacy version. 

# osu!
Set this up with Lutris and use ThePoon's audio latency patch; if you're having audio distortion, enable Pulseaudio Low Latency in Lutris to fix it. Game works fine; if you're using a tablet, your best bet is to set up OpenTabletDriver, which you can go on their page for that; it isn't anything I contribute to.

Alternatively, you could follow a guide over at https://osu.ppy.sh/community/forums/topics/1248084?n=1 which uses Pipewire and an install script to set up osu! with better latency.

# Overwatch
Lutris script installs Battle.net, which has some weird graphical issues I haven't really sorted out. DXVK and FSync used; game installs fine. You have to let the game generate shader cache to get it to run properly; otherwise, game works perfectly fine for me.

# Battlefield V 
Usual precaching with Vulkan, even under DX11. Once you play a round on all maps, it should be fine. Alternatively, you can configure DXVK to use async using the following:

    DXVK_ASYNC=1
Alternatively, if you're using an Nvidia GPU, adding this should help with it a bit as well.
 
    __GL_SHADER_DISK_CACHE_SKIP_CLEANUP=1
    
FSR also works with this as well. Game will be a bit slower than usual until shaders are finished caching (usually play a round or two on each map), and then you should be okay.

This was a game I played with my friend Devin (Clickyzz), who passed away in a car accident in May of 2021. I miss you, buddy.

# Path of Exile
Runs right out of the box on latest Proton version; nothing else to be said. Vulkan is probably ideal since you'll be translating DX to Vulkan under DX11.

# Cyberpunk 2077
Game seems to run fine; seems to be some graphical glitches that I'm currently chocking up to the game being on an HDD instead of an SSD; will move the game over to my SSD to test later. Tested using Proton-GE 6.14

# Puyo Puyo Tetris 2
Game runs fine; although I had some issues with text on my first launch. A reboot fixed the issue. Latest Proton.

# uno!
Single player works if you can get UPlay running; multiplayer will crash your game and freeze the games of other people in the lobby.

# Call of Duty: Infinite Warfare
I used Glorious Eggroll's Proton 6. Cancel shader caching; you'll be there all fucking night, and it won't do much from my testing. Only have tested Zombies in Spaceland, but it ran fine after the map was loaded in for a minute or so. Still more to test.

# Among Us
This runs fine. No tweaks needed.

# Call of Duty 4: Modern Warfare
Game works fine, however CoD4x servers will error out saying that you need to sign in to Steam, so avoid using this if you can, and manually download the CoD4 1.7 exe file online.

# Call of Duty: World at War
Still needs to be tested with Plutonium; supposedly this fixes issues with this game and Black Ops 2.

# Battlefield 4
Game works fine using the installer under Lutris for Origin and DXVK setup (using default Lutris-6.1 prefix). You will need to run the following commands to get ping working in game, otherwise you will get kicked from any server with Punkbuster:

    sudo setcap cap_net_raw=epi /path/to/lutris/wine-preloader

    sudo setcap cap_net_raw=epi /path/to/lutris/wine64-preloader

    sudo setcap cap_net_raw=epi /path/to/lutris/wineserver
    
If you're using a custom Wine version (staging or wine-tkg in my case), you can find the preloaders and wineserver in /usr/bin

To boot the game via Battlelog, you have to spoof your active user agent in your web browser to be that of a Windows version, otherwise, Battlelog will say that you do not have the game installed; this is easily done using an extension for your browser of choice.

I presume this applies to Battlefield Hardline as well, but I haven't gotten around to testing it yet, so can't say for sure.

# Heroes and Generals
No matter what Proton or Wine version you use, upon starting the game, you will receive an error, stating: "Please start the game through Steam." This isn't anything new, and has been going on for over two years. This isn't working, and I saw that it uses BattleEye, which probably explains this.

# A Dance of Fire and Ice
This game works perfectly out of the box; however UnityModManager will not open in game like it does in Windows if you have that enabled, so please keep that in mind.

# Golf It!
This game runs without issues; played with friends with little to no issues. 

# TrackMania Nations Forever
Loaded up game and performance seems to be really good; no complaints on my end. 

# Metro Exodus Enhanced Edition
Game black screens and you can't get any further; not sure if a Wine dependency issue; for now, use the native Linux port on Steam, considering DLSS won't be integrated via Wine until the new Nvidia driver in the fall.

# Old School Runescape
Why are you trying to run this over Proton? Just use RuneLite; it'll save you a headache and has some nice QoL features built in.


# Current list of games that I'm going to test (will be updated)
- Spongebob Squarepants: Battle for Bikini Bottom Rehydrated
- A Hat in Time
- OMORI
