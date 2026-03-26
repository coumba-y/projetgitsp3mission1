# Mission 1 : Mise en place du serveur Windows Server 2019

**Compte rendu rédigé par** : BIDANESSY Coumba
**Formation** : BTS SIO 1ère année - Option SISR  
**Établissement** : Lycée Paul-Louis Courier, Tours  

![img](./img/AP%20Partie%203%20active%20directory%201%20(apres%20gerer%20-%20ajout%20roles%20et%20fonct).png)


## Maquette Packet Tracer et implémentation du protocole DNS 

Voici la maquette Packet Tracer avec l'implémentation du DNS 

![image](./img/AP%20Partie%203%20active%20directory%202.png)

### Fiche de test

Accès au DNS par le serveur DHCP Linux

![image](https://hackmd.io/_uploads/BkRavpbjZx.png)


## Installation physique du serveur MN01

SCREEN VM

## Implémentation de l'Active Directory

### Procédure d'installation d'Active Directory dans le gestionnaire de serveur 

> Suivi des indications pour l'installation d'Active Directory
![AP Partie 3 active directory 1 (apres gerer - ajout roles et fonct)](./img/AP%20Partie%203%20active%20directory%201%20(apres%20gerer%20-%20ajout%20roles%20et%20fonct).png)
![AP Partie 3 active directory 2](./img/AP%20Partie%203%20active%20directory%202.png) 
![AP Partie 3 active directory 3](./img/AP%20Partie%203%20active%20directory%203.png)
![AP Partie 3 active directory 4(1)](./img/AP%20Partie%203%20active%20directory%204.png)
![AP Partie 3 active directory 5](./img/AP%20Partie%203%20active%20directory%205.png)
![AP Partie 3 active directory 6](./img/AP%20Partie%203%20active%20directory%206.png)


### Mise en place d'une unité d'organisation 

![AP Partie 3 active directory 7 unité d'organis créer](./img/AP%20Partie%203%20active%20directory%207%20unité%20d'organis%20créer.png)

### Création d'utilisateurs dans l'unité d'organisation

> Création du compte julie 
![AP Partie 3 active directory 8](./img/AP%20Partie%203%20active%20directory%208.png)

> Résultat final des utilisateurs dans l'unité d'organisation "admin55"
![AP Partie 3 active directory 9](./img/AP%20Partie%203%20active%20directory%209.png)

### Création d'un groupe d'utilisateurs dans le service RH

![AP Partie 3 active directory 10](./img/AP%20Partie%203%20active%20directory%2010.png)

>Permissions accordées au groupe RH 
![AP Partie 3 active directory 11](./img/AP%20Partie%203%20active%20directory%2011.png)

## Implémentation du serveur DNS

> Accès au gestionnaire DNS -> Zone de recherche directes -> lien de l'adresse IP du serveur DNS 172.16.55.250/24 au nom de domaine MN55.lan
 ![AP Partie 3 active directory 13](./img/AP%20Partie%203%20active%20directory%2013.png)


# Implémentation d'un client dans le même domaine Active Directory que le serveur Windows

### Configuration en DHCP du PC intégré dans le VLAN 20 

> ipconfig/ all 
![image](https://hackmd.io/_uploads/SkOCDpfjWg.png)


### Configuration en DHCP du PC intégré dans le VLAN 20 

![image](./img/15.png)

## Fiche de tests




### Utilisateur sur le logiciel virtualbox qui accède à l'unité d'organisation créer sur Nutanix


![image](./img/16.png)


## Accès par l'utilisateur du nom de domaine MN55.lan


![image](./img/17.png)

