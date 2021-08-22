# SoS2-Hologram-Darklight-Glow

Are your pawns

a) following an ideology with the Lighting precept,

b) holographic, and

c) crying about their own emitted light?

With this hacky patch applied, SoS2 (Save Our Ship 2) holograms now emit darklight instead of regular light. I'm not smart enough right now to make it a toggle, so it's always darklight right now.

What this patch does:

— Replaces glow on holograms from white light to darklight.

—— Specifically, this patch changes the <SoSHologramRace> def's <glowColor> from (255,255,255,0) to (78, 226, 229, 0), which is the specific colour assigned to darklight in Rimworld (DarklightUtility.IsDarklight).
  

What the patch does not do (yet):
  
— Provide the option to toggle between light and darklight.
  
— Stop the pawn from glowing entirely.

Considerations:
  
While this patch makes the light from a hologram darklight, it's still light, and having it follow a pawn around can cause issues. Your pawns presumably like darklight (else you wouldn't be here), but nutrifungus still doesn't want to see it. The pawn will damage your nutrifungus crops just by walking near them (and preventing sowing while the pawn is at it). I zone him out of the area. If your pawn is a grower, you're going to really want to do that.

I assume but have not tested the following:
  
— Presumably, the combat in darkness buff that the darkness meme grants is also ruined, regardless of if it's darklight or regular light.
  
— If you are running CE, your hologram is making a nice target (and doing the same for all your allies within 8 tiles), darklight or no darklight.
  

Future Plans:
  
This glow causes so many tiny little issues in a darkness run that I may have to look into an option to disable the glow entirely. This is easy to do by itself, I just don't know how to properly add the option to toggle between light, darklight, and no light. I'd have to steal whatever methods KV used in Rimfridge, I'm not good enough to do it on my own.

———————————————————————————————————
  
Installation:

Extract the SoS2-Hologram-Darklight-Glow-main folder to ~/Steam/steamapps/common/Rimworld/mods/
———————————————————————————————————

Run Rimworld on Steam? Grab this patch there:
https://steamcommunity.com/sharedfiles/filedetails/?id=2581525030

———————————————————————————————————

Want to buy me a coffee? I don't need any, thanks though.
