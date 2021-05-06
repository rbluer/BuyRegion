# [BuyRegion](https://www.spigotmc.org/resources/buyregion-updated-for-1-13.60189/)

This is an updated version of [BuyRegion](https://www.spigotmc.org/resources/buyregion.507/) for Minecraft 1.13.

Full credit goes to [Luke199](https://www.spigotmc.org/resources/authors/luke199.2113/).

If anyone has a problem with me publishing this resource, please let me know.



# Building This Project

First fork or clone the project and setup a local instance in your development environment. For example, within Eclipse, choose the option `File -> Import... -> Gradle / Existing Gradle Project ->` then follow the prompts to select the directory and then import it.


At the root of the project's directory, create a new directory name `libs`.  Then download a copy of RedProtect and place it within that libs directory.  Make sure the name of that jar matches what's in the file `build.gradle`.  For example:

```
    implementation files('libs/RedProtect-7.6.2-b247-Universal.jar')
```

Then run the gradle build either through your IDE, or manually from a command prompt using `./gradlew build`.  Note the `./` prefix may, or may not be required.


You can then find the build artifact under the path `build/libs/` and generated jar's name will include the property `pluginVersion`.  For example if `pluginVersion=2.2.4-alpha.1` it will generate the build artifact of `build/libs/BuyRegion-2.2.4-alpha.1.jar`.


