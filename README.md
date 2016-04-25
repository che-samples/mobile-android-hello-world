# mobile-android-hello-world

Android Hello World Application

# Developer Workspace

[![Contribute](http://beta.codenvy.com/factory/resources/codenvy-contribute.svg)](http://beta.codenvy.com/f?id=pszp1h06t076k093)

# Recipe

FROM [codenvy/ubuntu_android](https://hub.docker.com/r/codenvy/ubuntu_android/)

# How to run

1. Project build is started automatically when a workspace starts. Click the Preview URL, right click on the gray screen and launch the Emulator. It may take a while. 
2. Once the Emulator is started, right click on the gray screen and start the Terminal. In the Terminal run the following command to install apk: `adb install /projects/mobile-android-hello-world/target/mobile-android-java-basic.apk`.
3. Find your application in the Emulator's Menu.
4. Go back to the IDE. Change your application, build it with `build-n-run` command, go to the previously opened VNC window and run `adb install -r /projects/mobile-android-hello-world/target/mobile-android-java-basic.apk` command to see the changes.

| #       | Description           | Command  |
| :------------- |:-------------| :-----|
| 1      | Build and run | `cd ${current.project.path} && mvn clean install` |

