    ____  ____  ___   __________  _____    __  ____    _________    _   ____  __
   / __ \/ __ \/   | / ____/ __ \/ ___/   / / / / /   / ____/   |  / | / / / / /
  / / / / /_/ / /| |/ / __/ / / /\__ \   / / / / /   / __/ / /| | /  |/ / / / / 
 / /_/ / _, _/ ___ / /_/ / /_/ /___/ /  / /_/ / /___/ /___/ ___ |/ /|  / /_/ /  
/_____/_/ |_/_/  |_\____/\____//____/   \____/_____/_____/_/  |_/_/ |_/\____/   


README!

This application belongs to Mr. Dragos Uleanu. All rights reserved.


Description:

The following application represents a chat simulation. It used the principles of Client-Server programming. 


Technologies used:
Python
Python Sockets


Libraries:
socket  
select 
errno 
sys 

Explanation:

The server connects to the IP and PORT variables (deffault 1234) using a socket object created from Adress Family. 
Using a predefined Header and constantly checking it using a constant stream of information the server accepts
connections from users, displaying their ip address or usernames. The servers collects and displays incoming messages
and distributes them to other connect clients.


The client connects itself to the server (using the same IP and PORT tupple). A client can choose a username and the
send a message to the server.

By using these two concepts, provided by server.py and client.py, a virtual chat has been realised in which different
clients can communicate.

The application runs by activating the cmd: py server.py
				            py client.py

And by writting the message.













                                                                           
