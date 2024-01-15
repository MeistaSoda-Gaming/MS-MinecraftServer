# MS Minecraft Server (Java Edition)
This repository serves the purpose of easily setting up a Minecraft server and will show different methods and crucial steps of that process.

Downloading this whole repository saves the process of downloading the Minecraft server files and creating a new world.

## Methods
We will showcase not every possible method of hosting a minecraft server but rather relevant ones:
- Creating a server in a new generated world.
- Importint existing world into server.

## :one: Creating a new server
_This guide is also explained step by step in a [YouTube Video](https://youtu.be/V6G_drxxdB4?si=Kwns4ox8IphGTzjo)._

1. Make sure you have an updated [Java](https://www.java.com/download/ie_manual.jsp) version installed.
2. Go to the official [Minecraft website](https://www.minecraft.net/en-us/download/server) and download the server files.

![Minecraft Server Download](https://github.com/MeistaSoda-Gaming/MS-MinecraftServer/assets/65448960/9b470ae8-7f09-4fe7-8f2c-3d7bca2aa035)

3. Move the **setup.jar** file into an empty folder and execute the file.

![Java Setup File](https://github.com/MeistaSoda-Gaming/MS-MinecraftServer/assets/65448960/5cbeb673-c325-460d-8ed5-b24a0f9d810d)

4. Wait for extraction of the **eula.txt** and open it.

![Extracted Setup Folder](https://github.com/MeistaSoda-Gaming/MS-MinecraftServer/assets/65448960/cb66f9c2-96e8-4a31-8104-8a3d2af94d44)

Change `eula=false` to `eula=true` and save the text file.

![Accepting EULA](https://github.com/MeistaSoda-Gaming/MS-MinecraftServer/assets/65448960/8fad9e01-0ad4-4c38-a683-94c4eed728f4)

5. Execute the **setup.jar** once more for the server to extract all necessary data and files for the server.
The initial setup will take around 1-2 minutes and will say "Done" as soon as the world is created and the server is running.

![Minecraft Server Window](https://github.com/MeistaSoda-Gaming/MS-MinecraftServer/assets/65448960/5ea4c8ae-466f-49b7-a8d6-a50105388909)

Type `help` inside the input field at the server window to receive information to available commands.

6. Jump into the game and join through the server address `localhost` or your local IP-address.

## :two: Importing existing world

If you have created a server, you are able to insert your own singleplayer maps or downloaded maps into the server.
The location of your own Minecraft worlds is in `C:\Users\[USERNAME]\AppData\Roaming\.minecraft\saves`.

First rename the folder **world** in your server folder to f.e. **_world\_old_**.
Now copy one of your worlds into the server folder and rename it into **world**.

![Personal world saves](https://github.com/MeistaSoda-Gaming/MS-MinecraftServer/assets/65448960/4b78a84d-4c27-464e-84fa-1111884bcd62)

![Copy world to server folder](https://github.com/MeistaSoda-Gaming/MS-MinecraftServer/assets/65448960/a20044a8-c70c-4f89-a346-a6df54541e0a)

![Rename world](https://github.com/MeistaSoda-Gaming/MS-MinecraftServer/assets/65448960/631e2a71-9cad-4d16-bf98-c654003eb5d7)

You can then try to start the server via the **server.jar** file. If it doesn't work, go into the folder `C:\Users\[USERNAME]\Desktop\Minecraft Server\world\players` and delete all player files. This should leave that folder empty and help with starting the server.

![Delete player files](https://github.com/MeistaSoda-Gaming/MS-MinecraftServer/assets/65448960/56e361df-a4f0-4d69-bb3d-b788e258bcd3)

Execute the server file once more and the server should now be hosting the imported world.

ENJOY THE GAME! :D
