# Simple Compose Example

To build just:

        gradle packageUberJarForCurrentOS

On Linux, the jar is written to ./build/compose/jars/simple-compose-linux-x64-1.0.0.jar. 

So to run at client without gradle:

        java -jar ./build/compose/jars/simple-compose-linux-x64-1.0.0.jar

To run at dev with gradle:

        gradle run
