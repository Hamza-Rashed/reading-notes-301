# What is Node.js?

Node.js is a server-side platform built on Google Chrome's JavaScript Engine (V8 Engine). 
Node.js was developed by Ryan Dahl in 2009 and its latest version is v0.10.36. The definition of 
Node.js as supplied by its official documentation is as follows −

    Node.js is a platform built on Chrome's JavaScript runtime for easily building fast and scalable 
    network applications. Node.js uses an event-driven, non-blocking I/O model that makes it lightweight
    and efficient, perfect for data-intensive real-time applications that run across distributed devices.

Node.js is an open source, cross-platform runtime environment for developing server-side and networking 
applications. Node.js applications are written in JavaScript, and can be run within the Node.js runtime 
on OS X, Microsoft Windows, and Linux.

Node.js also provides a rich library of various JavaScript modules which simplifies the development of 
web applications using Node.js to a great extent.

![](https://www.cisin.com/coffee-break/images/easyblog_articles/1000/01.jpg)

# Express js 
Express is a minimal and flexible Node.js web application framework that provides a robust set of features to develop web and mobile applications. 
It facilitates the rapid development of Node based Web applications. Following are some of the core features of Express framework −

    Allows to set up middlewares to respond to HTTP Requests.

    Defines a routing table which is used to perform different actions based on HTTP Method and URL.

    Allows to dynamically render HTML Pages based on passing arguments to templates.

Installing Express

Firstly, install the Express framework globally using NPM so that it can be used to create a web application using node terminal.

``` $ npm install express --save ```

The above command saves the installation locally in the node_modules directory and creates a directory express inside node_modules. 
You should install the following important modules along with express −

    body-parser − This is a node.js middleware for handling JSON, Raw, Text and URL encoded form data.

    cookie-parser − Parse Cookie header and populate req.cookies with an object keyed by the cookie names.

    multer − This is a node.js middleware for handling multipart/form-data.

``` $ npm install body-parser --save ```
``` $ npm install cookie-parser --save``` 
```$ npm install multer --save ```

![](https://stackabuse.com/content/images/2020/01/authentication-and-authorization-in-expressjs-using-jwt-cover.png)



