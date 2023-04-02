# Sublime-Text-4-Build

Java Make executable .jar file: <br>

1. Compile .java file into binary .class code: javac myFile.java
2. Create in the same folder .mf file (manifest file) with this syntax: Main-Class: myFile
3. jar -cvmf myFile.mf myFile.jar myFile.class
