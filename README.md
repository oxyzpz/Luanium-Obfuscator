# Luanium-Obfuscator
Luanium is a Roblox LuaU and Lua 5.4 obfuscator better than MoonSec V3, Prometheus, IronBrew and etc. our number one competitor is Luraph

# Features
* Removes comments
* Renames variables
* Minifys code
* Control Flow Flattening
* Mangles Statements
* Mangles Numbers
* Mangles Strings
* Mangles Functions
* Mangles Globals
* Mangles Self Calls
* Anti-Dump, Anti-Debug, Anti-Tamper.
* Virtualize Code / VM (Premium Optional feature)
* VM Compression (Premium Optional feature)
* Macros
and more..

# What does Luanium have right now?
* Removes comments
* Renames variables
* Minifys code
* Control Flow Flattening
* Mangles Numbers
* Mangles Statements
* Mangles Strings
* Mangles Functions
* Mangles Globals

Nothing is toggleable everything is obfuscated in a whole.

I'll release this obfuscator once i make VM compression and virtualization / VM.
Our obfuscator will be accessed through a website.

version v0.0.3

Updates:
https://youtube.com/ | coming soon

This project was made to protect your Roblox and Lua scripts from reverse engineers.
Since our code is not opened sourced it is very difficult to deobfuscate Luanium

Supports Roblox LuaU and Lua 5.4 or higher

Here is what the obfuscation looks for now:
# Input
```lua
local function pr(message)
  print(message)
end

pr("Hi")
```

# Output
```lua 
local a = function(b);print(b);end;a("Hi");
```

output changes overtime when i added the features from above making it where it showcases what the obfuscation looks like right now.

Last Updated: 2025-11-06
