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

Obfuscator version: v0.0.3

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
local e_=bit32.bxor local r_,p,c,m,t_,a_;m={};r_=(getfenv());a_,p,t_=(string.char),(string.byte),(bit32 .bxor);c=function(d_,q)local n_,b_,h,o_;h={};o_,b_={},function(i_,k,s_)o_[i_]=e_(k,13761)-e_(s_,34870)return o_[i_]end;n_=o_[18805]or b_(18805,96356,19879)while n_~=-5.4293351610692255*-7295 do if n_<52026+-14165 then if n_>=-622031616/-17856 then if n_<=545392416/15656 then h[1]='';h[2],h[3],h[4],n_=1,(#d_- -11145/-11145)+(2618-2394),0.0072609400324149106*30850,o_[2419]or b_(2419,71579,48437)else h[4]=h[4]+h[2];h[5]=h[4]if h[4]~=h[4]then n_=796311640/15556 else n_=-5.5875147579693039*-6776 end end else h[1],n_=h[1]..a_(t_(p(d_,(h[5]- -0.28754813863928114*-779)+(-8937+8938)),p(q,(h[5]-(32153+-31929))%#q+5.7257371886630402e-05*17465))),o_[-17078]or b_(-17078,88524,26672)end elseif n_<-3.9657576696622248*-12908 then if(h[2]>=0 and h[4]>h[3])or((h[2]<0 or h[2]~=h[2])and h[4]<h[3])then n_=-1.9898157506025034*-25726 else n_=-0.57275026213532354*-16213 end elseif n_<=40329+10861 then return h[1]else h[5]=h[4]if h[3]~=h[3]then n_=o_[-13185]or b_(-13185,73861,50552)else n_=19379- -18482 end end end end return(function(f_,...)local j;j={};j[1]=function(l_)return f_[l_+(9688-9126)]end;j[2]=function(g)r_[c('\242f\235z\246','\130\20')](g)end;j[2](j[1](209872080/10512))end)({[15.216456634544107*1349]=c('*\v','b')},...)
```

output changes overtime when i added the features from above making it where it showcases what the obfuscation looks like right now.

Last Updated: 2025-11-06
