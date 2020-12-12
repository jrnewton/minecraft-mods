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
6. Download https://flansmod.com/
7. Follow https://www.minecraftmods.com/how-to-install-mods-for-minecraft-forge/

# Client side steps
1. Create an install profile in minecraft client for server version
