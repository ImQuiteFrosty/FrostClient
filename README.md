
<p align="center">
  <img src="/screenshots/FrostLogoV2.png" alt="Logo" width="200" height="200">
</p>


# FrostClient
FrostClient is an open source Minecraft PVP Client(Based on CloudClient) for 1.7.10 and 1.8.9 using the Forge API.

## Downloading
- Coming Soon...

## Screenshots
### TitleScreen
![TitleScreen](https://media.discordapp.net/attachments/1117324391869595680/1122617589688979496/image.png?width=1154&height=610)

### HudEditor
![TitleScreen](https://media.discordapp.net/attachments/1117324391869595680/1122617883822936106/image.png?width=1157&height=610)

### ModMenu
![TitleScreen](https://media.discordapp.net/attachments/1117324391869595680/1122618027217780827/image.png?width=1149&height=610)

## Workspace Setup
1. Clone or download the repository either using git or the zip download.
2. Open the folder, either `1.7.10\cloudclient` or `1.8.9\cloudclient` and copy the path.
3. Open a command proment or terminal and change the directory to the copied path.
```
cd C:\User\Desktop\cloudclient-main\<version>\cloudclient
```
4. Creating the workspace for your IDE <br>
- IntelliJ IDEA
```
gradlew setupDecompWorkspace idea
```
- Eclipse
```
gradlew setupDecompWorkspace eclipse
```
5. Open the project with your preferred IDE. Don't import it as a gradle project.
6. To get Mixins working in a Dev Environment, add the args below, to your program arguments.
```
--tweakClass org.spongepowered.asm.launch.MixinTweaker --mixin mixins.cloudmc.json
```

## Building
1. Open either the `1.7.10\cloudclient` or `1.8.9\cloudclient` folder and copy the path.
2. Open a command proment or terminal and change the directory to the copied path.
```
cd C:\User\Desktop\cloudclient-main\<version>\cloudclient
```
3. Make a build
```
gradlew build
```
You will find the new build in
```
C:\User\Desktop\cloudclient-main\<version>\cloudclient\build\libs
```
4. Copy the .jar file and paste it into your mods folder and launch forge for your version.

## Contributions
Feel free to fork this project, make changes and finally make a pull request to the development branch.

## License
This project is licensed under the GNU Lesser General Public License v3.0

Permissions:
- Modification 
- Distribution 
- Private use

Conditions:
- License and copyright notice
- State changes 
- Disclose source
- Same license 

This project uses code from:
- superblaubeere27 (Font Renderer) https://github.com/superblaubeere27
- LaVache-FR (AnimationUtil) https://github.com/LaVache-FR
- Moulberry (MotionBlur) https://github.com/Moulberry
