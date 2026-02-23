# LAB 3 – IPv6

##  Objectif du projet
Ce laboratoire a pour objectif de configurer un réseau IPv6 complet comprenant un routeur Cisco, deux serveurs et plusieurs postes clients.  
Il permet de manipuler l’adressage IPv6 (link-local, global unicast), l’autoconfiguration SLAAC, la configuration statique et les tests de connectivité.

---

##  Architecture du réseau

### Routeur R1 (Cisco 2811)
- F0/0 : 2001:DB8:1:1::1/64  
- F1/0 : 2001:DB8:1:2::1/64  
- Link-local : FE80::1  

### Serveurs
- Accounting : 2001:DB8:1:1::2/64  
- CAD : 2001:DB8:1:2::2/64  

### Clients
- Sales : SLAAC  
- Billing : SLAAC  
- Engineering : 2001:DB8:1:2::4/64  
- Design : 2001:DB8:1:2::3/64  

---

## Fonctionnalités principales

### Activation et configuration IPv6 sur le routeur
- Activation du routage IPv6  
- Configuration des adresses globales et link-local  
- Activation des interfaces  

### Configuration IPv6 des serveurs
- Adressage statique  
- Tests de connectivité  

### Autoconfiguration SLAAC
- Obtention automatique d’adresses IPv6  
- Vérification du préfixe et du routeur par défaut  

### Tests réseau
- Ping IPv6  
- Traceroute IPv6  
- Accès web en IPv6  

---

## Commandes principales utilisées

### Activation IPv6 et adressage du routeur
