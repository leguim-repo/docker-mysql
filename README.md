# MySQL Docker for Pom Hotel

Execute 01_build.sh in order to download and build MySQL Docker image.  That script create the database schema and populate it.  

The MySQL datas are in a docker persistent volume named pom-mysql-db-data.  

The script 99_startPom-MySQL-Container.sh start the container.  
The script 98_stopPom-MySQL-Container.sh stop the container.  

---
![Coded in Barcelona](codedinbcn.png "Coded in Barcelona")
