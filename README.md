<div align="center">
  <img src="https://github.com/user-attachments/assets/97f4b983-4e3d-46e5-a08f-d631479a7466" width="100%">
</div>

**Introduction**

xAPI is a fast, flexible and powerful pentesting and debugging tool written in pure luau.
It can detour, decompile and clone functions, hook metamethods and features over 60 globals that emulate the functionality of most executors.

**Installation**

To install xAPI, you will need to install the latest model from [releases](https://github.com/3skue/xAPI4/releases) and then insert it into your game, preferably inside of `game.ReplicatedStorage`.

You can then use the following script to load xAPI:
```lua
require(game.ReplicatedStorage.xAPI)()
```

**Feedback and Improvements**
- Go to Issues for questions or bugs
- Go to Pull Requests for improvements

---

<sub>

**Credits**
- rce incorporated - [Fiu](https://github.com/rce-incorporated/Fiu) (Luau bytecode interpreter)
- RealEthanPlayzDev - [LuauCeption](https://github.com/RealEthanPlayzDev/LuauCeption) (Luau bytecode compiler)
- krissynull - [os.clock session tracker](https://devforum.roblox.com/t/a-way-to-track-players-across-accounts/1819654)
- Egor Skriptunoff, boatbomber, and howmanysmall - [HashLib](https://devforum.roblox.com/t/hashlib-cryptographic-hashes-in-pure-lua/416732)
- metatablecat - [LZ4 in lua](https://gist.github.com/metatablecat/92345df2fd6d450da288c28272555faf#gistcomment-4849086)

  </br>

**Notes**

  Current version: 4.2
  
  xAPI is not against the Roblox TOS, as it does not modify the client externally and only runs what it is allowed to within the Roblox environment.

  <br />
  
  For script kiddies: Please, at least put `-- Forked from xAPI (github.com/3skue/xAPI4)` at the top of the script.
  
  I am literally going to have to change the license because of you. 
</sub>
