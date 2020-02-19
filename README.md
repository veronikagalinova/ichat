# ichat
A real-time chat application with Spring Boot and Angular 8.
## Prerequisites
	- Java 8
	- Maven
	- NodeJS
	- Angular CLI

## Functional summary

     The backend configures in-memory message broker and exposes STOMP endpoint to communicate
     through web sockets and Rest API for login/logout. It does not use Spring security for authentication.
     The login feature is only registering the user in the database (In memory database).

	   The frontend uses the bottom rewritten library @stomp/ng2-stompjs as a STOMP client.
     It implements a simple login page where the user can connect to the chat room. 
     The chat room displays the list of connected users and once the user clicks on a user in the list,
     they can start to send/receive messages between each other in real time.


