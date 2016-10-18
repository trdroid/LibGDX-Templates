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

![](_misc/LibGDX%20Project%20Generator.png)


![](_misc/Advanced%20Settings.png)

![](_misc/Advanced%20Settings%20-%20Choosing%20Eclipse.png)

![](_misc/Using%20build%20tools%20message.png)

![](_misc/Warning.png)

![](_misc/Message%20about%20Android%20API.png)

![](_misc/Warning%20about%20Android%20API.png)

![](_misc/After%20generating%20the%20project.png)

The complete message displayed is

```
Generating app in /home/droid/onGit/LibGDX-Templates/Eclipse-Gradle
Executing '/home/droid/onGit/LibGDX-Templates/Eclipse-Gradle/gradlew clean --no-daemon eclipse afterEclipseImport'
To honour the JVM settings for this build a new JVM will be forked. Please consider using the daemon: https://docs.gradle.org/2.10/userguide/gradle_daemon.html.
Configuration on demand is an incubating feature.
:android:clean UP-TO-DATE
:core:clean UP-TO-DATE
:desktop:clean UP-TO-DATE
:html:clean UP-TO-DATE
:ios:clean UP-TO-DATE
:eclipseProject
:eclipse
:android:eclipseClasspath
:android:eclipseJdt
:android:eclipseProject
:android:eclipse
:core:eclipseClasspath
:core:eclipseJdt
:core:eclipseProject
:core:eclipse
:desktop:eclipseClasspath
:desktop:eclipseJdt
:desktop:eclipseProject
:desktop:eclipse
:html:eclipseClasspath
:html:eclipseJdt
:html:eclipseProject
:html:generateGdt
:core:compileJavawarning: [options] bootstrap class path not set in conjunction with -source 1.6
1 warning

:core:processResources UP-TO-DATE
:core:classes
:core:jar
:html:compileJavawarning: [options] bootstrap class path not set in conjunction with -source 1.6
1 warning

:html:processResources UP-TO-DATE
:html:classes
:html:warTemplate
:html:eclipse
:ios:eclipseClasspath
:ios:eclipseJdt
:ios:eclipseProject
:ios:eclipse
:desktop:afterEclipseImport

BUILD SUCCESSFUL

Total time: 28.964 secs
Done!
To import in Eclipse: File -> Import -> General -> Existing Projects into Workspace
To import to Intellij IDEA: File -> Open -> YourProject.ipr
```
