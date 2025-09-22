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
* Uses custom Base85 and bit32
* Anti-Dump, Anti-Debug, Anti-Tamper, Anti-Deobfuscation
* Confuser / Dead code 
* VM (Premium Optional feature)
and more..

version v0.0.1

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
local function a(b);print(b);end;a("Hi");
```
