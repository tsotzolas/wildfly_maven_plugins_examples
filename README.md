## Wildfly Maven Plugin Examples

https://docs.jboss.org/wildfly/plugins/maven/latest/

Some examples for Wildfly Maven Plugin with Mysql

All the example work with Wildfly 10

Add Mysql JDBC driver

Add Datasource to Wildfly Server

Example for multiple server Deployment


## Instructions for addDatasource and addJDBCDriver 
* Check out the project 
* Go to the appropriate folder, depending on what you want to do (addDatasource or addJDBCDriver)
* Put your's settings in pom.xml in the properties section

#### Execute 

```
mvn clean 
```

```
mvn install 
```


## Deploy To multiple Wildfly Servers

Use the pom.xml in this module as a template for your's pom.xml

For deploy the application execute 

```
 mvn wildfly:deploy -P wildfly-deploy-a,wildfly-deployc-b
```

If you are using Jenkins 

![Jenkin's Setup](https://github.com/tsotzolas/Photos/blob/master/Wildfly_maven_plugin/jenkins.png?raw=true)

