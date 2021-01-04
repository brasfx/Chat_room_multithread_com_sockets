
<b>Chat implementation with sockets</b>

Server execution: </br>
1st gcc server.c -o server -lpthread </br>
2nd ./server <server_port> </br>

Example: ./server 1234

Client execution: </br>
1st gcc client.c -o client </br>
2nd ./client < IP > <server_port>

Example: ./client 127.0.0.1 1234

* All clients connecting to the chat must use the same server IP and port


<b>Implementação chat com sockets</b>

Execução do servidor:</br>
1° gcc server.c -o server -lpthread</br>
2° ./server <porta_do_servidor></br>

Ex: ./server 1234

Execução do cliente:</br>
1° gcc client.c -o client</br>
2° ./client < IP > <porta_do_servidor>

Ex: ./client 127.0.0.1 1234

* Todos os clientes que forem se conectar ao chat devem usar mesmo IP e porta do servidor

