# PerceiveProject
A template project for Perceive projects

## Usage
Just [download this project](https://github.com/PerceiveDev/PerceiveProject/archive/master.zip), fill in the variable placeholders in the `pom.xml` and `plugin.yml`, and rename the files in the `src/main/java` folder to their proper names.

## Naming
The name should be captialized correctly, such as `SomePlugin`, and the artifact ID should be an exact copy of the name, but all lower-case. The group ID should be `com.perceivedev`, unless you are using this for a personal project. If you change the group ID, make sure to also rename the folders, change the package declaration in the main class, and update the `plugin.yml` so it points to the new location of the plugin's main class.
