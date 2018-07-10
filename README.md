# spring-boot-jooq-liquibase-mysql
Starter project having spring boot, liquibase and JOOQ integration, having DB script creation and Jooq classes at maven build.

After adding your scripts in liquibase change log.
Create the Database on the MYSQL and then run
# mvn clean install 
This will run your liquibase scripts first, then generate JOOQ classes from it.

Have not created a single point for db configuration, they are present in pom and application.properties


For more help:
prasoonanand@ymail.com
