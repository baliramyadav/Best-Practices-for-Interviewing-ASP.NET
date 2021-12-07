# Best-Practices-for-Interviewing-ASP.NET
Best Practices for Interviewing  ASP.NET C# with Question Answer
 

Basic interview questions for asp.net developer:


ASP.NET Interview Questions
A list of top frequently asked ASP.NET interview questions and answers are given below.
1) What is ASP?
ASP stands for Active Server Pages. It is also known as classic ASP. It is a server-side technology provided by Microsoft which is used to create dynamic and user-friendly web pages. It uses different scripting languages to create dynamic web pages which can be run on any browsers.
________________________________________
2) What is ASP.NET?
ASP.Net is a specification by Microsoft which is used to create web applications and web services. It is a part of ".Net framework". You can create ASP.Net applications in most of the .Net compatible languages like Visual Basic, C#, etc. ASP.Net provides much better performance than scripting languages.
________________________________________
3) What is the difference between the ASP and ASP.NET?
The main difference between ASP and ASP.Net is that ASP is interpreted, while ASP.Net is compiled. ASP uses VBScript, therefore when the ASP page is executed, it is interpreted. On the other hand, ASP.Net uses .Net languages like C# and VB.NET, which is compiled to Microsoft intermediate language.
________________________________________
4) What is IIS?
IIS stands for Internet Information Services. It is created by Microsoft to provide Internet-based services to ASP.NET Web applications.
________________________________________
5) What is the usage of IIS?
Following are the main usage of IIS:
o	IIS is used to make your computer to work as a Web server and provides the functionality to develop and deploy Web applications on the server.
o	IIS handles the request and response cycle on the Web server.
o	IIS also offers the services of SMTP and FrontPage server extensions.
o	The SMTP is used to send emails and use FrontPage server extensions to get the dynamic features of IIS, such as form handler.
________________________________________
6) What is a multilingual website?
If a website provides content in many languages, it is known as a multilingual website. It contains multiple copies of its content and other resources, such as date and time, in different languages.
________________________________________
7) What is caching? Explain.
Caching is the technique which facilitates you to store frequently used items in memory so that they can be accessed more quickly.
________________________________________
8) what are the main requirements for caching?
o	By caching the response, your request is served by the response already stored in memory.
o	You must be very careful while choosing the items to cache because Caching incurs overhead.
o	A frequently used web form which data doesn't frequently change is good for caching.
o	A cached web form freezes form?s server-side content, and changes to that content do not appear until the cache is refreshed.
________________________________________
9) What are the advantages of ASP.NET?
ASP.Net is the next generation of ASP technology platform. It is superior to ASP in the following ways:
o	Highly Scalable
o	Compiled Code
o	User Authentication
o	Language Support
o	Third party control
o	Configuration and Deployment are easy.
o	Object and Page caching
o	Strict coding requirements
________________________________________
10) What is the concept of Postback in ASP.NET?
Postback is a request which is sent from a client to the server from the same page user is working with. There is an HTTP POST request mechanism in ASP.NET. It posts a complete page back to the server to refresh the whole page.
________________________________________
11) What is the used of "isPostBack" property?
The "IsPostBack" property of page object is used to check that the page is posted back or not.
________________________________________
12) How do you identify that the page is PostBack?
There is a property named "IsPostBack" property in Post object, which can be checked to know that the page is posted back.
________________________________________
13) What is the parent class of all web server control?
System.Web.UI.Control class
________________________________________
14) What is the difference between ASP.NET Webforms and ASP.NET MVC?
ASP.NET Webforms uses the page controller approach for rendering layout. In this approach, every page has its controller.
On the other hand, ASP.NET MVC uses the Front Controller approach. In this approach, there is a common controller for all pages.
________________________________________
15) What is the difference between the GET method () and POST method ()?
No.	get method( )	post method( )
1.	Data is affixed to the URL.	Data is not affixed to the URL.
2.	Data is not secured.	Data is secured.
3.	Data transmission is faster in this method.	Data transmission is comparatively slow.
4.	It is a single call system.	It is a two call system.
5.	Only a limited amount of data can be sent.	A large amount of data can be sent.
6.	It is a default method for many browsers.	It is not set as default. It should be explicitly specified.
________________________________________
16) What is the difference between session object and application object?
The session object is used to maintain the session of each user. A session id is generated if a user enters in the application and when the user leaves the application, the session id is automatically deleted.
On the other hand, the application object is used to store the information and access variables from any page in the application.
________________________________________
17) What is the difference between trace and debug?
Debug class is used to debug builds. Trace class is used for both debug and release builds.
________________________________________
18) What is the difference between client-side and server-side validations in WebPages?
The client-side validation happens at the client's side with the help of JavaScript and VBScript. This validation has occurred before the Web page is sent to the server.
The server-side validation happens at the server side.
________________________________________
19) What is the difference between file-based dependency and key-based dependency?
File-based dependency: File-based dependency facilitates you to save the dependency on a file in a disk.
Key-based dependency: In key-based dependency, you depend on another cached item.
________________________________________
20) What is the difference between globalization and localization?
Globalization: Globalization is a technique to identify the part of a Web application that is different for different languages and separate it out from the web application.
Localization: In localization, you try to configure a Web application so that it can be supported for a specific language or locale.
________________________________________
21) What is the difference between a page theme and a global theme?
Page Theme: The page theme is applied to particular web pages of the project. It is stored inside a subfolder of the App_Themes folder.
Global Theme: The Global theme is applied to all the web applications on the web server. It is stored inside the Themes folder on a Web server.
________________________________________
22) What is the difference between early binding and late binding?
Early Binding: In early binding, a non-virtual method is called which is decided at a compile time.
Late Binding: In late binding, a virtual method is called which is decided at runtime.
________________________________________
23) What is the difference between server-side scripting and client-side scripting?
Server-side scripting: In server-side scripting, all the script are executed by the server and interpreted as needed.
Client-side scripting: In client-side scripting, the script will be executed immediately in the browser such as form field validation, email validation, etc.
The client-side scripting is usually carried out in VBScript or JavaScript.
________________________________________
24) How to sign out from forms authentication?
FormsAuthentication.Signout() method is used to sign out from forms authentication.
________________________________________
25) How to display validation messages in one control?
By the help of ValidationSummary control, we can display all validation messages in one control.
________________________________________
26) What is the difference between authentication and authorization?
Authentication is a process of identifying user whereas authorization is used to check the access rights of an identified user.
________________________________________
27) Which object encapsulates state or data of a user?
Session object.
________________________________________
28) What is ViewState?
ViewState is a feature of ASP.NET to store the values of a page before it is submitted to the server. After posting the page, data from is ViewState is restored.
________________________________________
29) What is ViewState information stored?
It is stored in HTML hidden field.


