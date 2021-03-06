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

### Day 4: July 4, 2018
##### Other tests on Raspberry pi

**Today's focus** Try to communicate with raspberry to launch web browser.

### Day 5: July 5, 2018
##### Prepare for ann client interface

**Today'd focus** Installing Qt and PyQt, and begin to create an interface.

### Day 6: July 6, 2018
##### First client UI

**Today's focus** Create an UI for the client.

**Details**
 - Finish the installation of pyQt and use the good interpreter in Pycharm.
 - Create a first window open by a script
 - Show a Qlabel and a button
 - Add some parameters to fill "address" and "port"
 
### Day 7: July 7, 2018
##### Improve UI and connect some action

**Today's focus** Finalize a first version of the ui with the connection to a server.

**Details**
 - Add some GroupBox in the ui for a better organization
 - Add an image for more color ! 
 - Connect the "connect" button to try to connect to a server
 - Add a state information to now if connected or not
 
**For tomorrow** 
 - I have to add some exception and warning message in case of trying to connect to server with bad address/port, or to connect to a server not launched. 
 - To improve my Client class, I maybe have the possibility to initiate my class without trying to connect to server directly

### Day 8: July 8, 2018
##### Add parameters check and functionnalities

**Today's focus** Improve connection by checking parameters before trying to connect, add a default button and an error label.

**Details**
 - Create a class function "check_param" to type check address and port
 - Add a Qlabel which show param and connection error
 - Add a button to fill auto the address lineedit with 'localhost'
 
**For tomorrow**
 - Add the possibility to show several error messages
 - Add a colored circle in the state

### Day 9: July 9, 2018
##### Improve errors

**Today's focus** Add error and create output box

**Details**
 - Add an error when trying to send address without connected
 - Create a box with two lines of errors
 - Set errors output red
 
**For tomorrow**
 - Trying again to create a state circle
 - Tests with raspberry pi

### Day 10: July 10, 2018
##### Add circle states

**Today's focus** Add color circle state

**Details**
 - Add a red/green circle in the state box for not connected/connected state
 - Comment code
 
