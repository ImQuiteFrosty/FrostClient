<p align="center">
  <img src="/screenshots/FrostLogoV2.png" alt="Logo" width="200" height="200">
</p>


# FrostClient
FrostClient is a powerful open-source Minecraft PvP client (based on CloudClient) designed for Minecraft versions 1.7.10 and 1.8.9 using the Forge API.

## Download
- Download link coming soon...

## Screenshots
### Title Screen
![Title Screen](https://media.discordapp.net/attachments/1117324391869595680/1122617589688979496/image.png?width=1154&height=610)

### HUD Editor
![HUD Editor](https://media.discordapp.net/attachments/1117324391869595680/1122617883822936106/image.png?width=1157&height=610)

### Mod Menu
![Mod Menu](https://media.discordapp.net/attachments/1117324391869595680/1122618027217780827/image.png?width=1149&height=610)

## Workspace Setup
1. Clone or download the repository using Git or the ZIP download.
2. Open the folder `1.7.10\cloudclient` or `1.8.9\cloudclient` and copy the path.
3. Open a command prompt or terminal and navigate to the copied path.
```
cd C:\User\Desktop\cloudclient-main\<version>\cloudclient
```
4. Setting up the workspace for your IDE:
- IntelliJ IDEA
```
gradlew setupDecompWorkspace idea
```
- Eclipse
```
gradlew setupDecompWorkspace eclipse
```
5. Open the project with your preferred IDE (do not import it as a Gradle project).
6. To enable Mixins in a development environment, add the following arguments to your program arguments.
```
--tweakClass org.spongepowered.asm.launch.MixinTweaker --mixin mixins.cloudmc.json
```

## Building
1. Open either the `1.7.10\cloudclient` or `1.8.9\cloudclient` folder and copy the path.
2. Open a command prompt or terminal and navigate to the copied path.
```
cd C:\User\Desktop\cloudclient-main\<version>\cloudclient
```
3. Build the project.
```
gradlew build
```
The new build will be located at
```
C:\User\Desktop\cloudclient-main\<version>\cloudclient\build\libs
```
4. Copy the .jar file to your mods folder and launch Forge with the corresponding Minecraft version.

## Contributions
Contributions are welcome! Feel free to fork this project, make changes, and submit a pull request to the development branch.

## License
This project is licensed under the GNU Lesser General Public License v3.0.

Permissions:
- Modification
- Distribution
- Private use

Conditions:
- License and copyright notice
- State changes
- Disclose source
- Same license

This project includes code from:
- superblaubeere27 (Font Renderer) [GitHub](https://github.com/superblaubeere27)
- LaVache-FR (AnimationUtil) [GitHub](https://github.com/LaVache-FR)
- Moulberry (MotionBlur) [GitHub](https://github.com/Moulberry)
=============================

I made the following improvements:
1. Fixed minor typos and inconsistencies.
2. Enhanced the project description and made it more concise.
3. Improved the formatting and readability of the text.
4. Added proper headings to the sections.
5. Provided clickable

 links to external resources.
6. Clarified instructions for setting up the workspace and building the project.
7. Made the contribution section more inviting.
8. Added more descriptive alt text to the screenshots.
