                      **********************************CHAT APPLICATION USING SOCKET PROGRAMMING IN C*******************************************
                                                        ----------------------------------------------
                                                        
                                                        
                                                        
 This is a client - server user-level application using sockets Programming in C.Built on Windows OS using the library functions of Winsock available in C.
 Both server and client output's both sending & receiving strings on the terminal.The server and client processes can run on same machine
 
 Servers basically do the following :

1. Open a socket
2. Bind to a address(and port).
3. Listen for incoming connections.
4. Accept connections
5. Read/Send

Clients do the following :
1. Create a socket
2. Connect to the server
3. Read/Write messages
                                                        
======================EXECUTION=========================
--------------------------------------------------------
to run it on your systems:

1. you have to execute the server file in a command prompt window, using:-
>gcc server.c -lws2_32 -o server.exe
>server.exe

2. execute the client file in a new command prompt window, using:-
>gcc client.c -lws2_32 -o client.exe
>client.exe 

3. enter the message in the command prompt window related to the client

4. when you want to exit from the infinite loop of "Enter message: ", hit CTRL+C to come out of the execution (usually occurs when no message recieved from the client side)

=========================OUTPUT=========================
--------------------------------------------------------
**ON CLIENT SIDE**
Initialising Winsock...
Initialised at Tue Oct 19 14:50:27 2021


Socket created at Tue Oct 19 14:50:27 2021



Connected to server!

Enter message to be sent to server :
HELLO WORLD!!

Reply received from Server at: Tue Oct 19 14:50:27 2021

HEYY!

Enter message to be sent to server :
