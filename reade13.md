At it's most basic, the web uses a client/server architecture that can be summarized as follows. 
a client (usually a web browser) sends a request to a server (most of the time a web server like Apache,
Nginx, IIS, Tomcat, etc.), using the HTTP protocol. The server answers the request using the same protocol.

![](https://media.prod.mdn.mozit.cloud/attachments/2012/11/20/4291/c1a4a06f1fd9ed42ec5b06e814dd3111/client-server.png)

An HTML form on a web page is nothing more than a convenient user-friendly way to configure an HTTP request to
send data to a server. This enables the user to provide information to be delivered in the HTTP request.

On the client side: defining how to send the data

The <form> element defines how the data will be sent. All of its attributes are designed to let you configure the request to be sent when a user hits a submit button. The two most important attributes are action and method.
The action attribute

The action attribute defines where the data gets sent. Its value must be a valid relative or absolute URL. If this attribute isn't provided, the data will be sent to the URL of the page containing the form — the current page.

In this example, the data is sent to an absolute URL — https://example.com:

<form action="https://example.com">

Here, we use a relative URL — the data is sent to a different URL on the same origin:

<form action="/somewhere_else">

When specified with no attributes, as below, the <form> data is sent to the same page that the form is present on:

<form>

Note: It's possible to specify a URL that uses the HTTPS (secure HTTP) protocol. When you do this, the data is encrypted along with the rest of the request, even if the form itself is hosted on an insecure page accessed using HTTP. On the other hand, if the form is hosted on a secure page but you specify an insecure HTTP URL with the action attribute, all browsers display a security warning to the user each time they try to send data because the data will not be encrypted.

The names and values of the non-file form controls are sent to the server as name=value pairs joined with ampersands. The action value should be a file on the server that can handle the incoming data, including ensuring server-side validation. The server then responds, generally handling the data and loading the URL defined by the action attribute, causing a new page load (or a refresh of the existing page, if the action points to the same page).

How the data is sent depends on the method attribute.
