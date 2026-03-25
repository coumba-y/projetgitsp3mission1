# Mission 1 : Mise en place du serveur Windows Server 2019

**Compte rendu rédigé par** : BIDANESSY Coumba
**Formation** : BTS SIO 1ère année - Option SISR  
**Établissement** : Lycée Paul-Louis Courier, Tours  

![image](https://hackmd.io/_uploads/S1kRtvUrZg.png)


[toc]

## Maquette Packet Tracer et implémentation du protocole DNS 

Voici la maquette Packet Tracer avec l'implémentation du DNS 

![image](https://hackmd.io/_uploads/SkcKPTZjWg.png)

### Fiche de test

Accès au DNS par le serveur DHCP Linux

![image](https://hackmd.io/_uploads/BkRavpbjZx.png)


## Installation physique du serveur MN01

SCREEN VM

## Implémentation de l'Active Directory

### Procédure d'installation d'Active Directory dans le gestionnaire de serveur 

> Suivi des indications pour l'installation d'Active Directory
![AP Partie 3 active directory 1 (apres gerer - ajout roles et fonct)](https://hackmd.io/_uploads/S1BiO6bo-l.png)
![AP Partie 3 active directory 2](https://hackmd.io/_uploads/r18QtpbjWe.png) 
![AP Partie 3 active directory 3](https://hackmd.io/_uploads/HyzEKpWo-e.png)
![AP Partie 3 active directory 4(1)](https://hackmd.io/_uploads/Hkn8tTWjbe.png)
![AP Partie 3 active directory 5](https://hackmd.io/_uploads/r1jPYabj-l.png)
![AP Partie 3 active directory 6](https://hackmd.io/_uploads/rJ_FYp-oZl.png)


### Mise en place d'une unité d'organisation 

![AP Partie 3 active directory 7 unité d'organis créer](https://hackmd.io/_uploads/rJjy9a-jWx.png)

### Création d'utilisateurs dans l'unité d'organisation

> Création du compte julie 
![AP Partie 3 active directory 8](https://hackmd.io/_uploads/rkoGqpWsWg.png)

> Résultat final des utilisateurs dans l'unité d'organisation "admin55"
![AP Partie 3 active directory 9](https://hackmd.io/_uploads/BJLwcpWobe.png)

### Création d'un groupe d'utilisateurs dans le service RH

![AP Partie 3 active directory 10](https://hackmd.io/_uploads/r1bj5aWobx.png)

>Permissions accordées au groupe RH 
![AP Partie 3 active directory 11](https://hackmd.io/_uploads/H1K25Tbsbx.png)

## Implémentation du serveur DNS

> Accès au gestionnaire DNS -> Zone de recherche directes -> lien de l'adresse IP du serveur DNS 172.16.55.250/24 au nom de domaine MN55.lan
 ![AP Partie 3 active directory 13](https://hackmd.io/_uploads/r1CDsTbo-x.png)


## Fiche de tests

### Accès au serveur DNS depuis serveur DHCP


### Utilisateur sur le logiciel virtualbox qui accède à l'unité d'organisation créer sur Nutanix
