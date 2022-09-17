# SPRING_JDBC_DEMO



This is sample Project for demonstration of Spring JDBC 
  - In order to configure the project you need to follow the some steps.
  - Add Spring JDBC specific latest libraries mysql-connector-java.jar, org.springframework.jdbc.jar and org.springframework.transaction.jar in the project.
  - Create a Student table in database like given below.
  

              ```
              CREATE TABLE Student(
                 ID   INT NOT NULL AUTO_INCREMENT,
                 NAME VARCHAR(20) NOT NULL,
                 AGE  INT NOT NULL,
                 PRIMARY KEY (ID)
              );
              ```
  - After completing the above steps right click on Main file then run as Java Application
  - Check the Student table where information is stored or not.
