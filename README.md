# apache-cxf-helloworld
TomEE Hello Worlds with Apache CXF implementations of JAX-RS and JAX-WS.

Follow the Setup Steps below.

*************** Setup Steps ***************

Clone the apache-cxf-helloworld repo.
Copy apache-cxf-helloworld/setup/tomee.xml to TOMEE_HOME/conf.
Copy apache-cxf-helloworld/setup/logging.properties to TOMEE_HOME/conf.
Run build.gradle.
Copy apache-cxf-helloworld/build/libs/apache-cxf-helloworld.war to TOMEE_HOME/webapps.
Tail TOMEE_HOME/logs/catalina.out.

*************** Execution Steps ***************

Execute REST service using curl or Google Chrome Advanced REST Client 
(https://chrome.google.com/webstore/detail/advanced-rest-client/hgmloofddffdnphfgcellkdfbfbjeloo?hl=en-US)

Execute SOAP servuce using SOAP UI. Point to wsdl file when creating SOAP UI project
(http://localhost:8080/apache-cxf-helloworld/webservices/HelloWorldWSImpl?wsdl)
