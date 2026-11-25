This repository is my actively building a pack to practice/learn Github and packwiz.

Original modpack base is from here:  
https://www.curseforge.com/minecraft/modpacks/fear-nightfall/files/9389072

***The CurseForge zip will contain no mods unless you edit the profile and add the following java argument:***  
`-javaagent=unsup.jar`

***Additionally, if you run the CurseForge profile one time before adding the above argument, default keybinds and some other pre-set configurations will be missing. Recommended to delete the profile and start again.***

### Zips:  
https://github.com/setzke/FN-MIJ-dev/releases/download/zip/FN-MIJ-dev.CurseForge.zip  
https://github.com/setzke/FN-MIJ-dev/releases/download/zip/FN-MIJ-dev.Prism.zip  
https://github.com/setzke/FN-MIJ-dev/releases/download/zip/FN-MIJ-dev.Server.zip  
  
  
<details>
<summary>My personal area:</summary>  

# TODO:  
 
 - base create and all the compats, then expand
 
- should we add hamsters?
  https://modrinth.com/mod/adorable-hamster-pets
  
See mod list of what was added to last pack... ugh start making choices. Remember, your players can request things later to be added!
  
- Punchy recommends a resource pack for modded weapons
- do these mods allow for modded clothes that show on arm?

- add CREATE

-oh yeah add my 3rd person perspective mod as an optional on first launc


## *low priority:*  
- distant friends names  
  - Could do fun skins like santa, jack skelington... patrick / spongebob, whatever can be found. Maybe more horror themed ones tho. Even better if can find ones that have emissives.
- Look into resource-pack-overrides config  
- Investigate config for traveler's titles. Add title for mindscape that isn't "???". Other biomes too if added later. PURPLE OFC.  
  - example from the mod page:  
    "travelerstitles.minecraft.the_nether": "The Nether",  
    "travelerstitles.minecraft.the_nether.color": "ff0000",  
    singleplayer or OP test:  
    /biometitle <biome>  
    /dimensiontitle <dimension>  
- Work on unsup colors.  

- clean up more server vs client files (options and servers.dat aren't needed in server)


## *Backburner:*  
- Look into analytics mod in pack

- Figure out how simple rpc works. Can January set it to STREAMING and have a link to his twitch on Discord? Not needed, but a cool feature.  

- garbage collection for DH for client if needed  
(server exists, but that was for java 25. Would other servers have java 17? Should it adapt to version? Can java handle just throwing each one at it? Look into garbage collection.)
  - Client is java 17 and needs shenandoah, if any

- jei setting (investigate)  

----
### Failed fabric Homestead hexxy:  
cardinal components api\
hexcassettes\
hexical\
hextended

</details>