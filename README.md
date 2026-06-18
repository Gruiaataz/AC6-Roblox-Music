![Screenshot_20251018_152829_Roblox](https://github.com/user-attachments/assets/193241ae-4184-40c7-ae1c-070794a414d0)

# AC6-Music-Exploit🔍
a Luau Script that uses a Exploit that is in the A-Chassis Module
and play custom Audio On the game Server-Side

# What is A-Chassis?
It's a module script that provides a complete, physics-based vehicle system (cars, motorcycle, even tanks, and etc.) that developers can easily drop into their games and customize.

# Whats the Exploit?
Allowing Creation of a New Audio Instance Server-Sided in any Service - Instance or any Objects that Allows Audio to be parented under them through a UnSecure RemoteEvent
the exploit also can:
- Change Volume of custom audio
- Change the Pitch Also
- Loop
- and ofc play any AssestId (that is Atleast publicly available in assest store)

# How to Use/Execute?
your executor gotta atleast support **PluginSecurity**
(Check [Roblox-Identities](https://github.com/Pseudoreality/Roblox-Identities) for more info about capabilities & identities)

[UNC/sUNC](https://docs.sunc.su/About/what-is-sunc/): [gethui](https://docs.sunc.su/Instances/gethui/)
Note that it doesn't **require** the UNC/SUNC functions, the script will work normally even if your current executor doesn't support it

**Script:**
you can directly execute the enitre script by copying this and executing it
```Luau
loadstring(game:HttpGet("https://raw.githubusercontent.com/Roblox-HttpSpy/AC6-Music-Exploit/refs/heads/main/Ac6ExploitSource.luau"))()
-- By Https
```
you can also check the ``INFECTED_GAMES.txt`` to see known infected games or if you found a game with the vulnerablity please sumbit in issues or discussions but please follow the submission rules in the txt file

or check on updates goto the [tags/releases](https://github.com/Roblox-HttpSpy/AC6-Music-Exploit/releases) read the release notes

# NOTES 📝
- Something Broke/Broken? Submit a Issue!
but make sure its something wrong with the script and not the current game else the issue will be closed

- Why No Sound Playing even tho it found a AC6-Vuln?
  some games (like big games) may have a custom/modified AC6 (A-Chassis) that is secured, and no we cant bypass it

- Have a suggestion or other?
  Create a New Discussion or Issue!

also big note that lot of games with a A-Chassis may rename there Remote to something else, if you know Luau (know what your doing) execute [DEX](https://github.com/AZYsGithub/DexPlusPlus/) or [RemoteSpy](https://github.com/78n/SimpleSpy) (or both or any other tools that can help) and try to find the ReNammed RemoteEvent...

---

# Credits
- [yofriendfromschool1](https://github.com/yofriendfromschool1/)
basically giving me the idea
- [IceMinisterq](https://github.com/IceMinisterq)
the [NotificationLibrary](https://github.com/IceMinisterq/Notification-Library) Creator

# Misc.
[![License: GPL3.0](https://img.shields.io/badge/License%3A-GPL3.0-yellow?style=plastic)](https://github.com/Roblox-HttpSpy/AC6-Music-Exploit/blob/main/LICENSE)

[![Scripting Language: LUAU](https://img.shields.io/badge/Scripting%20Language%3A-LUAU-blue?style=plastic)](https://github.com/luau-lang/luau)
