# Mission 1 : Mise en place du serveur Windows Server 2019

**Compte rendu rédigé par** : BIDANESSY Coumba  
**Formation** : BTS SIO 1ère année - Option SISR  
**Établissement** : Lycée Paul-Louis Courier, Tours  

![img]()

---

## Maquette Packet Tracer et implémentation du protocole DNS 

Voici la maquette Packet Tracer avec l'implémentation du DNS 

![image]()

### Fiche de test

Accès au DNS par le serveur DHCP Linux

![image]()

---

## Installation physique du serveur MN01

SCREEN VM

---

## Implémentation de l'Active Directory

### Procédure d'installation d'Active Directory dans le gestionnaire de serveur 

> Suivi des indications pour l'installation d'Active Directory

![AP Partie 3 active directory 1 (apres gerer - ajout roles et fonct)](/img/1.png)
![AP Partie 3 active directory 2](/img/2.png)  
![AP Partie 3 active directory 3](/img/3.png)  
![AP Partie 3 active directory 4(1)](/img/4.png)  
![AP Partie 3 active directory 5](/img/5.png)  
![AP Partie 3 active directory 6](/img/6.png)

---

### Mise en place d'une unité d'organisation 

![AP Partie 3 active directory 7 unité d'organis créer](/img/7.png)

---

### Création d'utilisateurs dans l'unité d'organisation

> Création du compte julie  

![AP Partie 3 active directory 8](/img/8.png)

> Résultat final des utilisateurs dans l'unité d'organisation "admin55"  

![AP Partie 3 active directory 9](/img/9.png)

---

### Création d'un groupe d'utilisateurs dans le service RH

![AP Partie 3 active directory 10](/img/10.png)

> Permissions accordées au groupe RH  

![AP Partie 3 active directory 11](/img/11.png)

---

## Implémentation du serveur DNS

> Accès au gestionnaire DNS → Zone de recherche directes → lien de l'adresse IP du serveur DNS 172.16.55.250/24 au nom de domaine MN55.lan  

![AP Partie 3 active directory 13](/img/13.png)

---

# Implémentation d'un client dans le même domaine Active Directory que le serveur Windows

### Configuration en DHCP du PC intégré dans le VLAN 20 

> ipconfig /all  

![image](/img/14.png)

---

### Configuration en DHCP du PC intégré dans le VLAN 20 

![image](/img/15.png)

---

## Fiche de tests

### Utilisateur sur le logiciel VirtualBox qui accède à l'unité d'organisation créée sur Nutanix

![image](/img/16.png)

---

## Accès par l'utilisateur du nom de domaine MN55.lan

![image](/img/17.png)
