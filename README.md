# Spark Challenge
--------------------
#### Link to repo:
https://github.com/PoojithaSingam/sparkChallenge

#### Steps to follow
-  Open Root folder in VS Code
-  Create a mvn project of type archetype-quickstart-jdk8 with latest version
-  Give the required field in terminal  to create our project
-  Close VS Code and open pom file and make necessary changes in pom file.
-  Run the following commands

```PowerShell
mvn clean
mvn compile
mvn assembly:single
```
-  Execute using the below given command by changing the unique group Id and also the name of the input text file

```Bash
java -cp target/spark-challenge-1.0.0-jar-with-dependencies.jar edu.nwmissouri.singam.App "input.txt"
```
-  Once all the commands runs successfully open our result folder and explore output in part-00000.
