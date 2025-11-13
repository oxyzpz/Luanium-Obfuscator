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
* Virtualization / VM 
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
-- This script was protected by using Luanium Obfuscator v0.0.4 [https://luanium.com]

-- With control flow flatten ( mid but i'll improve it ) execute this in your executor

local j_=getfenv()local U,W,Zo=j_.string.char,j_.string.byte,j_.bit32.bxor local V=function(wC,ej)local Fy='' for xq=1,#wC do Fy=Fy .. U(Zo(W(wC,xq),W(ej,(xq-1)%#ej+1)))end return Fy end local F=function(b_,yb,ef)return(bit32.bxor(ef,72593)-bit32.bxor(yb,20483))+b_ end local yx=function(...)local lW=nil local v_=false local uy={} local X,Hg,as,Mk,lH,eQ,h_,pV,R,nU,E,xq,s_,w_,m_,iJ,Er local yH={} uy[F(42769,44012,5473)]=function()X=function(Hg,as)local Mk,lH=string.char,string.byte local eQ,h_=lH(Hg,((82688492829.53707886-82688492839.53707886)+(21515760896.38986588-21515760885.38986588)),((63077079953.62996674-63077079963.62996674)+(36411659059.20986938-36411659047.20986938)))if not eQ then return "" end local pV=eQ*((69548419781.1164856-69548419686.1164856)+(46960982777.13671112-46960982616.13671112))+h_ local R={lH(Hg,((25468883171.90601349-25468883191.90601349)+(18794931448.27972412-18794931425.27972412)),((92913793897.91317749-92913793898.91317749)+(10545766843.21901512-10545766840.21901512))+pV)} local nU={lH(as,((67631103471.77852631-67631103467.77852631)+(40144291072.57102203-40144291075.57102203)+(646578521.143424-646578521.0)-(646578521.143424-646578521.0)),#as)} local E={} for xq=((28289835518.32115173-28289835531.32115173)+(5897676240.79378033-5897676226.79378033)),#R do table.insert(E,Mk(bit32.bxor(R[xq],nU[(xq-((77800129349.94599915-77800129364.94599915)+(45997396758.78892517-45997396742.78892517)))%#nU+((36155194753.25026703-36155194746.25026703)+(39944295644.4956665-39944295650.4956665))])))end return table.concat(E)end s_=function(w_,...)local Z=function(m_)local iJ=w_[m_+(((97036274413.99766541-97036272168.99766541)+(66493253547.56382751-66493250255.56382751)+(44307386829.01283264-44307383544.01283264)+(75412310312.53671265-75412307353.53671265)+(50417262.851957-50417262.0)-(50417262.851957-50417262.0)))]if j_[V('\000\010\004\022','ts')](iJ)==X("\000\008\240\061\043\176\226\033\042\189","\150\072\069\211")then return iJ()else return iJ end end local c_=function(Er)j_[V('\017\006\008\026\021','at')](Er)end c_(Z(-(((50421033460.04011536-50421030429.04011536)+(55114305784.07976532-55114303891.07976532)))))end return F(28888,4290,7195)end uy[F(28888,4290,7195)]=function()if(#j_[V('\017\012\022\023\023\010\011\004','ec')](yH[1]or "")+1)>=0 then do yH[3]=(yH[3]or 0)-4562 end end lW=(s_{[((46359959735.23697662-46359956250.23697662)+(49870402658.67238617-49870399286.67238617))]=(function()return X("\000\002\193\094","\137\055\100")end)})v_=true return 0 end local L=F(42769,44012,5473)while L~=0 do local vt=uy[L]if not vt then break end L=vt()end return lW end yx(...)
```

output changes overtime when i added the features from above making it where it showcases what the obfuscation looks like right now.

Last Updated: 2025-11-13
