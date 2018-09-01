## Description:

- Run the "make" command
- $make #this creates executable called "normal_web_server"
- Now run the executable
- $./normal_web_server PORT_NO
- This command starts the server at given port
- In the program the main contains method called "make_socket(port)"
- This method takes our INPUT(port_no) as parameter and creates a socket at that port.
- Socket and port and binded in the make socket method.
- In the main server is pushed into listen state and can handle 1000 clients.
- Now, the server is in LISTEN state.
- When a client  makes a request the server accepts it.
- Parses the request to find the version(HTTP 1.1) and type of request(GET).
- Checks whether the client who made the request supports gzip encoding or not in gzip_support function.
- Then the request is parsed(decoded) and the command is excuted at the server side with the help of "popen()".
- The response is then constructed with respective header information and sent to client.
- This is the flow of my program. 

