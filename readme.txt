To run follow the following steps.
1. Pull down a copy of the repo to your machine
2. Open project in Eclipse
3. Right click on the project folder
4. Select Maven > Update Project (This refreshes the references to the objects downloaded from the Maven repository)
5. Execute the following command from command line(Assuming that you have Maven 3.5.3 installed on your machine and a JDK in your PATH environment variable). 
    mvn install -Dapikey="<API KEY>"  -Denv="prod"

Troubleshooting: 
In the event of "[ERROR] COMPILATION ERROR :" Please repeat the following steps.
1. Open project in Eclipse
2. Right click on the project folder
3. Select Maven > Update Project
4. Execute the following command from command line
    mvn install -Dapikey="<API KEY>" -Denv="prod"

*******Note that the only environment currently configured is "prod" as I didn't see an option for Dev, Test, or Staging environments.***** 
