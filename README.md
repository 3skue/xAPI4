<div align="center">
  <img src="https://github.com/user-attachments/assets/97f4b983-4e3d-46e5-a08f-d631479a7466" width="100%">
</div>

**Introduction**

xAPI is a fast, flexible and powerful pentesting and debugging tool written in pure luau.
It can detour, decompile and clone functions, hook metamethods and features over 100 globals that emulate the functionality of most, if not all, executors.

**Installation**

To install xAPI, you will need to download the latest installer from [releases](https://github.com/3skue/xAPI4/releases) and insert it into `game.ServerScriptService`.

You can then use the following snippet to load xAPI into your script:
```lua
require(game.ReplicatedStorage:WaitForChild("xAPI"))()
```

**Feedback and Improvements**
- Go to Issues for questions or bugs
- Go to Pull Requests for improvements

---

<br />

<sub>

**Notes**

  Current version: 4.4
  
  xAPI is not against the Roblox TOS, as it does not modify the client externally and only runs what it is allowed to within the Roblox environment.
</sub>

---