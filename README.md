# password-finder
This GO-lang project focuses on searching a password from the given list of passwords. The overall application architecture consists of three core components (and corresponding programs): Client, Server and Slaves. • The client is responsible for making the request, to the Server, to search the password. • The server program on receiving the request, welcomes the client, analyzes and divides the task into parts and allocates these parts to Slaves, which have already registered with the server. • The slaves are the workhorses and they register with server and are assigned the tasks. Once they register, they notify the server about the file chunks they have and the server uses this info for scheduling. 
