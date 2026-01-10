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


