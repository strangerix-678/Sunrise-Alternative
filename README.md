# Sunrise-Alt

An alternative take on Project Sunrise, built on the 0.3.2 base. Same offline exploration
mod, with the movement page reworked and a few settings widened. This is a fork with my own
tweaks on top — all the real work is by the authors credited below.

Offline only, same as the original — it does not connect to live servers.



## What's different in this version

* Movement page renamed **Teleport \& Flying**, reorganised into clear sections:
**Teleport → Noclip → Flying**.
* **Teleport** distance raised to **200** units. The key row is labelled **TP Key**.
* **Noclip** is its own section with a simple on/off toggle (no key needed) — it sits between
Teleport and Flying so it's always visible.
* **Flying** groups the fly controls with a clearer description. Fly speed range widened to
**0.5 – 200 units/s** with finer (decimal) steps, so you can fly slower for precision or
much faster than before.
* HUD page is listed as **Sunrise HUD** in the menu (its in-panel title stays "HUD").



## Usage

Open the overlay with `Insert`, then go to the **Teleport \& Flying** tab.



### Teleport

Turn on **Enabled**, set the **Distance** slider (up to 200), then click **TP Key** and press
the key you want. Press that key in-game to teleport.



### Noclip

Turn **Enabled** on or off. Pass through walls and floors — works while walking or flying.



### Flying

Turn on **Enabled**, set **Speed**, then click **Fly Key** and press the key you want. Then in-game:

* `W / A / S / D` to move along the facing direction
* `Spacebar` (jump) to go up
* `Ctrl` (crouch) to go down

All keys and settings are saved between sessions.



## Preview
Left is base, right is the alternative version.
<img width="1920" height="1080" alt="alternate" src="https://github.com/user-attachments/assets/bbeec423-c2e2-4884-a5ad-d4bb11515bad" />





## Credits

All the real work is theirs, I just edited on top:

* stanuwu — Project Sunrise (base, incl. fly/noclip in 0.3.2): https://github.com/stanuwu/Sunrise



Thank you as always.



# Sunrise

Destiny 2 Offline Exploration Mod

> This mod installs onto an old build of the game and allows you to play it offline, loading into
> destinations and exploring them.
>
> No other features are currently supported. (Missions, Enemies, NPCs, Quests, Inventory
> Management, ...)

* [Install Instructions](https://github.com/stanuwu/Sunrise/wiki/Installing)
* [FAQ](https://github.com/stanuwu/Sunrise/wiki/FAQ)
* [Common Issues](https://github.com/stanuwu/Sunrise/wiki/Common-Issues)
* [Discord](https://discord.gg/jQYqhkuh7h)

## 

## Support the Original Author

Leave a star on the original repo: https://github.com/stanuwu/Sunrise

If you want to support stanuwu's open source work you can find the means on their
[profile](https://github.com/stanuwu). Also consider donating to charity instead.

All content released under this project is free and open source. If someone is trying to sell you
something you are getting scammed.

## Rules

Issues are for bug reports only. PRs are for pull requests only. Do not go and argue/chat there,
you can do that on the discord.

## Contributing

Pull Requests are welcome. Please follow these rules:

* **No Copyrighted Data** - All game data should be extracted at runtime.
* **Code Formatting** - Stick to the provided clang-format and clang-tidy configs.
* **Clean Code** - Try to post readable high quality code, follow the projects existing style of
comment and add docs.
* **Provide Documentation** - Please explain what you changed, why you changed it and the effects it
has in detail, it saves me a lot of work.
* **Follow Up** - If something with the PR is not right, I will reply and ask you to fix it.
* **One Feature** - Do not put multiple features into one PR.
* **Complete Implementations** - Do not PR features that are not completed and/or have non functional parts.
* **Server Focus** - For features that are intended to be part of the server, don't abuse client patches. Sometimes its needed but mostly everything should go through the right requests and pushes.

## Credits

### Dependencies:

* https://github.com/ocornut/imgui
* https://github.com/microsoft/detours

### Artwork:

* [Solus](https://www.youtube.com/@Solus-yt)

### Testing:

* [Ferr](https://x.com/light_fades_awy)
* [gage](https://x.com/_Quolu_)
* [Jenka](https://youtube.com/@jenkad2oob?si=OQpCGeBCEJBS0zHx)
* [Katie](https://github.com/Confetti3)
* [Kody Ivie](https://x.com/Kody_Ivie)
* [Solus](https://www.youtube.com/@Solus-yt)
* Breshi
* [Deltadog55](https://www.youtube.com/@deltadog55)
* Moosh
* [MoveableFormula](https://youtube.com/@movableformula)
* Z
* The Cube17

### Inspiration/Helpful Repos

* https://github.com/v4nguard/tiger-pkg
* https://github.com/cohaereo/alkahest
* https://codeberg.org/V4NGUARD/tachyscope
* https://github.com/MontagueM/D2TagParser
* https://github.com/MontagueM/DestinyUnpackerCPP
* https://github.com/nblockbuster/D2TextureRipper
* https://github.com/v4nguard/tiger-parse
* https://github.com/Demonware-Custom-Server/demonware-cod4
* https://github.com/hosseinpourziyaie/demonware-companion
* https://github.com/jordam/demonbugger
* https://github.com/project-bo4/shield-development
* https://github.com/MontagueM/Charm
* https://github.com/v4nguard/quicktag
* https://github.com/nblockbuster/D2StaticDocs
* https://github.com/MontagueM/D2Maps
* https://github.com/MontagueM/DestinyMapmining
* https://github.com/nblockbuster/tachyscope
* https://github.com/cohaereo/destinydocs
* https://github.com/MontagueM/DestinyUnpacker

### Other:

* [Ginsor](https://x.com/GinsorKR) - Gave me some useful pointers

> These credits are from the original Sunrise project. Want to be added to or removed from the
> credits? Let the original author know.

## Content Disclaimer

Sunrise is not:

* A Crack
* A Cheat
* A Custom Server

Everyone needs to provide their own copy of the game, no piracy is happening. The mod does not
connect to any servers, it runs completely locally. We do not offer any servers or services.

## Legal Disclaimer

This project is not for profit. It does not affect live servers or newer versions of the game where
research like this could pose a security risk. No game data will be included in the release so this
is not a copyright violation. This is also not a circumvention of protective measures. Please do not
file any DMCA or other copyright claims against this. Legal action will be taken for abuse of the
copyright system to censor this work.

## AI Disclaimer

AI was used in the creation of this project. If you are not comfortable with the use of AI in
programming projects beware.

AI was NOT used to create any art or creative writing. Only for RE, development and documentation
purposes. All AI work that is publicly released is reviewed by a human. AI is a tool and the user is
responsible for the results it produces.

## Affiliation Disclaimer

This project is not affiliated with Bungie or Sony in any way.

## License

GPLv3, same as the original. See LICENSE. Original notices kept intact.
Modified: reorganised the movement UI into Teleport \& Flying (Teleport / Noclip / Flying),
raised teleport max to 200, widened fly speed to 0.5-200 units/s with finer steps, renamed the
HUD menu entry to Sunrise HUD.

