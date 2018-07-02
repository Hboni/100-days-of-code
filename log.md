# 100 Days Of Code - Log

### Jour 0: 30 Juin 2018
##### Mise en place et préparation

**Avancement**: Forked le projet initial de 100 Days of code.

**Idées:** Je pense commencer par essayer de tester la création d'une app en python pour communiquer en local avec mon raspberry pi.


### Jour 1: 1 Juillet 2018
##### Création du projet de streaming avec Raspberry PI

**Objectif** Projet de communication en local (TCP/IP) sous python

**Avancement**: 
 - Création d'un nouveau [repository](https://github.com/Hboni/Raspberry-stream.git) pour un projet de communication en local avec mon raspberry pi. 
 - Premiers tests d'utilisation de la toolbox socket ([exemple ici](http://apprendre-python.com/page-reseaux-sockets-python-port)) pour la communication en TCP, et création de classes Client et Server !

**Et pour demain ?** Il faudrait que je premette l'envoi de plusieurs messages, et d'arrêter à un message précis et non plus dès le premier message.


### Jour 2: 2 Juillet 2018
##### Update du serveur et du client pour envoyer plusieurs messages

**Objectif** Envoi de plusieurs messages sur un server

**Avancement**
 - Ajout de la possibilité d'envoyer plusieurs messages sur le server sans qu'il se ferme
 - Utilisation d'un mot clé pour fermer le server
 - J'ai utilisé le socket.settimeout() pour permettre d'attendre un peut avec le socket.recv() voir si quelque chose est reçu.
 
**Et pour demain ?** Je vais continuer l'amélioration de mes classes, en essayant d'envoyer des fichiers.
