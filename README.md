# ASP.Net

## Table of Contents

| No. |   Questions                                              |
|-----|----------------------------------------------------------|
| 01. |[What is ASP.Net?](#01-what-is-aspnet)|
| 02. |[What are the different validators in ASP.NET?](#02-what-are-the-different-validators-in-aspnet)|
| 03. |[What is ViewState?](#03-what-is-viewstate)|
| 04. |[Where the viewstate is stored after the page postback?](#04-where-the-viewstate-is-stored-after-the-page-postback)|
| 05. |[What are the different Session state management options available in ASP.NET?](#05-what-are-the-different-session-state-management-options-available-in-aspnet)|
| 06. |[What is caching?](#06-what-is-caching)|
| 07. |[What are the different types of caching?](#07-what-are-the-different-types-of-caching)|
| 08. |[List the events in page life cycle](#08-list-the-events-in-page-life-cycle)|
| 09. |[What is the difference between web config and machine config?](#09-what-is-the-difference-between-web-config-and-machine-config)|
| 10. |[What is Cross Page Posting?](#10-what-is-cross-page-posting)|

#### 01. ***What is ASP.Net?***
It is a framework developed by Microsoft on which we can develop new generation web sites using web forms(aspx), 
MVC, HTML, Javascript, CSS etc. Its successor of Microsoft Active Server Pages(ASP). 
Currently there is ASP.NET 4.0, which is used to develop web sites. 
There are various page extensions provided by Microsoft that are being used for web site development. 
Eg: aspx, asmx, ascx, ashx, cs, vb, html, XML etc. 

<div align="right">
    <b><a href="#">back to top</a></b>
</div>

#### 02. ***What are the different validators in ASP.NET?***
    1. Required field Validator
    2. Range Validator
    3. Compare Validator
    4. Custom Validator
    5. Regular expression Validator
    6. Summary Validator
    
<div align="right">
    <b><a href="#">back to top</a></b>
</div> 

#### 03. ***What is ViewState?***
ViewState is used to retain the state of server-side objects between page post backs. 

<div align="right">
    <b><a href="#">back to top</a></b>
</div>

#### 04. ***Where the viewstate is stored after the page postback?***
ViewState is stored in a hidden field on the page at client side. ViewState is transported to the client and back to the server, and is not stored on the server or any other external source. 

<div align="right">
    <b><a href="#">back to top</a></b>
</div>

#### 05. ***What are the different Session state management options available in ASP.NET?***
    1. In-Process
       In-Process stores the session in memory on the web server.
    
    2. Out-of-Process.
       Out-of-Process Session state management stores data in an external server. 
       The external server may be either a SQL Server or a State Server. 
       All objects stored in session are required to be serializable for Out-of-Process state management. 

<div align="right">
    <b><a href="#">back to top</a></b>
</div>

#### 06. ***What is caching?***
Caching is a technique used to increase performance by keeping frequently accessed data or files in memory. 
The request for a cached file/data will be accessed from cache instead of actual location of that file. 

<div align="right">
    <b><a href="#">back to top</a></b>
</div>

#### 07. ***What are the different types of caching?***
ASP.NET has 3 kinds of caching :
* Output Caching,
* Fragment Caching,
* Data Caching.

<div align="right">
    <b><a href="#">back to top</a></b>
</div>

#### 08. ***List the events in page life cycle***
1) Page_PreInit
2) Page_Init
3) Page_InitComplete
4) Page_PreLoad
5) Page_Load
6) Page_LoadComplete
7) Page_PreRender
8) Render

<div align="right">
    <b><a href="#">back to top</a></b>
</div>

#### 09. ***What is the difference between web config and machine config?***
Web config file is specific to a web application where as machine config is specific to a machine or server. 
There can be multiple web config files into an application where as we can have only one machine config file on a server. 

<div align="right">
    <b><a href="#">back to top</a></b>
</div>

#### 10. ***What is Cross Page Posting?***
When we click submit button on a web page, the page post the data to the same page. 
The technique in which we post the data to different pages is called Cross Page posting. 
This can be achieved by setting POSTBACKURL property of the button that causes the postback. 
Findcontrol method of PreviousPage can be used to get the posted values on the page to which the page has been posted. 

<div align="right">
    <b><a href="#">back to top</a></b>
</div>
