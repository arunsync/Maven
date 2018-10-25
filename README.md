# Maven

1. Build Life Cycle
2. Consist of Phases
    1. validate (We won't explicitly call, it check it is on order, pom in place)
    2. compile (comiple the java files and generate .class files. It will create the target folder and place all the class files)
    3. test (to run the test cases)
    4. package (If all the above phases are successfully completed, it will package the class files in to jar or war)
    5. install (Installs/publish that package/artifact(jar/war) to local maven repo)-this is maven specific.Nothing to do with app server.
    6. deploy (Installs/publish that package/artifact(jar/war) to remote maven repo)-this is maven specific.Nothing to do with app server.
3. Specify the build phase you need, previous phases automatically run.

Commands to run the maven (you should be on the location where pom.xml is present)
  1. mvn clean (delete the )
  2. mvn compile
  3. mvn package
  
  SNAPSHOT - version means, it is a initial version and it is stil under development
