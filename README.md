# BaseJavaMod

## Installation
Download the latest release (`.jar`) [here](). <br>
Put `.jar` to one of these paths:
* Windows: `%AppData%/Mindustry/mods`
* Linux: `~/.local/share/Mindustry/mods` 
* Server: `config/mods`

## Building
* Windows: `gradlew jar`
* Linux/Mac OS: `./gradlew jar`
* Android: `gradlew androidJar` / `./gradlew androidJar`
* Composite: `gradlew deploy` / `./gradlew deploy`

After building, the `.jar` file should be located in `build/libs` folder.

If the terminal returns `Permission denied` or `Command not found`, run `chmod +x ./gradlew`.
