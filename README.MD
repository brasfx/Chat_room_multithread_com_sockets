Implementação chat com sockets

Execução do servidor:
1° gcc server.c -o server -lpthread
2° ./server <porta_do_servidor>

Ex: ./server 1234

Execução do cliente:
1° gcc client.c -o client
2° ./client <IP> <porta_do_servidor>

Ex: ./client 127.0.0.1 1234

*Todos os clientes que forem se conectar ao chat devem usar mesmo IP e porta do servidor

