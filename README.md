# maven_project

what is mavem ?
Maven is a popular open-source build tool developed by the Apache Group to build, publish, and deploy several projects at once for better project management. The tool provides allows developers to build and document the lifecycle framework.

what is its usage?
Maven is a build automation tool used primarily for Java projects. Maven can also be used to build and manage projects written in C#, Ruby, Scala, and other languages. The Maven project is hosted by the Apache Software Foundation, where it was formerly part of the Jakarta Project

What cmd we have in maven ?
mvn clean :- This command cleans the maven project by deleting the target directory. 
mvn compiler:compile:-This command compiles the java source classes of the maven project.
mvncompiler:testCompile :=This command compiles the test classes of the maven project.
mvn package:= This command builds the maven project and packages them into a JAR, WAR, etc.
mvn install:- This command builds the maven project and installs the project files (JAR, WAR, pom.xml, etc) to the local repository.
mvn validate:- This command validates the maven project that everything is correct and all the necessary information is available.
mvn dependency:tree:- This command generates the dependency tree of the maven project.
mvn deploy:--This command is used to deploy the artifact to the remote repository. The remote repository should be configured properly in the project pom.xml file distributionManagement tag. The server entries in the maven settings.xml file is used to provide authentication details.

maven lifecycle:--
Maven is based around the central concept of a build lifecycle. What this means is that the process for building and distributing a particular artifact (project) is clearly defined.

For the person building a project, this means that it is only necessary to learn a small set of commands to build any Maven project, and the POM will ensure they get the results they desired.

There are three built-in build lifecycles: default, clean and site. The default lifecycle handles your project deployment, the clean lifecycle handles project cleaning, while the site lifecycle handles the creation of your project's web site
