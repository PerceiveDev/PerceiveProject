# PerceiveProject
A template project for Perceive projects

## Usage
Just [download this project](https://github.com/PerceiveDev/PerceiveProject/archive/master.zip), fill in the variable placeholders in the `pom.xml` and `plugin.yml`, and rename the files in the `src/main/java` folder to their proper names.

### CLI tool
A better alternative is to usage the [PerceivePluginArchetype](https://github.com/PerceiveDev/PerceivePluginArchetype), a Maven archetype for Bukkit plugins. *PerceiveProject* is meant as a backup for *PerceivePluginArchetype* so if you fail to get the archetype working, you can still use the project template. The main difference is you have to manually replace all variable references with this. _**Note: There will be a better command-line tool for creating projects as soon as I (Rayzr) can figure out how to make it work on Windows as well as Unix-based systems.**_

## Naming
The name should be captialized correctly, such as `SomePlugin`, and the artifact ID should be an exact copy of the name, but all lower-case. The group ID should be `com.perceivedev`, unless you are using this for a personal project. If you change the group ID, make sure to also rename the folders, change the package declaration in the main class, and update the `plugin.yml` so it points to the new location of the plugin's main class.
