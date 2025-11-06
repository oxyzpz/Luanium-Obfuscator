# Luanium-Obfuscator
Luanium is a Roblox LuaU and Lua 5.4 obfuscator better than MoonSec V3, Prometheus, IronBrew and etc. our number one competitor is Luraph

# Features
* Removes comments
* Renames variables
* Minifys code
* Control Flow Flattening
* Mangles Numbers
* Mangles Statements
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
* Mangles Functions
* Mangles Globals

I'll release once i make VM compression / virtualization.


version v0.0.3

Updates:
https://youtube.com/ | coming soon

Get started and start obfuscating:
https://luanium | coming soon

This project was made to protect your Roblox and Lua scripts from reverse engineers.
Since our code is not opened sourced it is very difficult to deobfuscate Luanium

Supports Roblox LuaU and Lua 5.4 or higher

Our obfuscator will release in 2026-01-01

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

output will be changed soon.
