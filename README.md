# LauncherProject
An open source Minecraft Launcher that supports multiple profiles, modpacks, mobs, and is really just easy to use.

## (Name TDB)

## Project Structure

##### [`app`](https://github.com/BlazingTide/LauncherProject/tree/main/app) -> The source code for the Desktop Launcher. Utilies [`tauri`](https://tauri.app/) and [`vue 3.0`](https://vuejs.org/).
##### [`net`](https://github.com/BlazingTide/LauncherProject/tree/main/net) -> Contains folders relating to the HTTP Service side of the project that handles metrics and performance tracking
##### [`net/api`](https://github.com/BlazingTide/LauncherProject/tree/main/net/api) -> The REST Api written in Kotlin & utilizes Ktor. Serves & receives metrics data aswell as facilitates Mod & Modpack data alongside creation of such modpacks
##### [`net/frontend`](https://github.com/BlazingTide/LauncherProject/tree/main/net) -> The frontend which contains the website *(TDB)*.
  
