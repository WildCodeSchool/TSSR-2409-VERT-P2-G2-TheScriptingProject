# **DOCUMENTATION ADMINISTRATEUR**

## **SOMMAIRE**

* ###  :one:  [Prérequis techniques]()
* ###  :two:  [Installation des Machines Virtuelles]()
  * ####  2.1 [Ubuntu 22]()
  * ####  2.2 [Debian 12]()
  * ####  2.3 [Windows 10]()
  * ####  2.4 [Windows Server 2022]()
* ### :three: [Configuration des ISO]()
  * #### 3.1 [Cartes Réseaux]()
  * #### 3.2 [IP statiques]() 
    * #### 3.2.1 [Ubuntu]()
    * #### 3.2.2 [Debian 12]()
    * #### 3.2.3 [Windows 10]()
    * #### 3.2.4 [Windows Server 2022]()
 * ##### 3.3 [Ping]()
  * ##### 3.4 [SSH]()
     * ##### 3.4.1 [Installation]()
     * ##### 3.4.2 [Clefs SSH]()

***
***
***

* ### :one: [Prérequis techniques]()
  * ##### ▶️ Diposer d'un ordinateur suffisament puissant pour acceuillir plusieurs VM.
  * ##### ▶️ Disque (SSD mini, nvme recommandé) 200Go.
  * ##### ▶️ Ram 16 Go minimun, 32 Go recomandé.
  * ##### ▶️ Processeur capable de prendre en charge la virtualisation

***
***

* ###  :two:  [Installation des Machines Virtuelles]()

  * ####  2.1 [Ubuntu 22]()
#### Choisir un nom d'utilisateur : 
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Ubuntu%201.jpg" width="1000">
</picture>

#### Monter l'image ISO d'Ubuntu 22 :
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Ubuntu%202.jpg" width="1000">
</picture>

#### Caractéristiques techniques allouées à la VM :
###### Vous pouvez choisir de modifier ces caractéristiques, mais nous ne pouvons garantir que cela fonctionnera
<picture>
  <img src="https://raw.githubusercontent.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/refs/heads/main/Screenshots/Install%20Ubuntu%203.png" width="500">
</picture>
<picture>
  <img src="https://raw.githubusercontent.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/refs/heads/main/Screenshots/Install%20Ubuntu%204.png" width="500">
</picture>
<picture>
  <img src="https://raw.githubusercontent.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/refs/heads/main/Screenshots/Install%20Ubuntu%205.png" width="500">
</picture>

#### Lancer la VM afin d'installer Ubuntu
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Ubuntu%205%20V2.png" width="1000">
</picture>

#### Sélectionner Ubuntu (safe graphics)
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Ubuntu%206.jpg" width="1000">
</picture>

#### Selectionner la langue et cliquer sur Install Ubuntu
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Ubuntu%207.jpg" width="1000">
</picture>

#### Sélectionner la disposition des touches et la langue du clavier
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Ubuntu%208.jpg" width="1000">
</picture>

#### Sélectionner Normal Instalation et décocher la case Download updates while installing Ubuntu :
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Ubuntu%209.jpg" width="1000">
</picture>

#### Sélectionner Erase disk and Istall Ubuntu et cliquer sur Install Now
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Ubuntu%2010.jpg" width="1000">
</picture>

#### Cliquer sur Continue 
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Ubuntu%2011.jpg" width="1000">
</picture>

#### Entrer le nom d'utilisateur, le nom de la machine et le mot de passe
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Ubuntu%2012.jpg" width="1000">
</picture>

#### Redémarrer


***

  * ####  2.2 [Debian 12]()

#### Choisir un nom d'utilisateur
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%201%20V2.png" width="1000">
</picture>

#### Monter l'image ISO de Debian 12
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%202.jpg" width="1000">
</picture>

#### Caractéristiques techniques allouées à la VM
###### Vous pouvez choisir de modifier ces caractéristiques, mais nous ne pouvons garantir que cela fonctionnera
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%203.png" width="500">
</picture>
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%204.png" width="500">
</picture>
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%205.png" width="500">
</picture>

#### Lancer la VM afin d'installer Debian
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%206.png" width="1000">
</picture>

#### Sélectionner Grpahical Install
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%207.png" width="1000">
</picture>

#### Sélectionner la langue
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%208.jpg" width="1000">
</picture>

#### Sélectionner la disposition des touches
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%209.jpg" width="1000">
</picture>

#### Nommer la machine
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%2010.png" width="1000">
</picture>

#### Laisser le nom de domaine vide
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%2011.png" width="1000">
</picture>

#### Définir le mot de passe du superutilisateur (root) <== *(nous avons utilisé le mot de passe suivant : Azerty1*)*
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%2012.png" width="1000">
</picture>

#### Définir un nom d'utilisateur
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%2013.jpg" width="1000">
</picture>