30) What are the differences between the Response.Write() and Response.Output.Write()?
Response.Write() is used for normal output whereas Response.Output.Write() is used for formatted output.
________________________________________
31) Define the types of configuration files.
There are two types of configuration files:
o	Application Level config = Web.config.
o	Machine Level config = Machine.config.
________________________________________
32) What is the difference between Web config and Machine config files?
Web config file is specific to web application whereas Machine config file is specific to machine or server.
There can be multiple web config files in an application but only one machine config file.
________________________________________
33) What is MVC?
MVC stands for Model View Controller. It is a design pattern that is used to separate business logic and presentation logic. It is used to develop the highly customized application.
The Model represents data, View represents presentation and controller acts as an interface between Model and View.
________________________________________

34) What are the built-in objects in ASP.NET?
The major built-in objects are given below:
o	Application
o	Session
o	Context
o	Request
o	Response
o	Server
o	Trace
________________________________________
35) What do you mean by Role-based security?
Role-based security is used in almost all organization, and the Role-based security assigns certain privileges to each role.
o	Each user is assigned a particular role from the list.
o	Privileges as per role restrict the user's actions on the system and ensure that a user can do only what he is permitted to do on the system.
________________________________________
36) What is a cookie?
A Cookie is a small piece of information which is stored at the client side. There are two types of cookie:
o	Session/Temporary Cookie: valid for a single session
o	Persistent Cookie: valid for multiple session
________________________________________


37) What is the default timeout for a cookie?
30 minutes.
________________________________________
38) How would you turn off cookies on a page of a website?
You have to follow the procedures given below:
o	Use the "Cookie.Discard" property.
o	It gets or sets the discard flag set by the server.
o	When set to true, this property instructs the client application not to save the Cookie on the hard disk of the user at the end of the session.
________________________________________
39) Which protocol is used to call web service?
HTTP protocol.
________________________________________
40) What is the file extension of web service?
The File extension of web service is .asmx.
________________________________________
41) What are the HTML server controls in ASP.NET?
o	HTML server controls are just like HTML elements that we use on the HTML pages.
o	HTML server controls are used to expose properties and events for use.
o	To make these controls programmatically accessible, we specify that the HTML controls act as a server control by adding the runat="server" attribute.
________________________________________

42) What is the use of Global.asax file?
The Global.asax file is used to execute the application-level events and sets application-level variables.
________________________________________
43) What is event bubbling?
When child control sends events to parent, it is termed as event bubbling. Server controls like Data Grid, Data List, and Repeater can have other child controls inside them.


What is session type in asp.net?
ASN:
Session-State modes are 5 type:
InProc mode: which stores session state in memory on the Web server. This is the default.
StateServer mode: which stores session state in a separate process called the ASP.NET state service. This ensures that session state is preserved if the Web application is restarted and also makes session state available to multiple Web servers in a Web farm.
SQLServer mode stores session state in a SQL Server database. This ensures that session state is preserved if the Web application is restarted and also makes session state available to multiple Web servers in a Web farm.
Custom mode: which enables you to specify a custom storage provider.
Off mode: which disables session state.
-------------------extra---------------
There are three kinds of session, and they are listed as follows
1.	Inprocess.
2.	Outprocess.
3.	Sql server session.
where they are stored.
1.	inproc - default stored in web.config.
2.	outproc - stored in server side.
3.	Sql server - stored in database.
You have following types of session management in asp.net which you can define in your web.config file
Session mode="inproc"...means the session will be stored on the webserver within your application session mode="outproc"....means session will be stored on the server outside your application session mode="stateserver"...means session will be stored in a temporary memory in the database session mode="sqlserver"...means session will be stored in the database permanently.


