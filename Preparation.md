## client-server model
-  It's a distributed application between client(requester) and server(provider).
- To precise it's all about the client sends a request to the server via a communication-channel which is the **internet** and the server respond back.
- **HTTP** is the communication language between client and server.
    ___
## frontend Vs backend
#### frontend
> - It's every thing you can see as a client.
> - The code runs at the client-side only, the server sends files to the brwoser and browser rendering it. 
> - **HTML** is the standard markup language for creating web pages, it describes the structure of the page.
> - **CSS** gives the html elements its style.
> - **JS** gives the elements its interactivity.
#### backend 
> - It's what the user never see.
> - The code runs at the server-side, and never be sent to the user.
> - **PHP** is most popular general-purpose scripting language, and specially sutable for web development.
> - The **HTML** statements can be written in the .php files.
  ___
## static-websites and dynamic ones
#### static-website
> The client send a request for a file and the server send this file to the client as it is stored in the server files.
- This file is a ==**hard-coded**== file.
  ***hard-coded*** **:** is a file written so that it can only be modified by the creator from the source code.
#### dynamic-website
> The data in the file sent to the client depend on his requested **URL**.
- [This is a chart of a requst to a dynamic website](https://ibb.co/7S5JB3G).

**Note**: 
- if the facebook was a static-website there must be three-billion file for only the profile page of each user.
- web application constructs data in the html templates(files).
    ___
## design pattern in web application
pattern is the design of classes, and it's the solution of complexity.
<br>
#### compound pattern
is more than one pattern into a single one design.
+ The most popular compound pattern is **MVC**
+ **MVC** separat the functionalities through **view**, **model** and **controller**.
+ Model is dealing with the database , view dealing with the user and controller works as a medium.
> The overall architecture is the **client-server** model.
> The software architecture is **MVC**.
    ___
## HTTP request
consists of **verb** and **path**  
**path** is the what >> the resource.  
**verb** is the how  >> the method.



