# SpringBootChatApplication
Chat application with Spring Boot and WebSocket where anyone can communicate or chat with others. Just you need to type your name to login and start chatting with others.  
Tools and Technologies used are: 
*Java 16  
*Spring Boot
*Spring MVC 
*Web Socket  
*Eclipse STS IDE 


Generally, the web application has been developed in the model of request and response parameter, so whenever any request comes to the server then it returns the data as a response parameter, however, the server never sends the data to the client on its own.

The server always waits for the client or browser request and accordingly sends the data in the form of JSON. Therefore, there is only one way of communication between the server and the client. The server always needs to be dependent on the client in order to send the data.

But with the help of the WebSocket Protocol, we can achieve the two-way communication between the server and the client, which means the server need not to wait for the client’s request to send the data.
