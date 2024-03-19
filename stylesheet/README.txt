Il faut entrer dans ce dossier les images nécessaires au fonctionnement du site !

Voici une (petite) présentation de ce qu'est un chemin relatif en html :
. Un exemple : ./dossier/fichier.extension
. Le '.' avant le '/' signifie que l'on commence le parcours dans le dossier ou est placer le fichier, exemple de chemin relatif d'une image dans le dossier images pour le fichier index.php : ./images/image.png
. le '/' permet de diriger le chemin vers un dossier, donc '/images' = rentre dans le dossier images ou arrete toi a : ce fichier 

Le chemin relatif est différent de son homologue le chemin absolu car celui-ci démarre de la racine de l'arborescence des fichiers.
Exemple de chemin absolu : 'C:/Users/nom de l'utilisateur/Documents/fichier.extension du fichier'


Le css est facilement utilisable (c'est le but) dans un fichier html : 
. Il faut utiliser la balise link, donner le chemin relatif (ou absolu mais peu commun) de l'image, le type du fichier : donc du css et enfin la nature du fichier : le css signifie Cascade Style Sheet il faut donc mettre 'stylesheet'
. Exemple : <link href="./stylesheet/style.css" rel="stylesheet" type="text/css" /> en partant du fichier index.php
