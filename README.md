# Simple Compose Example

Review gradle files to choose the correct java version expected, i.e. 17. Do not hesitate to update your local gradle and kotlin compiler too.

To build just:

        gradle packageUberJarForCurrentOS

On Linux, the jar is written to ./build/compose/jars/simple-compose-linux-x64-1.0.0.jar. 

So to run at client without gradle:

        java -jar ./build/compose/jars/simple-compose-linux-x64-1.0.0.jar

To run at dev with gradle:

        gradle run
