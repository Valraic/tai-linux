# Commandes Linux GNU

## Sommaire
* Concepts généraux
* Manipulation fichiers et répertoires
* Gestion user et droits
* Gestion des logiciels
* Commandes avancées

## Concepts généraux
* Commande : logiciel lancé sans interface graphique
* KISS : 'Keep it simple and stupid'
* Chainer des commandes : on utilise le `|`
* Les redirections : 
  * \> : crée et écrit dans un fichier : exemple : `sort /etc/passwd > /tmp/users6_tries.txt`
  * \>\> : ajoute à la suite du fichier : `date >> /tmp/date.txt`
* Afficher le manuel des commandes : `man [commande]`

## Manipulation fichiers et répertoires
* afficher le répertoire actuel : `pwd`
* afficher le contenu du répertoire : `ls`
* changer de répertoire : `cd`
  * revenir au répertoire précédent : `cd -`
* créer un fichier vide : `touch`
* éditer un fichier : `nano`
* archiver un dossier/fichier : `tar`
  * sans compression : `tar cvf archive.tar /home/barth/projets`
  * avec compression : `tar czvf archive.tar.gz /home/barth/projets`
* extraire une archive : `tar xzvf archive.tar.gz`
* afficher le contenu d'un fichier : `cat [fichier]`
* compter nombre ligne dans un fichier : `wc -l [fichier]`
* afficher la fin d'un fichier : `tail [fichier]`
  * en temps réel `tail -f [fichier]`
* afficher le début d'un fichier : `head [fichier]`
* afficher les lignes contenant mot clé : `grep [mot clé] [fichier]`

