## FiveM - FXServer Starter Pack
Pack FXServer pré-configuré pour Windows

## - Base
* FXServer **Build 2430**
* Xampp **7.4.7**

## - Resources
* mysql-async **3.3.1**
* async **1.0.1**
* cron **1.0.0**
* es_extended **1.2.0 Final**
* esx_menu_default **1.0.4**
* esx_menu_list **1.0.2**
* esx_menu_dialog **1.1.0**

## - Installation
### Base de données:
* Télécharger l'archive [ici](https://mega.nz/file/54FUyA6J#UNwKXX-RtIr_oUisaRWXtL5ztzpZA9QPGqfoPXsk4Rk)
* Extraire l'archive à la racine de votre disque local **C:**
  * (C:\xampp)
* Installer les redistribuables
  * (xampp\commonredist\vcredist\)
* Exécuter xampp-control
  * (xampp\xampp-control.exe)
* Démarrer MySQL et Apache
  * (Start)
  
### Serveur:
* Télécharger l'archive [ici](https://github.com/IceWeedo/FiveM-FXServer-Starter-Pack/releases/latest)
* Extraire l'archive à la racine de votre disque local **C:**
  * (C:\FXServer)
* Modifier le fichier **server.cfg** avec vos informations: Nom du serveur, [Clé FiveM](https://keymaster.fivem.net), [Clé API Steam](https://steamcommunity.com/dev/apikey)...
  * (FXServer\server-data\server.cfg)
* Ouvrire le port **30120** en **TCP/UDP** dans le pare-feu Windows et votre box internet
* Exécuter run.bat
  * (FXServer\server-data\run.bat)

## - En jeu
### Fonctionnalité (touche):
* Console: **F8**

## - Autres
### Droit administrateur:
* Dans la base de données **fxserver** table **users** colonne **group** remplacer **user** par **admin**

![Alt Text](https://i.ibb.co/r3R4RSf/admin.png)
