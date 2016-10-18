### Project Creation

Download the "Setup App" from https://libgdx.badlogicgames.com/download.html to "~/software/LibGDX"

```sh
~/software/LibGDX$ java -version
java version "1.8.0_65"
Java(TM) SE Runtime Environment (build 1.8.0_65-b17)
Java HotSpot(TM) 64-Bit Server VM (build 25.65-b01, mixed mode)

~/software/LibGDX$ java -jar gdx-setup.jar
Usage: GdxSetup --dir <dir-name> --name <app-name> --package <package> --mainClass <mainClass> --sdkLocation <SDKLocation> [--excludeModules <modules>] [--extensions <extensions>]
dir ... the directory to write the project files to
name ... the name of the application
package ... the Java package name of the application
mainClass ... the name of your main ApplicationListener
sdkLocation ... the location of your android SDK. Uses ANDROID_HOME if not specified. Ignored if android module is excluded
excludeModules ... the modules to exclude on the project generation separated by ';'. Optional
extensions ... the extensions to include in the project separated by ';'. Optional
```

