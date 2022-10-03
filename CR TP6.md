# Compte  rendu TP 6 :

## Exercice 1 :

Sous réseaux | Adresse de sous-réseau | Adresse de broadcast | Première addr | Dernière addr
------------ | ---------------------- | -------------------- | ------------- | -------------
 1 | 172.16.0.64 | 172.16.0.127 | 172.16.0.65 | 172.16.0.126
 2 | 172.16.1.64 | 172.16.1.127 | 172.16.1.65 | 172.16.1.126
 3 | 172.16.0.0 | 172.16.0.63 | 172.16.0.1 | 172.16.0.62
 4 | 172.16.0.192 | 172.16.0.255 | 172.16.0.193 | 172.16.0.254
 5 | 172.16.1.0 | 172.16.1.63 | 172.16.1.1 | 172.16.1.62
 6 | 172.16.0.128 | 172.16.0.191 | 172.16.0.129 | 172.16.0.190
 7 | 172.16.1.128 | 172.16.1.159 | 172.16.1.129 | 172.16.1.158


## Exercice 2 :
 1 - Ajout d'une carte réseau sur la deuxième Vm :

![image](https://user-images.githubusercontent.com/60741854/193533429-ea5b7319-c752-4908-b2cf-1d7af1dde3ad.png)

 2 - Vérification de la présence des deux interfaces réseau sur le serveur:

![image](https://user-images.githubusercontent.com/60741854/193537645-e2e7dad4-4556-492b-9731-ced31c657647.png)

"lo" correspond à l'interface de loopback.

 3 - Pour supprimer le paquet cloud-init on effectue la comande "sudo apt-get remove cloud-init" sur les deux machines (client et serveur)
 
 4 - Pour changer le ghostname on tape la commande "sudo hostnamectl set-hostname SrvBour"
De plus, pour que ce changement soit permanent on viens modifier le nom du serveur dans le fichier "/etc/hosts" avec la commande "sudo nano /etc/hosts" :

![image](https://user-images.githubusercontent.com/60741854/193546731-c58c2cc5-8fc1-4735-9748-0d424aab64b3.png)


## Exercice 3 :

