READ ME

Database Project

Connects to users OIT mysql 

FILES
	DatabaseMenu.java
	Patient.java
	TableMethods.java
	mysql-connector-java-5.1.35-bin.jar
	project.sql  (schemas)

COMMAND LINE ****************************************************************
COMPILE: 
	javac -cp ".;mysql-connector-java-5.1.35-bin.jar;" DatabaseMenu.java TableMethods.java Patient.java Worker.java

RUN
	java -cp ".;mysql-connector-java-5.1.35-bin.jar;" DatabaseMenu TableMethods Patient Worker

*************************************************************************


TERMINAL

compile : 
	javac -cp mysql-connector-java-5.1.35-bin.jar DatabaseMenu.java TableMethods.java Patient.java Worker.java

run	: 
	java -cp ".:mysql-connector-java-5.1.35-bin.jar" DatabaseMenu TableMethods Patient Worker