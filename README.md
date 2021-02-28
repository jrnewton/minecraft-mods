# Pre-reqs 
1. Determine mods being installed
2. The mod version seems to correspond to the MC server version, E.g. Flan's Mod 1.12.2 requires Minecraft server 1.12.2 and Forge 1.12.2

# Server side steps
1. sudo apt install default-jre
2. Download minecraft server: https://www.minecraft.net/en-us/download/server  
3. Edit eula.txt, set eula prop equal to true 
4. Create minecraft.sh to launch the server:
```
#!/bin/bash
java -Xmx1024M -Xms1024M -jar minecraft_server.1.16.4.jar nogui
```
5. Modify minecraft.properties as needed

# Client side steps
1. Download https://flansmod.com/ for MC version used above.
2. Follow https://www.minecraftmods.com/how-to-install-mods-for-minecraft-forge/
