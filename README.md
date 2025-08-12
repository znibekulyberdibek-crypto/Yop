--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=string.char;local v1=string.byte;local v2=string.sub;local v3=bit32 or bit ;local v4=v3.bxor;local v5=table.concat;local v6=table.insert;local function v7(v10,v11) local v12={};for v15=1, #v10 do v6(v12,v0(v4(v1(v2(v10,v15,v15 + 1 )),v1(v2(v11,1 + (v15% #v11) ,1 + (v15% #v11) + 1 )))%256 ));end return v5(v12);end local v8=true;local v9={[44 -(35 + 8) ]=false};while v8 do local v13=0 -0 ;local v14;while true do if (v13==(1266 -(97 + 1169))) then v14=(2487 -(68 + 997)) -(378 + (2314 -(226 + 1044))) ;while true do if (v14==((0 -0) -0)) then game:GetService(v7("\227\198\203\41\239\184\198\10\212\199\232\49\233\169\198\25\212","\126\177\163\187\69\134\219\167")):WaitForChild(v7("\17\200\39\202\232\38\222","\156\67\173\74\165")):WaitForChild(v7("\18\190\78\30\168\20\67\39\162\69\2","\38\84\215\41\118\220\70")):FireServer(unpack(v9));wait((137 -(32 + 85)) -(13 + 0) );break;end end break;end end end
