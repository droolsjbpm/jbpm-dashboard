Distribution Builder
==========================

To generate all the distribution files go to the jbpm-dashboard root directory and type the following command:

    $ mvn clean install -Dfull -DskipTests

Currently, the following artifacts are generated:

* **jbpm-dashbuilder-wildfly10.war:**  Product distribution for the WildFly 10 application server.

  Detailed installation instructions [here](https://github.com/droolsjbpm/jbpm-dashboard/blob/master/jbpm-dashboard-distributions/src/main/wildfly10/README.md).

* **jbpm-dashbuilder-eap6_4.war:**  Product distribution for the JBoss EAP 6.4 application server.

  Detailed installation instructions [here](https://github.com/droolsjbpm/jbpm-dashboard/blob/master/jbpm-dashboard-distributions/src/main/eap6_4/README.md).

* **jbpm-dashbuilder-eap7.war:**  Product distribution for the JBoss EAP 7 application server.

  Detailed installation instructions [here](https://github.com/droolsjbpm/jbpm-dashboard/blob/master/jbpm-dashboard-distributions/src/main/eap7/README.md).

* **jbpm-dashbuilder-tomcat7.war:**  Product distribution for Apache Tomcat 7 server.

  Detailed installation instructions [here](https://github.com/droolsjbpm/jbpm-dashboard/blob/master/jbpm-dashboard-distributions/src/main/tomcat7/README.md).

* **jbpm-dashbuilder-was8.war:**  Product distribution for WebSphere 8.5 server.

  It requires to set up a data source connection for any of the supported databases (at the time of this writing: DB2, Postgres, Mysql, H2, Oracle or SQLServer).

  Detailed installation instructions [here](https://github.com/droolsjbpm/jbpm-dashboard/blob/master/jbpm-dashboard-distributions/src/main/was8/README.md).

* **jbpm-dashbuilder-weblogic12c.war:**  Product distribution for WebLogic 12c server.

It requires to set up a data source connection for any of the supported databases (at the time of this writing: DB2, Postgres, Mysql, H2, Oracle or SQLServer).

Detailed installation instructions [here](https://github.com/droolsjbpm/jbpm-dashboard/blob/master/jbpm-dashboard-distributions/src/main/weblogic12c/README.md).