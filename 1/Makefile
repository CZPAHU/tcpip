all:clean server client

server: hello_server.c
	gcc hello_server.c -o hserver

client: hello_client.c
	gcc hello_client.c -o hclient

clean:
	rm -rf *.o hserver hclient