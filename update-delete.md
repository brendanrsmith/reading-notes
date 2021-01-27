# Sending form data
What happens when form data is submitted?

## Client/server architecture
clients send requests to servers via HTTP protocol

   An HTML form on a web page is nothing more than a convenient user-friendly way to configure an HTTP request to send data to a server. This enables the user to provide information to be delivered in the HTTP request.
 
 the `action` attribute allows us to define where form data gets sent. The `method` attribute desfines the HTTP protocol we will use to send that data. 
 
 `GET` sends an empty body.
 
 `POST` attaches data to the body of the HTTP request
