# Network-File-Sharing-Server-and-Client
 A client–server chat application implemented in C++ using socket programming and Docker. The project demonstrates bidirectional communication between two containers—one acting as a server and the other as a client—connected through a Docker network using docker-compose.
 
 Run the Server:
 docker-compose run server                                                                                                                                                                                             
Expected output:
Server listening on port 8080...
 
 Run the Client (in new/split terminal):                                                                                                                                                                              docker-compose run client

 Expected output:
Connected to server!                                                                                                                                                                                                   
Enter message to send to server (or 'EXIT' to quit):
 
 Chat Interaction:                                                                                                                                                                                                      
Type messages in the client terminal → seen in server.                                                                                                                                                                 
Type messages in the server terminal → seen in client.                                                                                                                                                                 
Type EXIT to close the chat gracefully.                                                                                                                                                                                

Stop and clean up:                                                                                                                                                                                                      
docker-compose down

(This releases all containers and ports.)
