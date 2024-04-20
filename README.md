<div align="center">
  <img src="https://github.com/3skue/xAPI4/assets/142699644/f7a7bc99-4ac6-454c-adc4-9e544ccd4f6b" width="25%">
</div>

**Introduction**

xAPI is a fast, flexible and powerful pentesting and debugging tool written in pure luau.
It can detour, decompile and clone functions, hook metamethods and features over 45 globals that emulate the functionality of most executors.

**Installation**

To install xAPI, you will need to install the module from the GitHub repository and then insert it into your game, preferably inside of `game.ReplicatedStorage`.

You can then use the following script to load xAPI:
```lua
require(game.ReplicatedStorage.xAPI).load(debug.info(1, "f"))
```

**Feedback and Improvements**
- Go to Issues for questions or to report bugs
- Go to Pull Requests for improvements

---

<sub>
  
  **Notes**

  Current version: 4.0a

  xAPI is not against the Roblox TOS, as it does not modify the client externally and only runs what it is allowed to within the Roblox environment.
</sub>
