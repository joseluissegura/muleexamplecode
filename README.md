This is an example of Mule coding:

 1) an HTML interface
 2) REST inbound/outbound service in a jetty server
 3) SOAP inbound/outbound service
 4) JMS  inbound/outbound service in a activemq server
 5) JDBC inbound/outbound service in a derby server

Instruction to install
 1) download the MuleRestSoapJmsJdbcExample.zip file
    this is a MuleStudio project export file.

 2) expand the file

 3) install MuleStudio

 4) import the project
      File > Import > General > Existing Project into Workspace > Next > Select root directory Browse..
        select the MuleRestSoapJmsJdbcExample directory

 5) run the project
      5.1) In the Package Explorer panel right click "flows > mynewproject.mflow" > Run As > Mule Application

      5.2) Open a Browser

           5.2.1) http://localhost:8080/
                   The browser will show you:
                        Destination: SJO
                        <Submit>

           5.2.2) click Submit
                   The browser will show you a formatted HTML page:
                    Search Results

                    300 American REST
                    300 SouthWest SOAP
                    300 United JMS
                    500 Delta JDBC


                   Each of which the result of the outbound/inbound to a REST,SOAP, JMS
                   and JDBC service in a corresponding server
