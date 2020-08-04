## - FiveM - FXServer Starter Pack
Pack FXServer pré-configuré pour Windows

## - Contenu du pack
* #### Base:
  * FXServer **Build 2430**
  * Xampp **7.4.7**

* #### Resources:
  * mysql-async **3.3.2**
  * async **1.0.1**
  * cron **1.0.0**
  * es_extended **1.2.0 Final**
  * esx_menu_default **1.0.4**
  * esx_menu_list **1.0.2**
  * esx_menu_dialog **1.1.0**

## - Installation
* #### Base de données:
  * Télécharger l'archive [ici](https://mega.nz/file/8sEAUIyZ#mR496mEZDHuxx1YIxr0mMyFyqV8QirILyc77Q4boT74)
  * Extraire l'archive à la racine de votre disque local **C:**
    * (C:\xampp)
  * Installer les redistribuables
    * (xampp\commonredist\vcredist\)
  * Exécuter xampp-control
    * (xampp\xampp-control.exe)
  * Démarrer MySQL et Apache
    * (Start)
  
* #### Serveur:
  * Télécharger l'archive [ici](https://github.com/IceWeedo/FiveM-FXServer-Starter-Pack/releases/latest)
  * Extraire l'archive à la racine de votre disque local **C:**
    * (C:\FXServer)
  * Modifier le fichier **server.cfg** avec vos informations: Nom du serveur, [Clé FiveM](https://keymaster.fivem.net), [Clé API Steam](https://steamcommunity.com/dev/apikey)...
    * (FXServer\server-data\server.cfg)
  * Ouvrire le port **30120** en **TCP/UDP** dans le pare-feu Windows et votre box internet
  * Exécuter run.bat
    * (FXServer\server-data\run.bat)

## - En jeu
### Fonctionnalité
* #### Touche:
  * Console: **F8**
  * Inventaire: **F2**

## - Autres
### Droit administrateur
* #### FXServer:
  * Connecté vous sur votre serveur 
  * Dans la cosole du serveur **CMD Windows** taper la commande **status**
  ![CMD](https://i.ibb.co/3RK3g23/cmd.png)
  * Dans **server.cfg** section **# Add system admins** ajouter la ligne **add_principal identifier.steam:xxxxxxxxxxxxxx group.admin**
  * Redémarrer votre serveur

* #### ES eXtended:
  * Dans la base de données **fxserver** table **users** colonne **group** remplacer **user** par **superadmin**

![Alt Text](https://i.ibb.co/r3R4RSf/admin.png)
