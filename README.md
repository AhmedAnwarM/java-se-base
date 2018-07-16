# Java SE 8 Base Project #

This is a Maven base project that you can use for Java SE development.

## How to run? ##

1. Open a terminal (linux) or command line (windows) in the project's root directory
2. Run the command "mvn clean install". This builds the project to the directory "target"
3. In target directory, you can find a file java-se-base.jar
4. From the project's root directory again, run the command "java -jar target/java-se-base.jar"
5. The main method in class com.sumerge.grad.program.main.Main will run
6. You can choose the main class by opening the MANIFEST.mf file and replacing the existing class with the one you wish to run
