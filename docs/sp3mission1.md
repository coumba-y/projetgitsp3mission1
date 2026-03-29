# Mission 1 : Mise en place du serveur Windows Server 2019

**Compte rendu rédigé par** : BIDANESSY Coumba  
**Formation** : BTS SIO 1ère année - Option SISR  
**Établissement** : Lycée Paul-Louis Courier, Tours  

---

## Maquette Packet Tracer et implémentation du protocole DNS

Voici la maquette Packet Tracer avec l'implémentation du DNS

![image](assets/img/01.png)

---

## Implémentation de l'Active Directory

### Procédure d'installation d'Active Directory dans le gestionnaire de serveur

> Suivi des indications pour l'installation d'Active Directory

![AP Partie 3 active directory 1 (apres gerer - ajout roles et fonct)](assets/img/1.png)
![AP Partie 3 active directory 2](assets/img/2.png)  
![AP Partie 3 active directory 3](assets/img/3.png)  
![AP Partie 3 active directory 4(1)](assets/img/4.png)  
![AP Partie 3 active directory 5](assets/img/5.png)  
![AP Partie 3 active directory 6](assets/img/6.png)

---

### Mise en place d'une unité d'organisation

![AP Partie 3 active directory 7 unité d'organis créer](assets/img/7.png)

---

### Création d'utilisateurs dans l'unité d'organisation

> Création du compte julie  

![AP Partie 3 active directory 8](assets/img/8.png)

> Résultat final des utilisateurs dans l'unité d'organisation "admin55"  

![AP Partie 3 active directory 9](assets/img/9.png)

---

### Création d'un groupe d'utilisateurs dans le service RH

![AP Partie 3 active directory 10](assets/img/10.png)

> Permissions accordées au groupe RH  

![AP Partie 3 active directory 11](assets/img/11.png)

---

## Implémentation du serveur DNS

> Accès au gestionnaire DNS → Zone de recherche directes → lien de l'adresse IP du serveur DNS 172.16.55.250/24 au nom de domaine MN55.lan  

![AP Partie 3 active directory 13](assets/img/13.png)

![image](assets/img/14.png)

---

# Implémentation d'un client dans le même domaine Active Directory que le serveur Windows

### Configuration en DHCP du PC intégré dans le VLAN 20

> ipconfig /all
---

![image](assets/img/15.png)

---

## Fiche de tests

### Utilisateur sur le logiciel VirtualBox qui accède à l'unité d'organisation créée sur Nutanix

![image](assets/img/16.png)

---

## Accès par l'utilisateur du nom de domaine MN55.lan

![image](assets/img/17.png)
