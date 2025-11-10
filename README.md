# Luanium-Obfuscator
Luanium is a Roblox LuaU and Lua 5.1 obfuscator better than MoonSec V3, Prometheus, IronBrew and etc.

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

Obfuscator version: v0.0.4

Updates:
https://youtube.com/ | coming soon

I made this project to protect your Roblox Lua scripts (exploiting) from reverse engineers.

Supports Roblox LuaU and Lua 5.1 or higher

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
-- This script was protected by using Luanium Obfuscator v0.0.3 [https:// the website is still not hosted yet.]
-- there is no control flow flattening in this one but ill showcase it probably tomorrow

local mv=getfenv()local t_,iG,wE=mv.string.char,mv.string.byte,mv.bit32.bxor local qs=function(ns,Jj)local Jk='' for xk=1,#ns do Jk=Jk .. t_(wE(iG(ns,xk),iG(Jj,(xk-1)%#Jj+1)))end return Jk end local mI=function(Gd,N)local Pt={} for xk=(613213501-613213468),(2537283445-874760438-765298463-897224427)do Pt[string.char(xk)]=xk-(1805715690-697521496-751576138-356618023)end local U=function(ns)local ah={} for xk=(820699860-176678395-644021464),#ns,((73557811)%463218-369362)do local c_=0 for L=0,(1943498808-615906716-734129525-593462563)do local dC=ns:sub(xk+L,xk+L)c_=c_*(480991830-368293953-112697792)+(Pt[dC]or 0)end for L=(513376597-146176362-367200232),0,-((53177186)%383449-261223)do table.insert(ah,string.char(bit32.band(bit32.rshift(c_,(400527986-400527978)*L),0xFF)))end end return table.concat(ah)end local f_=U(Gd)local x_,o_=string.byte(f_,(2824/2824),(709898307-709898305))local D=x_*(210067838-210067582)+o_ local Mh={} for xk=(134271648-134271645),(686017516-686017514)+D do Mh[#Mh+(161658025-161658024)]=string.byte(f_,xk)end local O=U(N)local Ba={string.byte(O,((38380128)%378093-192734),#O)} local ah={} for xk=(265496851-265496850),#Mh do table.insert(ah,string.char(bit32.bxor(Mh[xk],Ba[(xk-((11942006)%671380-528545))%#Ba+(514556338-514556337)])))end return table.concat(ah)end local nf=function(sd,...)local dC=function(yw)local mU=sd[yw+(-(86603747/4957))]if mv[qs('\013\020\009\008','ym')](mU)==mI("!!n<nc)HqMbbP4=","i#JN7")then return mU()else return mU end end local Os=function(e_)mv[qs('\001\026\024\006\005','qh')](e_)end Os(dC((431951031-243935871-187989163)))end return nf{[(68702508/8058)]=(function()return mI("!!59T","FS=2a")end)}
```

output changes overtime when i added the features from above making it where it showcases what the obfuscation looks like right now.

Last Updated: 2025-11-10
