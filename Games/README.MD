# Wayland Native Games Compatibility List
A curated list of tricks to run linux games without XWayland 

| Game | Wayland | Engine | Info |
|------|---------|--------|------|
| Aragami | no | Unity | SDL2: crash |
| Awaria | yes* | Unity | SDL2 preload download the game from [itch.io](https://vanripper.itch.io/awaria) ,[screenshot](https://github.com/Twig6943/Wayland-Gaming/blob/main/Games/Screenshots/Awaria.png) |
| Baba Is You | no | Multimedia Fusion 2 | SDL2: crash |
| Bastion | yes* | FNA-XNA | SDL2 preload mouse KO, xbox pad OK |
| BattleBlock Theater® | yes* | - | SDL2 preload, [Screenshot](https://raw.githubusercontent.com/Twig6943/Wayland-Gaming/refs/heads/main/Games/Screenshots/BattleBlock_Theater.png) |
| Besiege | no | Unity | SDL2 : no effect |
| BioShock Infinite | yes* | Unreal Engine 3 | SDL2 preload |
| BIT.TRIP Presents... Runner2: Future Legend of Rhythm Alien | no | - | SDL2: crash |
| Black Mesa | yes* | Source | SDL2 preload |
| Borderlands 2 | no | Unreal Engine 3 | SDL2: error |
| Celeste | yes* | FNA-XNA | SDL2 preload, [screenshot](https://raw.githubusercontent.com/Twig6943/Wayland-Gaming/refs/heads/main/Games/Screenshots/Celeste.png) |
| Clone Hero | yes* | Unity | SDL2 preload, [screenshot](https://raw.githubusercontent.com/Twig6943/Wayland-Gaming/refs/heads/main/Games/Screenshots/Clone_hero.png) |
| Chess | yes | | Install from [flatpak](https://flathub.org/apps/org.gnome.Chess) |
| Chivalry: Medieval Warfare | yes* | Unreal Engine 3 | SDL2 preload mouse KO |
| Cities: Skylines | no | Unity | launcher fail to start game |
| Counter-Strike: Global Offensive | yes* | Source | SDL2 preload |
| Counter-Strike: 2 | yes* | Source 2 | SDL2 preload (this is very experimental) |
| Crusader Kings II | no | Clausewitz Engine | SDL2: crash |
| Day of Infamy | yes* | Source | SDL2 preload |Day of Dragons
| DDNet | yes | | Install from [flatpak](https://flathub.org/apps/tw.ddnet.ddnet), [Screenshot](https://raw.githubusercontent.com/Twig6943/Wayland-Gaming/refs/heads/main/Games/Screenshots/ddnet.png) |
| Dead Cells | yes*	 | Heaps | [See](https://gist.github.com/ToxicMushroom/d6cd025656f75e425c14249c1bc53f96) |
| Deus Ex: Mankind Divided | no | Dawn Engine | SDL2: no visible window |
| DiRT Rally | no | Ego Engine | SDL2: no visible window |
| Distance | no | - | SDL2 : no effect |
| Dreamfall Chapters | no | Unity | SDL2 : no effect |
| Euro Truck Simulator 2 | no | Prism3D | SDL2 : no effect |
| Europa Universalis IV | no | Clausewitz Engine | SDL2: crash |
| EVERSPACE™ | no | Unreal Engine 4 | SDL2: crash |
| Factorio | yes* | - | SDL2 preload |
| Friday night funkin' | yes* | - | SDL2 preload |
| fault - milestone one | yes* | Ren'Py | SDL2 preload |
| FEZ | yes* | FNA-XNA | SDL2 preload |
| From the Depths | no | - | SDL2: no visible window |
| FTL: Faster Than Light | no | - | SDL2 : no effect |
| Game Dev Tycoon | no | NW.js | SDL2 : no effect |
| Garry's Mod | yes* | Source | SDL2 preload |
| Gear Up | no | - | SDL2 : no effect |
| Grand Theft Auto IV | no | RAGE | Got it running with proton-tkg, [screenshot](https://raw.githubusercontent.com/Twig6943/Wayland-Gaming/refs/heads/main/Games/Screenshots/GtaIV.png) |
| Guns of Icarus Online | no | Unity | SDL2 : no effect |
| Hearts of Iron IV | no | Clausewitz Engine | launcher fail to start game |
| Helltaker | no* | Unity | SDL2 preload doesn't work, probably because the unity version of the game is old |
| HITMAN™ | no | - | SDL2: no visible window |
| Hollow Knight | no | Unity | SDL2: no visible window |
| Iconoclasts | no | Construct 3 | SDL2 : no effect |
| Indivisible | yes* | - | SDL2 preload |
| Insurgency | yes* | Source | SDL2 preload |
| ISLANDERS | no | Unity | SDL2: crash |
| Kerbal Space Program | no | Unity | SDL2: crash |
| Keypunch | yes | | Install from flatpak(https://flathub.org/apps/dev.bragefuglseth.Keypunch)|
| Left 4 Dead 2 | yes* | Source | SDL2 preload |
| Life is Strange - Episode 1 | no | Unreal Engine 3 | SDL2: crash |
| Life is Strange 2 | yes* | Unreal Engine 4 | SDL2 preload |
| Life is Strange: Before the Storm | no | Unity | SDL2: no visible window |
| Mad Max | no | Apex Engine | SDL2: no visible window |
| Metro 2033 : Redux | no | 4A Engine | SDL2 : OpenGL 4.0 or later has not been found |
| Metro Last Light : Redux | no | 4A Engine | SDL2 : OpenGL 4.0 or later has not been found |
| Minecraft | yes* | LWJGL | Your launcher needs to support the use of system libs / Your glfw pkg must be 3.4 or higher, [Screenshot](https://github.com/Twig6943/Wayland-Gaming/blob/main/Games/Screenshots/Minecraft.png?raw=true)  |
| Mini Metro | no | Unity | SDL2: crash |
| Momodora: Reverie Under The Moonlight | no | GameMaker Studio | SDL2 : no effect |
| Northgard | no | - | SDL2: crash |
| PAYDAY 2 | no | Diesel Engine | SDL2: crash |
| Portal | no | Source | SDL2: logo and crash |
| Portal 2 | yes* | Source | SDL2 preload |
| Phoenix Wright: Ace Attorney Trilogy | yes* | | Play android version via waydroid, [screenshot](https://raw.githubusercontent.com/Twig6943/Wayland-Gaming/refs/heads/main/Games/Screenshots/AceAttorney.png) |
| PokeMMO | yes* | GLWF | Need a newer version of GLWF, use the Flatpak version and remove the x11 permission |
| Project Zomboid |  | LWJGL | XWayland: compatibility mode |
| Robocraft | no | Unity | SDL2: no visible window |
| Roblox | yes |  | Use [sober](https://sober.vinegarhq.org/) to play, [screenshot](https://raw.githubusercontent.com/Twig6943/Wayland-Gaming/refs/heads/main/Games/Screenshots/Roblox.png) |
| ReIII | yes* | RAGE | Game uses glfw for windowing soo all you need to do is compile with wayland support (Couldn't find a binary that has wayland support enabled) |
| ReVC | yes* | RAGE | Game uses glfw for windowing soo all you need to do is compile with wayland support (Couldn't find a binary that has wayland support enabled) |
| Rocket League® | yes* | Unreal Engine 3 | SDL2 preload Native RL deprecated, for online game need Proton/RocketLeague |
| Saints Row IV | yes* | - | SDL2 preload |
| Saints Row: The Third | yes* | - | SDL2 preload |
| Seers Isle | no | - | XWayland crash |
| Shadow of the Tomb Raider | yes* | - | SDL2 preload |
| Space Cadet | yes | | Install the [flatpak](https://flathub.org/apps/com.github.k4zmu2a.spacecadetpinball) |
| Speedrunners | yes* | FNA-XNA | SDL2 preload, [screenshot](https://raw.githubusercontent.com/Twig6943/Wayland-Gaming/refs/heads/main/Games/Screenshots/Speedrunners.png) |
| Synergy | yes* | Source | SDL2 preload, [screenshot](https://raw.githubusercontent.com/Twig6943/Wayland-Gaming/refs/heads/main/Games/Screenshots/Synergy.png) |
| Shan Gui (山桂) | no | - | XWayland crash |
| Sid Meier's Civilization® V | no | Gamebryo | SDL2: crash |
| Snow Light | no | - | SDL2: logo and crash |
| Solitaire | yes | - | Install from [flatpak](https://flathub.org/apps/org.kde.kpat) |
| Sound of Drop - fall into poison - | yes* | - | SDL2 preload |
| Star Conflict | no | Hammer Engine | SDL2: crash |
| Stellaris | no | Clausewitz Engine | SDL2: crash |
| Tabletop Simulator | yes* | - | Need `SDL_DYNAMIC_API` and `SDL_VIDEODRIVER` |
| Terraria | yes* | FNA-XNA | SDL2 preload mouse KO |
| Team Fortress 2 | yes* | Source | SDL2 preload, [screenshot](https://raw.githubusercontent.com/Twig6943/Wayland-Gaming/refs/heads/main/Games/Screenshots/team_fortress_2.png) |
| The Coma: Recut | no | - | SDL2: crash |
| The Witcher 2: Assassins of Kings Enhanced Edition | yes* | REDengine | SDL2 preload need mouse border calibration |
| Tomb Raider | no | - | SDL2: no visible window |
| Transistor | no | - | SDL2: logo and crash |
| Unturned | no | Unity | SDL2: crash |
| VA-11 Hall-A: Cyberpunk Bartender Action | no | GameMaker Studio | SDL2 : no effect |
| VirtuaVerse | yes* | Unity | Need `SDL_DYNAMIC_API` and `SDL_VIDEODRIVER` |
| War Thunder | yes | - | Use the [flatpak](https://flathub.org/apps/net.gaijin.WarThunder) |
| We. The Revolution | no | - | SDL2: no visible window |
| Whispering Willows | no | Unity | SDL2: crash |
| XCOM® 2 | no | Unreal Engine 3 | SDL2: crash |

## Status Legend

| Code | Meaning |
|------|---------|
| **yes** | The linux port runs on Wayland natively without any configuration |
| **yes*** | The linux port can work on Wayland natively, but needs some tinkering |
| **no** | The linux port either doesn't exist or requires XWayland to run. Try emulating another port of the game |
| **no*** | There isn't a port of the game that you can emulate without XWayland. |

## Environment Variables

You need to install the sdl2 package on your distro before doing this.

| Launcher | How to find it |
|----------|----------------|
| Steam | Library > Properties > Launch options > Add environment variables before `%command%` |
| Heroic game Launcher | Library > Settings > Environment Variables |

### SDL_VIDEODRIVER

To run an SDL2 application on Wayland, set `SDL_VIDEODRIVER=wayland` 

### SDL_DYNAMIC_API
`SDL_DYNAMIC_API` override the SDL library used by a particular game. Useful if the game use a old version without Wayland support.

Fedora, Arch: `SDL_DYNAMIC_API=/usr/lib64/libSDL2-2.0.so`

Flatpak: `SDL_DYNAMIC_API="/usr/lib/x86_64-linux-gnu/libSDL2-2.0.so.0"`
