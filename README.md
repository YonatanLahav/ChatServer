 # ChatServer instructions
 after cloning Chat-App-Server repository, do the following :
 1) open the solution - ChatWebServer.sln on Visual Studio.
 2) set the Web-server as the strart-up project.
 3) in the Package Manager Console type - update-database initialization
 4) set the web-api as the start up project and run it

## Chat Clients:
### Android Client 
https://github.com/YonatanLahav/ChatClient-Android
### Web Client (React)
https://github.com/YonatanLahav/ChatClient-React

## Pay attention to the following :
1. the api-server is runing on localhost:7182 and can communicate with localhost:3000, and localhost:3001 only
2. This program is using database, therefore the data is localy saved on the users computer, that is why the chat will be empty for any data, (users, messages, conversation...) in your first run. 
