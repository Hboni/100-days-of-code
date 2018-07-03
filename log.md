# 100 Days Of Code - Log

### Day 0: June 30, 2018
##### Preparation

**Details**: Forked the initial 100 Days of code project.

**Thought:** I think i'll begin by trying to create a python app to communicate locally with my Raspberry pi.


### Day 1: July 1, 2018
##### Creation of the streaming Raspberry pi

**Today's focus** Project of TCP/IP local communication under python

**Details**: 
 - Creation of a new [repository](https://github.com/Hboni/Raspberry-stream.git) for a local communication project with my raspberry pi.
 - First test of the socket toolbox use ([example here](http://apprendre-python.com/page-reseaux-sockets-python-port))for the TCP communication.
 - Creation of Client and Server classes.

**For tomorrow:** I would like to try to send several messages from the client to the server, and to stop it with a word.


### Day 2: July 2, 2018
##### Server and Client update to send several messages

**Today's focus** Send several messages to the server

**Details**
 - Add the possibility to send several messages to the server without closing it.
 - Use of the "fin" keyword to stop the server.
 - I used socket.settimeout() to wait to see if something was send by the server, and received by socket.recv().
 
**For tomorrow:** I'm going to upgrade my classes to send files

### Day 3: July 3, 2018
##### Communication with Raspberry pi

**Today's focus** First tries to communicate with my Raspberry pi

**Details**
 - Add the possibility to use different address and different port to communicate (for Server and Client).
 - Test the use of my functions on my raspberry pi.
 - Finaly communicate with Raspberry pi, with server on it and Cient on my computer, using the RP address.
 - Ass an option to open web browser on server-side (Not tested!).
 
 **For tomorrow:** I'll try to use the web-launch option on raspberry pi.
