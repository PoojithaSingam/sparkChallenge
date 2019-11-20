# Spark Challenge
--------------------
#### Link to repo:
https://github.com/PoojithaSingam/sparkChallenge

#### Steps to follow
- 1. Open Root folder in VS Code
- 2. Create a mvn project of type archetype-quickstart-jdk8 with latest version
- 3. Give the required field in terminal  to create our project
- 4. Close VS Code and open pom file and make necessary changes in pom file.
- 5. Run the following commands

```PowerShell
mvn clean
mvn compile
mvn assembly:single
```
- 6.Execute using the below given command by changing the unique group Id and also the name of the input text file

```Bash
java -cp target/spark-challenge-1.0.0-jar-with-dependencies.jar edu.nwmissouri.singam.App "input.txt"
```
- 7.Once all the commands runs successfully open our result folder and explore output in part-00000.
