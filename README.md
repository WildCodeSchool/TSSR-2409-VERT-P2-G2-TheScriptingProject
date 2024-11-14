# **DOCUMENTATION GÉNÉRALE**

## **SOMMAIRE**

### :one: [Présentation du Projet](https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/README.md#one-pr%C3%A9sentation-du-projet-1)
### :two: [Objectifs du Projet](https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/README.md#two-objectifs-du-projet)
### :three: [Présentation de l'équipe](https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/README.md#three-pr%C3%A9sentation-de-l%C3%A9quipe)
### :four: [Choix Techniques](https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/README.md#four-choix-techniques-syst%C3%A8me-dexploitation-et-version)
### :five: [Difficultés rencontrées](https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/README.md#five-difficult%C3%A9s-rencontr%C3%A9es--probl%C3%A8mes-techniques-rencontr%C3%A9s)
### :six: [Solutions Touvées](https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/README.md#six-solutions-trouv%C3%A9es--solutions-et-alternatives-trouv%C3%A9es)
### :seven: [Améliorations Possibles](https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/README.md#seven-am%C3%A9liorations-possibles--suggestions-dam%C3%A9liorations-futures)

---


### :one: Présentation du Projet

---

Ce projet vise à créer un script permettant d'exécuter des tâches d'automatisation sur plusieurs environnements.

1. **Windows Server 2022 vers Windows 10 Pro**
2. **Debian 12 vers Ubuntu**
3. **Optionnel :**
   - **Debian 12 vers Windows 10 Pro**
   - **Windows Server 2022 vers Ubuntu**

---

#### :two: Objectifs du Projet

---

- **Mettre en place une architecture client/serveur** :  
Configuration et gestion de serveurs et de clients pour la communication et l'exécution de tâches à distance.
- **Créer et gérer des scripts Bash et PowerShell** :  
Développement de scripts permettant l'automatisation de diverses tâches sur des systèmes Windows et Linux.
- **Réaliser un projet en équipe** :  
Collaboration sur un projet avec gestion des rôles, des tâches et des responsabilités au sein de l'équipe en utilisant la méthode Agile.
- **Documenter toutes les étapes** :  
Faire des guides d'installation, d'utilisation et de configuration à l'intention des utilisateurs.
- **Faire une démonstration de la réalisation finale** :  
Présentation des fonctionnalités du script et de son utilisation sur les différents environnements.

---

#### :three: Présentation de l'Équipe

---

| Première   | Semaine      |       |  Deuxième   |   Semaine     |       |   Troisième   |   Semaine     |       |   Quatrième   |   Semaine     |
| :--------: | :----------: | :---: | :---------: | :---------:   | :---: | :-----------: | :---------:   | :---: | :-----------: | :---------:   |
| **Membre** | **Rôle**     |       | **Membre**  | **Rôle**      |       |  **Membre**   |  **Rôle**     |       |  **Membre**   |  **Rôle**     |
| Adeline    | Technicienne |       |   Adeline   | Scrum Master  |       |   Adeline     | Technicienne  |       |    Adeline    | Product Owner |
| Charles    | Technicien   |       |   Charles   | Product Owner |       |   Charles     | Technicien    |       |    Charles    | Scrum Master  |
| Freddy     | Scrum Master |       |   Freddy    | Technicien    |       |   Freddy      | Product Owner |       |    Freddy     | Technicien    |
| Yohann     | Product Owner|       |   Yohann    | Technicien    |       |   Yohann      | Scrum Master  |       |    Yohann     | Technicien    |

---

#### :four: Choix Techniques (Système d'exploitation et Version)

---

**Clients :**  

1. _Client sur OS Windows 10_<br>
   Nom : CLINWIN01<br>
   Utilisateur : Wilder<br>
   Mot de passe : Azerty1*<br>
   Configuration réseau en interne<br>
   IPv4 fixe : 172.16.10.20<br>
   Netmask : 255.255.255.0<br>

3. _Client sur OS Ubuntu_<br>
   Nom : CLILIN01<br>
   Utilisateur : Wilder<br>
   Mot de passe : Azerty1*<br>
   Configuration en réseau interne<br>
   IPv4 Fixe : 172.16.10.30<br>
   Netmask : 255.255.255.0<br>

**Serveurs :**  

1. _Serveur Windows Server 2022_<br>
   Nom : SRVWIN01<br>
   Compte : Administrator<br>
   Mot de passe : Azerty1*<br>
   IPv4 Fixe : 172.16.10.5<br>
   Netmask : 255.255.255.0<br>

2. _Serveur Debian 12_<br>
   Nom: SRVLX01<br>
   Compte : root<br>
   Mot de passe : Azerty1*<br>
   IPv4 fixe : 172.16.10.10<br>
   Netmask : 255.255.255.0<br>

---

#### :five: Difficultés rencontrées : Problèmes techniques rencontrés

---

- Configuration des VM (Virtual Machine) : cartes réseaux, configuration réseaux.<br>
- Copie/Colle des scripts.<br>
- Trouver une (des) application(s)/bibliothèque(s) afin d'insérer un "Menu" pour la selection de script.<br>

---

#### :six: Solutions Trouvées : Solutions et Alternatives trouvées

---

- Travail commun pour la configuration des VM (Virtual Machine)<br>
- Connexion de VSCode (Virtual Studio Code)<br>
- Test de plusieurs bibliothèques (Linux), Whiptail, Dialog et Zenety.
- Choix de ```System.Windows.Forms.MessageBox``` pour le Powershell

---

#### :seven: Améliorations Possibles : suggestions d'améliorations futures 

---

- Boite de l'interface pourrait être plus esthétique.
- Plus de sécurisation des 


