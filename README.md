# Chatting-App
Peer-to-Peer Chatting App made by Hussam Al Basha, Batoul Fakha, Nadine Al Fadel Raad, Ali Farhat



This project was built using one of the most secure operating systems and the simplest programming language:
Ubunutu 20.04 and Python respectively.

The main goal of the project is to create a reliable environment that transfers messages, files, and images between two peers.
Although it uses UDP as a main protocol for data transfer, but timeout and detection of corrupt packets was properly written in the code 
to ensure reliability.
The latter was tested using netem. For the application to function several steps should be followed.

1) Run the Server.py (This will exchange the details and can be turned off after exchanging the ips and port numbers of the 2 peers)
2) run Client1.py and Client2.py on separate terminals
3) you can start the chat:
To request sending a file, write /file |
To request sending an image, write /image |
To exit the application, write /exit  

Note that the file or the image that you want to send must be in the same folder or path of the code application file.
