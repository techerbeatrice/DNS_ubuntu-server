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
**Configuration du fichier named.conf.local de Bind**   
**Test**  
___

**Installation de Bind9**   

Après avoir fait un **apt-get update**, exécuter la commande suivante pour installer DNS :   
![image](https://github.com/techerbeatrice/DNS_ubuntu-server/assets/138071140/d8c34ab5-3951-4ade-b14e-7ed59a898047)

![image](https://github.com/techerbeatrice/DNS_ubuntu-server/assets/138071140/a51f8499-52f7-4de4-9d01-c919e3705f86)

![image](https://github.com/techerbeatrice/DNS_ubuntu-server/assets/138071140/fe864308-b746-4314-ae3f-499c299d6c4d)

____
**Création du fichier de la zone**   

![image](https://github.com/techerbeatrice/DNS_ubuntu-server/assets/138071140/c43bb3ce-e870-46c4-8778-a40c7d297e7b)




____________
**Création du fichier de la zone inversée**   

![image](https://github.com/techerbeatrice/DNS_ubuntu-server/assets/138071140/f4625ece-7eae-4628-8f4a-3ce003283aa4)


_______________

**Configuration du fichier named.conf.local de Bind**   

![image](https://github.com/techerbeatrice/DNS_ubuntu-server/assets/138071140/b461dbf1-8e6f-4442-8da1-4ea1380bd35c)

____


**Démarrage de Bind9**   

![image](https://github.com/techerbeatrice/DNS_ubuntu-server/assets/138071140/820e344d-b2c7-43a0-9ecd-5892380d555a)

**Test**   

![image](https://github.com/techerbeatrice/DNS_ubuntu-server/assets/138071140/216f5399-ed4b-4dcb-8237-f1f106098abd)

