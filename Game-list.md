# Note
This list exists purely for documentation of getting Windows games (or attempting to get them) to run on Linux using software such as Wine and other dependencies for performance. This is purely my experience, and I may have tips to get things working in this thread.

# If you would like me to test a game, submit an issue ticket and I will check the game out.

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
The normal launcher boots under the first Lutris installer script; you have to be in legacy, or else the launcher will be stuck on the game logo. Haven't tested the game yet. Open-source fast launcher encounters a rundll32 error, and will crash after some time downloading the game. No further testing or tweaks done; all on Lutris 6.2 x64

# osu!
Set this up with Lutris and use ThePoon's audio latency patch; if you're having audio distortion, enable Pulseaudio Low Latency in Lutris to fix it. Game works fine; if you're using a tablet, your best bet is to set up OpenTabletDriver, which you can go on their page for that; it isn't anything I contribute to.

# Overwatch
Lutris script installs Battle.net, which has some weird graphical issues I haven't really sorted out. DXVK and FSync used; game installs fine. You have to let the game generate shader cache to get it to run properly; otherwise, game works perfectly fine for me.

# Battlefield V 
Usual precaching with Vulkan, even under DX11. Once you play a round on all maps, it should be fine.
This was a game I played with my friend Devin (Clickyzz), who passed away in a car accident in May of 2021. I miss you, buddy. In honor of him.

# Path of Exile
Runs right out of the box on latest Proton version; nothing else to be said. Vulkan is probably ideal since you'll be translating DX to Vulkan under DX11.

# Cyberpunk 2077
Got to the menu on this; haven't tested further. Menu feels fine so far, although I do know that ray tracing will not work under DXVK, be warned. Was going to install control tweaks before I tested further; will update later.

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
    
If you're using a custom Wine version (staging or wine-tkg in my case), you can fine the preloaders and wineserver in /usr/bin

To boot the game via Battlelog, you have to spoof your active user agent in your web browser to be that of a Windows version, otherwise, Battlelog will say that you do not have the game installed; this is easily done using an extension for your browser of choice.

# Heroes and Generals
No matter what Proton or Wine version you use, upon starting the game, you will receive an error, stating: "Please start the game through Steam." This isn't anything new, and has been going on for over two years. This isn't working, and I saw that it uses BattleEye, which probably explains this.

# A Dance of Fire and Ice
This game works perfectly out of the box; however UnityModManager will not open in game like it does in Windows if you have that enabled, so please keep that in mind.

# Golf It!
This game runs without issues; played with friends with little to no issues. 

# TrackMania Nations Forever
This game seems to work, however I haven't really played it much to confirm this.


# Current list of games that I'm going to test (will be updated)
- Spongebob Squarepants: Battle for Bikini Bottom Rehydrated
- A Hat in Time
- OMORI
