all:clean server client

server: tcp_server.c
	gcc tcp_server.c -o hserver

client: tcp_client.c
	gcc tcp_client.c -o hclient

clean:
	rm -rf *.o hserver hclient