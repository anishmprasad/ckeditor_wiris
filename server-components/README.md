
## Installation instructions

WIRIS EDITOR server components are available as a Java and ASP .NET web applications.

All services offered by WIRIS EDITOR server components are stateless. Consequently, WIRIS EDITOR has compatibility with distributed server environments.

### Installing as Java Web application

#### Requirements

1. Oracle Java 1.6 or higher
2. Java application server

#### Installation

1. Download the Java version of the WIRIS editor - server components.
2. Deploy the war file into your application server.
3. Product key: For version 3.5.5 and higher, you need to include your product key in the WEB-INF/web.xml file located inside the war file. The license will be validated against our server whenever you restart your application.


#### Configuring your plugins
In case you are using the WIRIS plugins for editing formulas, you will need to change the `configuration.ini` file with the following values:
```java

wirisimageservicehost = <your-domain>
wirisimageserviceport = 80
wirisimageservicepath = /<context>/render

```
### Installing as ASP .NET Web application

#### Requirements

1. .NET Framework 2.0 or higher
2. IIS 5.1 or higher

#### Installation

1. Download the ASP .NET version of the WIRIS editor - server components.
2. Deploy the zip file into IIS with ASP .NET enabled and create a Web application.
3. Product key: From version 3.11.1 you need to include your product key in WIRISeditor `Web.config` file. The license will be validated against our server whenever you restart your application.

Note: If you're using a version prior to IIS 7

Open IIS and look for the folder resources/fonts
Right click on it and choose Properties
Go to HTTP Headers tab and add the following one
```
Custom Header Name = Access-Control-Allow-Origin
Custom Value Name    = *
```
Feel free to move files around and create your own `Web.config` file.

Note: If you use .NET 4.0 or above use the values of Web.config4.0.

#### Testing the application
You can test the application typing the URL in your browser

http://<your-domain>/<web-app-path>/editorservice.aspx/render?mml=<mi>x</mi>
#### Configuring your plugins

In case you are using the WIRIS plugins for editing formulas, you will need to change the configuration.ini file with the following values:
```
wirisimageservicehost = <your-domain>
wirisimageserviceport = 80
wirisimageservicepath = /<web-app-path>/editorservice.aspx/render
```
