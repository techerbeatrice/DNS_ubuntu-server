# DNS sur ubuntu : installation, configuration et test

**Quête :**  
Configure la carte réseau de ta machine virtuelle en "Réseau Interne"  
Mettre en place un serveur DNS sur Linux avec Bind9  
Ce serveur fait autorité sur la zone wilders.lan  
Créer un enregistrement de type A et CNAME  
Teste le bon fonctionnement du serveur y compris depuis un client sur le réseau local  
___

**Les étapes :**  
**Installation de Bind9**  
**Création du fichier de la zone**  
**Création du fichier de la zone inversée**  
**Configuration de la zone et de la zone inversée dans le fichier named.conf.local de Bind**   
**Test**  
___

**Installation de Bind9**   

Après avoir fait un **apt-get update**, exécuter la commande suivante pour installer DNS :   
![image](https://github.com/techerbeatrice/DNS_ubuntu-server/assets/138071140/d8c34ab5-3951-4ade-b14e-7ed59a898047)

![image](https://github.com/techerbeatrice/DNS_ubuntu-server/assets/138071140/a51f8499-52f7-4de4-9d01-c919e3705f86)

![image](https://github.com/techerbeatrice/DNS_ubuntu-server/assets/138071140/fe864308-b746-4314-ae3f-499c299d6c4d)

____
**Création du fichier de la zone**

____________
**Création du fichier de la zone inversée**
_______________

**Configuration de la zone et de la zone inversée dans le fichier named.conf.local de Bind**   
____


**Démarrage de Bind9**   

![image](https://github.com/techerbeatrice/DNS_ubuntu-server/assets/138071140/258a2fd6-4b52-4b56-92f1-4532ed447e41)


