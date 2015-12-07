Super Mario Bros. Clone
==========
![image](logo.png)

A clone of Super Mario Bros. 16-bit version game.

### About
This game is based of the Super Mario Bros. 16-bit version featured on Super Mario All-Starts for the Super Nintendo (SNES). The game is written in Java an using the [LibGdx](http://libgdx.badlogicgames.com/) engine.

Features of the game:
* Mini Mario turns into big Mario with the help of mushrooms.
* If you walk of the platform into the deep, you will die.
* Goomba's (enemies) will kill Mario, Mario can kill the Goomba's by jumping on their heads.
* Jump up against bricks, they will be destroyed if you are big Mario.
* Bonus bricks which can contain multiple Mushrooms.
* At the end of the level you can slide down the flag, you will then walk automatically to the castle. The game will then restart.
* Sound effects and music.

The project is updated to work with the new LibGdx release (1.4.1) which uses Gradle and has a different structure..

I am no longer adding new features to the game. Though, if you still find some bugs, just let me know (I might fix it)!

Here is a video demo:

[![Youtube video](http://img.youtube.com/vi/GxyUYAL4O7I/0.jpg)](http://www.youtube.com/watch?v=GxyUYAL4O7I)

### Download

[Click here](https://github.com/ArjanFrans/mario-game/releases/download/1/mario-game-1.0.jar) to download the game. You need [Java](https://java.com/nl/download/) to be able to run it.

### Development setup

1.  Install Java JDK. Make sure JAVA_HOME is in your environment variables.
2.   Install the Android SDK and setup an Android platform. Make sure to set ANDROID_HOME in your environment variables.
3.  Install Gradle.
3.  Clone this repository. Open the project in your IDE.
If you are using IntlliJ the Gradle plugin should be installed by default. The gradle project settings should popup.
Accept the default settings. If it is missing the Android SDK
 or JAVA_HOME make sure to setup Java and Android SDK in your environment variables.
4. Edit your run configuration. Make sure `android/assets` is set as your working directory!
5. When running in IntelliJ it should automatically compile.

Setting up the project can be a pain, which I have experienced myself, even when I tried to set up my own project again.
Please let me know if you are having trouble!



## TO SUBMIT:

https://classroom.github.com/assignment-invitations/38bf51d0641ee58c5888c1e112fcc37d

## Submission Procedure with Git: 

```shell
$ cd /path/to/your/android/app/
$ git init
$ git add –all
$ git commit -m "your message, e.x. Assignment 1 submission"
$ git remote add origin <Assignment link copied from assignment github, e.x. https://github.com/DeLaSalleUniversity-Manila/secondactivityassignment-melvincabatuan.git>
$ git push -u origin master
<then Enter Username and Password>
```
 
 ## Videocapture:
-----------

 https://youtu.be/kdzj83gVrrE


### This Fork

```shell
$ ./gradlew build
Downloading https://services.gradle.org/distributions/gradle-2.2-all.zip
................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................
Unzipping /home/cobalt/.gradle/wrapper/dists/gradle-2.2-all/vk5dmipuddvq5mpa6rlusql2u/gradle-2.2-all.zip to /home/cobalt/.gradle/wrapper/dists/gradle-2.2-all/vk5dmipuddvq5mpa6rlusql2u
Set executable permissions for: /home/cobalt/.gradle/wrapper/dists/gradle-2.2-all/vk5dmipuddvq5mpa6rlusql2u/gradle-2.2/bin/gradle
Configuration on demand is an incubating feature.
Download https://jcenter.bintray.com/de/richsource/gradle/plugins/gwt-gradle-plugin/0.6/gwt-gradle-plugin-0.6.pom
Download https://repo1.maven.org/maven2/org/robovm/robovm-gradle-plugin/1.0.0/robovm-gradle-plugin-1.0.0.pom
Download https://repo1.maven.org/maven2/org/robovm/robovm-dist-compiler/1.0.0/robovm-dist-compiler-1.0.0.pom
Download https://repo1.maven.org/maven2/org/robovm/robovm-dist-parent/1.0.0/robovm-dist-parent-1.0.0.pom
Download https://repo1.maven.org/maven2/org/robovm/robovm-parent/1.0.0/robovm-parent-1.0.0.pom
Download https://jcenter.bintray.com/de/richsource/gradle/plugins/gwt-gradle-plugin/0.6/gwt-gradle-plugin-0.6.jar
Download https://repo1.maven.org/maven2/org/robovm/robovm-gradle-plugin/1.0.0/robovm-gradle-plugin-1.0.0.jar
Download https://repo1.maven.org/maven2/org/robovm/robovm-dist-compiler/1.0.0/robovm-dist-compiler-1.0.0.jar
Download https://repo1.maven.org/maven2/com/badlogicgames/gdx/gdx-platform/1.5.5/gdx-platform-1.5.5.pom
Download https://repo1.maven.org/maven2/com/badlogicgames/gdx/gdx-parent/1.5.5/gdx-parent-1.5.5.pom
Download https://repo1.maven.org/maven2/org/sonatype/oss/oss-parent/5/oss-parent-5.pom
Download https://repo1.maven.org/maven2/com/badlogicgames/gdx/gdx-freetype-platform/1.5.5/gdx-freetype-platform-1.5.5.pom
Download https://repo1.maven.org/maven2/com/badlogicgames/gdx/gdx-platform/1.5.5/gdx-platform-1.5.5-natives-armeabi.jar
Download https://repo1.maven.org/maven2/com/badlogicgames/gdx/gdx-platform/1.5.5/gdx-platform-1.5.5-natives-armeabi-v7a.jar
Download https://repo1.maven.org/maven2/com/badlogicgames/gdx/gdx-platform/1.5.5/gdx-platform-1.5.5-natives-x86.jar
Download https://repo1.maven.org/maven2/com/badlogicgames/gdx/gdx-freetype-platform/1.5.5/gdx-freetype-platform-1.5.5-natives-armeabi.jar
Download https://repo1.maven.org/maven2/com/badlogicgames/gdx/gdx-freetype-platform/1.5.5/gdx-freetype-platform-1.5.5-natives-armeabi-v7a.jar
Download https://repo1.maven.org/maven2/com/badlogicgames/gdx/gdx-freetype-platform/1.5.5/gdx-freetype-platform-1.5.5-natives-x86.jar
Download https://repo1.maven.org/maven2/com/badlogicgames/gdx/gdx-backend-android/1.5.5/gdx-backend-android-1.5.5.pom
Download https://repo1.maven.org/maven2/com/badlogicgames/gdx/gdx-freetype/1.5.5/gdx-freetype-1.5.5.pom
Download https://repo1.maven.org/maven2/com/badlogicgames/gdx/gdx/1.5.5/gdx-1.5.5.pom
Download https://repo1.maven.org/maven2/com/badlogicgames/gdx/gdx/1.5.5/gdx-1.5.5.jar
Download https://repo1.maven.org/maven2/com/badlogicgames/gdx/gdx-freetype/1.5.5/gdx-freetype-1.5.5.jar
Download https://repo1.maven.org/maven2/com/badlogicgames/gdx/gdx-backend-android/1.5.5/gdx-backend-android-1.5.5.jar
:android:preBuild
:android:compileDebugNdk
:android:preDebugBuild
:android:checkDebugManifest
:android:prepareDebugDependencies
:android:compileDebugAidl
:android:compileDebugRenderscript
:android:generateDebugBuildConfig
:android:generateDebugAssets UP-TO-DATE
:android:mergeDebugAssets
:android:generateDebugResValues
:android:generateDebugResources
:android:mergeDebugResources
:android:processDebugManifest
:android:processDebugResources
:android:generateDebugSources
:core:compileJava
warning: [options] bootstrap class path not set in conjunction with -source 1.6
1 warning
:core:processResources UP-TO-DATE
:core:classes
:core:jar
:android:compileDebugJava
:android:preDexDebug
:android:dexDebug
:android:processDebugJavaRes UP-TO-DATE
:android:validateDebugSigning
:android:packageDebug
:android:zipalignDebug
:android:assembleDebug
:android:preReleaseBuild
:android:checkReleaseManifest
:android:prepareReleaseDependencies
:android:compileReleaseAidl
:android:compileReleaseRenderscript
:android:generateReleaseBuildConfig
:android:generateReleaseAssets UP-TO-DATE
:android:mergeReleaseAssets
:android:generateReleaseResValues
:android:generateReleaseResources
:android:mergeReleaseResources
:android:processReleaseManifest
:android:processReleaseResources
:android:generateReleaseSources
:android:compileReleaseJava
:android:lintVitalRelease SKIPPED
:android:compileReleaseNdk
:android:preDexRelease
:android:dexRelease
:android:processReleaseJavaRes UP-TO-DATE
:android:packageRelease
:android:assembleRelease
:android:assemble
:android:compileLint
:android:lint
Ran lint on variant release: 2 issues found
Ran lint on variant debug: 2 issues found
Wrote HTML report to file:/home/cobalt/repos/mario-game/android/build/outputs/lint-results.html
Wrote XML report to /home/cobalt/repos/mario-game/android/build/outputs/lint-results.xml
:android:check
:android:build
:core:assemble
:core:compileTestJava UP-TO-DATE
:core:processTestResources UP-TO-DATE
:core:testClasses UP-TO-DATE
:core:test UP-TO-DATE
:core:check UP-TO-DATE
:core:build
...

BUILD SUCCESSFUL

Total time: 59 mins 12.34 secs
```