#### Définir le mot de passe de cet utilisateur
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%2014.jpg" width="1000">
</picture>

#### Sélectionner le mode assisté de partionnement et continuer
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%2015.jpg" width="1000">
</picture>

#### Sélectionner Tout dans une seul partition
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%2016.jpg" width="1000">
</picture>

#### Sélectionner Terminer le partionnement et appliquer les changements
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%2017.jpg" width="1000">
</picture>

#### Ne pas analyser d'autres supports d'installation
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%2018.png" width="1000">
</picture>

#### Choisir votre pays et un miroi pour la gestion des paquets
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%2019.jpg" width="1000">
</picture>

#### Ne pas mettre de mandataure HTTP
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%2020.png" width="1000">
</picture>

#### Nous avons décide de ne pas participer au popularity-contest *(vous pouvez en décider autrement)*
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%2021.png" width="1000">
</picture>

#### Pour une installation en CLI, décocher tous les éléments de bureau et cocher Serveur SSH
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%2022.png" width="1000">
</picture>

#### Installer GRUB
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%2023.png" width="1000">
</picture>

#### Sélectionner votre disque dur
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%2024.png" width="1000">
</picture>

#### Appuyer sur Continuer pour finaliser l'installation et redémarrer
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Debian%2025.png" width="1000">
</picture>


***

  * ####  2.3 [Windows 10]()

#### Choisir un nom d'utilisateur
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Windows%201.png" width="1000">
</picture>

#### Monter l'image ISO de Windows 10
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Windows%202.jpg" width="1000">
</picture>

#### Désactiver la connexion internet en décochant Enable Network Adapter (important pour l'installation)
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Windows%203.png" width="1000">
</picture>

#### Caractéristiques techniques allouées à la VM
###### Vous pouvez choisir de modifier ces caractéristiques, mais nous ne pouvons garantir que cela fonctionnera
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Windows%204.png" width="500">
</picture>
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Windows%205.png" width="500">
</picture>
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Windows%206.png" width="500">
</picture>

#### Sélectionner la langue et la disposition des touches du clavier, puis cliquer sur Install Now
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Windows%207.jpg" width="1000">
</picture>

#### Cliquer sur I don't have a product key
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Windows%208.jpg" width="1000">
</picture>

#### Sélectionner une version de Windows 10 (ici Windows 10 Pro)
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Windows%209.jpg" width="1000">
</picture>

#### Cliquer sur Custom: Install Windows only
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Windows%2010.jpg" width="1000">
</picture>

#### Sélectionner l'unique disque dur
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Windows%2011.jpg" width="1000">
</picture>

#### Choisir la région et la disposition des touches selon convenance
#### Entrer le nom d'utilisateur

<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Windows%2012.jpg" width="1000">
</picture>

#### Entrer le mot de passe et répondre aux propositions de Windows selon votre convenance


***

  * ####  2.4 [Windows Server 2022]()

#### Choisir un nom d'utilisateur
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Winsrv%201.png" width="1000">
</picture>

#### Monter l'image ISO de Windows Server 2022
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Winsrv%202.jpg" width="1000">
</picture>

#### Caractéristiques techniques allouées à la VM
###### Vous pouvez choisir de modifier ces caractéristiques, mais nous ne pouvons garantir que cela fonctionnera
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Winsrv%203.png" width="500">
</picture>
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Winsrv%204.png" width="500">
</picture>
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Winsrv%205.png" width="500">
</picture>

#### Sélectionner la langue et la disposition des touches du clavier, puis cliquer sur Install Now
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Winsrv%206.jpg" width="1000">
</picture>

#### Sélectionner une version de Windows Server (ici Windows Server 2022 Standard Evaluation)
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Winsrv%207.jpg" width="1000">
</picture>

#### Sélectionner l'unique disque dur
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Install%20Winsrv%208.jpg" width="1000">
</picture>

***
***
***

# Configuration des Machînes virtuelles

***

## Configuration des cartes réseaux
##### Une fois les installations terminées, les quatre machines virtuelles sont configurées avec deux cartes réseaux, la première pour avoir accès à internet, la seconde pour communiquer sur un même réseau privé.

#### Première carte réseau configurée en pont
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Carte%20r%C3%A9seau%201.png" width="1000">
</picture>

#### Seconde carte réseau configurée en réseau interne 
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/Carte%20r%C3%A9seau%202.png" width="1000">
</picture>


***
***

## Mise en place des adresses IP statiques et autorisation du port 22 (port SSH)

***

### Client Ubuntu

#### Cliquer l'icône réseau en haut à droite du bureau puis sur Ethernet (enp0s8)
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Ubuntu%201.png" width="1000">
</picture>

#### Cliquer sur l'engrenage de la connexion Ethernet (enp0s8)
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Ubuntu%202.png" width="1000">
</picture>

