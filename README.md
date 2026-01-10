_Conceptualistaion clair et précise du Projet SAE 1.02_

**Objectif Global du Projet** : concevoir, simuler et mettre en place un réseau informatique complet pour une petite entreprise, comme si on travaillais dans un bureau d’étude en Réseaux & Télécoms.
 
 Le but est de montrer que l'on sait : 

 -> comprendre un cahier des charges,
 -> concevoir un réseau logique et physique,
 -> configurer des équipements réseau,
 -> tester et justifier techniquement ton travail,
 -> documenter et présenter ton projet de manière professionnelle.

**Au niveau matériel :**

On es chargé d’installer l’infrastructure réseau de l’entreprise avec :

-> 1 routeur Cisco série 800
-> plusieurs switchs Cisco 2960
-> plusieurs réseaux séparés par VLAN

L’entreprise veut 4 réseaux distincts, chacun avec un rôle précis : 

| VLAN            | Nom             | Rôle                           |
| --------------- | --------------- | ------------------------------ |
| VLAN ADMIN      | Administrateurs | Gestion du réseau, serveurs    |
| VLAN PERSONNEL  | Employés        | Postes de travail              |
| VLAN PRODUCTION | Usine           | Machines industrielles         |
| VLAN VIDEO      | Vidéo           | Flux vidéo internes            |
| VLAN 800        | Internet        | Accès Internet (déjà existant) |

**Important :** 

Les VLAN doivent être configurés sur les switchs
Le routage inter-VLAN doit être assuré par le routeur

Les services réseau à mettre en place pour ces entreprises :

**On aura donc : **
_DHP_ -> Installé sur le routeur
       Fournit automatiquement des adresses IP aux machines

_DNS_ -> Un serveur DNS doit être accessible depuis le réseau

_Sevreur Web_ -> Situé dans le VLAN ADMIN
               Serveur Apache
               Page web statique présentant l’entreprise


**le plus important : le plan d’adressage IPv4 :**


**Attribuer :**
une plage IP par VLAN
une adresse IP à chaque équipement

**Indiquer l’adresse IP + masque sur :**
le schéma réseau
le rapport technique

On vas donc ce retrouver avec par exemple : 

VLAN ADMIN : 192.168.10.0 /24
VLAN PERSONNEL : 192.168.20.0 /24

**La partie TEST **


On réalise ensuite donc les schémas réseaux pour ces quatres entreprises avec Cisco PKT avec évidemment les notation mises au dessus au préalable.
Et en s'aidant bien entendu de avec draw.io

Pour la partie test avec donc les VM (ce que l'on vas faire à la prochaine séance) :

Dire dans un premier temps ce que l'on attend ex :
on fais une requête un PC obtient une adresse IP grâce au protôcole DHCP 

Fairer ensuite donc le test :
On regarde ce que l'on obtient et on en débat 

Regarder les résultat et bien évidement prendre une capture d'écran de chaque test individuelle pour ensuite pourvoir les commenter et en déduire par la suite si ces résultats sont conforme a ce que l'on attendez ou non

On aura donc comme étapes de conception dans l'ordre : 

Recherche & conception
Simulation
Maquette Virtuelle
Maquette finale (28 janvier 2026)


Livrables attendus pour tout le monde du grp :

1 Schéma réseau

2 Plan d’adressage IPv4

3 Devis matériel

4 Rapport technique (Markdown / Jupyter)

5 Compte-rendu de tests

6 Présentation orale (collective + individuelle)

7 Présentation du projet en anglais

Pour ce qui en est de l'évaluation on fera un point plus tard en grp vers le 18 / 20 javiers (minimum une semaine avant)
























