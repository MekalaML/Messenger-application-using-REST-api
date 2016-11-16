# Messenger-application-using-REST-api
Messenger application using RESTful web services available in the web containers

<ul>
<li>You can copy the source and deploy in TOMCAT server at local machine</li>
<li>The service class is having two hard-coded messages. So, you can directly do GET request for message id 1 & 2 using POSTMAN</li>
<li>
<dl>
  <dt>GET request for all messages:</dt>
  <dd>- URL(http:localhost:8080/webapi/messages) Body(No content) Header(No content)</dd>
  <dt>GET request for message with id:</dt>
  <dd>- URL(http:localhost:8080/webapi/messages/{messageid}) Body(No content) Header(No content)</dd>
  <dt>POST request:</dt>
  <dd>- URL(http:localhost:8080/messages/{messageid}) Body(New message in JSON payload) Header(No content)</dd>
  <dt>PUT request:</dt>
  <dd>- URL(http:localhost:8080/messages/{messageid}) Body(Update message in JSON payload) Header(No content)</dd>
  <dt>DELETE request:</dt>
  <dd>- URL(http:localhost:8080/messages/{messageid}) Header(No content)</dd>
</dl> 
</li>
<li>Comment for each message is also handled in this code</li>
<li>
<dl>
  <dt>GET request for all comments under the message id:</dt>
  <dd>- URL(http:localhost:8080/messages/{messageid}/comments) Body(No content) Header(No content)</dd>
  <dt>GET request for a comment with id under the message id:</dt>
  <dd>- URL(http:localhost:8080/messages/{messageid}/comments/{commentid}) Body(No content) Header(No content)</dd>
  <dt>POST request:</dt>
  <dd>- URL(http:localhost:8080/messages/{messageid}/comments/{commentid}) Body(New comment in JSON payload) Header(No content)</dd>
  <dt>PUT request:</dt>
  <dd>- URL(http:localhost:8080/messages/{messageid}/comments/{commentid}) Body(Update comment in JSON payload) Header(No content)</dd>
  <dt>DELETE request:</dt>
  <dd>- URL(http:localhost:8080/messages/{messageid/comments/{commentid}}) Header(No content)</dd>
</dl>
</li>
</ul>