#### Dans l'onglet IPV4, cliquer sur Manual, puis entrer l'adresse IP fixe et le Masque de sous réseau
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Ubuntu%203.jpg" width="700">
</picture>

#### Ouvrir le terminal pour ouvrir le port 22 (port SSH)
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Ubuntu%204.png" width="700">
</picture>


***

### Serveur Debian

#### Modifier le fichier qui gère les connexions réseaux
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Debian%201.jpg" width="500">
</picture>

#### Configurer la connexion enp0s8 comme suit 
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Debian%202.png" width="700">
</picture>

#### Le pare-feu de Debian 12 est ouvert par defaut, il n'est donc pas nécessaire de configurer le port 22 (port SSH).


***

### Client Windows 10

#### Ouvrir le Panneau de Configuration et ouvrir le centre de Réseau et Partage
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Windows%201.png" width="1000">
</picture>

#### Cliuqyer sur ethernet 2
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Windows%202.png" width="1000">
</picture>

#### Cliquer sur Properties
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Windows%203.png" width="500">
</picture>

#### Cliquer sur Internet Protocol Version 4 (TCP/IPv4) puis sur Properties
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Windows%204.png" width="500">
</picture>

#### CLiquer sur Use the following IP adress, puis entrer l'adresse IP fixe et le Masque de sous réseau, puis valider
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Windows%205.png" width="500">
</picture>

#### Pour ouvrir le port 22 (port SSH), cliquer sur l'icône Réseau de la barre des tâches puis sur Network & Internet settings
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Windows%206.png" width="1000">
</picture>

#### Cliquer sur Windows Firewall
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Winsrv%207.jpg" width="1000">
</picture>

#### Cliquer sur Advanced Settings
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Winsrv%208.jpg" width="1000">
</picture>

#### Créer une nouvelle règle
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Winsrv%209.jpg" width="1000">
</picture>

#### Cliquer sur Port
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/SSH%20Windows%201.png" width="1000">
</picture>

#### Dans Specific local ports, inscrire port 22
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Winsrv%2010.jpg" width="1000">
</picture>

#### Dans Action, sélectionner Allow the connection
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/SSH%20Windows%202.png" width="1000">
</picture>

#### Dans Profile, ne rien modifier et cliquer sur Next
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/SSH%20Windows%203.png" width="1000">
</picture>

#### Donner un nom clair à cette nouvelle règle et cliquer sur Finish
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/SSH%20Windows%204.png" width="1000">
</picture>


***

### Client Windows server 2022

#### Ouvrir le Panneau de Configuration et ouvrir le centre de Réseau et Partage
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Windows%201.png" width="1000">
</picture>

#### Cliuqyer sur ethernet 2
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Windows%202.png" width="1000">
</picture>

#### Cliquer sur Properties
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Windows%203.png" width="500">
</picture>

#### Cliquer sur Internet Protocol Version 4 (TCP/IPv4) puis sur Properties
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Windows%204.png" width="500">
</picture>

#### CLiquer sur Use the following IP adress, puis entrer l'adresse IP fixe et le Masque de sous réseau, puis valider
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Windows%205.png" width="500">
</picture>

#### Pour ouvrir le port 22 (port SSH), cliquer sur l'icône Réseau de la barre des tâches puis sur Network & Internet settings
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Winsrv%206.jpg" width="1000">
</picture>

#### Cliquer sur Windows Firewall
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Winsrv%207.jpg" width="1000">
</picture>

#### Cliquer sur Advanced Settings
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Winsrv%208.jpg" width="1000">
</picture>

#### D'abord pour Inbound Rules et ensuite pour Outbound Rules, créer une nouvelle règle (il faut donc faire la procédure deux fois)
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Winsrv%209.jpg" width="1000">
</picture>

#### Cliquer sur Port
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/SSH%20Windows%201.png" width="1000">
</picture>

#### Dans Specific local ports, inscrire port 22
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/IP%20Winsrv%2010.jpg" width="1000">
</picture>

#### Dans Action, sélectionner Allow the connection
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/SSH%20Windows%202.png" width="1000">
</picture>

#### Dans Profile, ne rien modifier et cliquer sur Next
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/SSH%20Windows%203.png" width="1000">
</picture>

#### Donner un nom clair à cette nouvelle règle et cliquer sur Finish
<picture>
  <img src="https://github.com/WildCodeSchool/TSSR-2409-VERT-P2-G2-TheScriptingProject/blob/main/Screenshots/SSH%20Windows%204.png" width="1000">
</picture>

#### 
<picture>
  <img src="" width="1000">
</picture>

#### 
<picture>
  <img src="" width="1000">
</picture>

#### 
<picture>
  <img src="" width="1000">
</picture>

#### 
<picture>
  <img src="" width="1000">
</picture>

#### 
<picture>
  <img src="" width="1000">
</picture>
