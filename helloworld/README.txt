This is the example project referred to in the
Struts 2 documentation, Hello World tutorial.
See:  http://struts.apache.org.

To build the application's war file run mvn clean package
from the project's root folder.

The war file is created in the target sub-folder.

Copy the war file to your Servlet container (e.g. Tomcat) and 
then startup the Servlet container.

Or if you are using maven you can run command:
mvn jetty:run

In a web browser go to:  http://localhost:8080/helloworld/index.action.

You should see a web page with Welcome to Struts 2!


Important Note as 2025 for struts2 core 7.0.3 version:
Need to use Tomcat 11 version
Struts.xml need to add "<constant name="struts.allowlist.enable" value="false"/>" in order for the property to work


