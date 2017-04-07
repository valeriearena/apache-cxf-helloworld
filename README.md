# tomee-apache-cxf-hello-world
TomEE Hello Worlds with Apache CXF implementations of JAX-RS and JAX-WS.

Follow the Setup Steps below.

*************** Setup Steps ***************

1. Clone the apache-cxf-helloworld repo.
2. Copy apache-cxf-helloworld/setup/tomee.xml to TOMEE_HOME/conf.
3. Copy apache-cxf-helloworld/setup/logging.properties to TOMEE_HOME/conf.
4. Run build.gradle.
5. Copy apache-cxf-helloworld/build/libs/apache-cxf-helloworld.war to TOMEE_HOME/webapps.
6. Tail TOMEE_HOME/logs/catalina.out.

*************** Execution Steps ***************

Execute REST service using curl or Google Chrome Advanced REST Client 
(https://chrome.google.com/webstore/detail/advanced-rest-client/hgmloofddffdnphfgcellkdfbfbjeloo?hl=en-US)

Execute SOAP servuce using SOAP UI. Point to wsdl file when creating SOAP UI project
(http://localhost:8080/apache-cxf-helloworld/webservices/HelloWorldWSImpl?wsdl)
