Parrot [CURRENT BUILD STATUS OF RELEASE PREVIEW]: Revision 12 - 1.20
===========

The new fork of PaperMC with 1.20 support!


```xml
<dependency>
    <groupId>com.zoey.parrotmc</groupId>
    <artifactId>parrot-loader-api</artifactId>
    <version>1.20-relPRE-12</version>
    <scope>provided</scope>
</dependency>
 ```
How To (Compiling Jar From Source)
------
To compile Paper, you need JDK 17 and an internet connection.

Clone this repo, run `./gradlew applyPatches`, then `./gradlew createReobfBundlerJar` from your terminal. You can find the compiled jar in the project root's `build/libs` directory.

To get a full list of tasks, run `./gradlew tasks`.
