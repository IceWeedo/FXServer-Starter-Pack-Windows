## FiveM - FXServer Starter Pack
Pack FXServer pré-configuré pour Windows

## - Base
* FXServer Build 2430 - 15/07/2020

## - Resources
* mysql-async 3.3.1
* async 1.0.1
* es_extended - 1.2.0 Final
* esx_menu_default 1.0.3
* esx_menu_list 1.0.1
* esx_menu_dialog 1.1.0
* nb_menuperso 2.5.0

## - Installation
* Extraire l'archive
* Installer les redistribuables
  * (FXServer\commonredist\vcredist\)
* Importer la base de données es_extended.sql dans Xampp, MariaDB...
  * (FXServer\sql\es_extended.sql)
* Modifier le fichier server.cfg avec vos informations MySQL, Nom du serveur, Clé FiveM, API Steam...
  * (FXServer\server-data\server.cfg)
* Ouvrire le port 30120 en TCP/UDP dans le pare-feu Windows et votre box internet
* Lancer run.bat
  * (FXServer\server-data\run.bat)
