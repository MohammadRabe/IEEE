## HTTP
* HTTP allows the web-based devices to communicate and exchange the data.
* HTTP is the messanger of the web.
* It's a TCP/IP based.
* It's connectionless ... means that it stop the connection after request then connect > respond > stop.
* It's stateless so the client and server don't know about each other except when request or response and when the connection ended they need to send information as very first process to connect.
<br>
#### HTTP message
it consists of header fields and they are as follow
**general**, **request**, **respond** and each contains 
| **General** | **Request** | **Response** |
| --- | --- | --- |
| request URL, request method and status-code | cookies, content-type and lenght, authorization and user-agent |  server, content-type and length, set-cookies and date |  

- For each request there is a **status-code** describes the response of the server.
- 
| **1xx** | **2xx** | **3xx** | **4xx** | **5xx** |
| ---     | ---     | ---     | ---     | ---     |
|request recieved and processing|request recieved and accepted| redirection stuff|client error|server error|

#####most familiar status-codes
**200**: Ok 
**201**: Ok, created (when post or put method)
**204**: No content (a response with no body)
**301**: Moves to new URL
**304**: Not modified (this page did not modified from last open)
**400**: Bad request (a malformed request for example)
**404**: File not found
**500**: Server error