# Hello Scaloid for gradle

This is a template project that can be a starting point of a new [Scaloid](https://github.com/pocorall/scaloid) project.

This contains minimum code as possible; therefore easy to run, examine and extend.

Prerequisites
-------------
* Android build tool 22.0.1
* Android SDK Level 16
 - Level 16 is required for building, while this app retains runtime compatibility from API Level 10. Please refer to `minSdkVersion` property in `build.gradle`

Build
-----
You can build this project using gradle:

    $ gradlew packageDebug

This will compile the project and generate an APK.

For more command, refer to [gradle-android-scala-plugin](https://github.com/saturday06/gradle-android-scala-plugin).

Is the build too slow?
----------------------
This gradle project works completely. But long build time would matter, which usually takes more than 40 seconds.
We recommend to [build your project with sbt](https://github.com/pocorall/hello-scaloid-sbt), which enables incremental build.
This usually takes only several seconds.

Further Reading
---------------
- [Scaloid](https://github.com/pocorall/scaloid)
- [Scaloid APIdemos](https://github.com/pocorall/scaloid-apidemos)
