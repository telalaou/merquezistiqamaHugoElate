Installation de l’environnement de travail :
1.	Ovrir un terminal (ou console) selon l’Os de votre ordinateur
2.	Installer homebrew en suivant la manière indiquée dans le lien suivant https://brew.sh/index_fr
3.	Installer la librairie hugo

Déploiement du site en production :
1.	depuis un terminal se placer à la racine du projet dans le repertoire merquesistiqamaHugoElate
 et lancer la commande suivante : hugo -b http://markezalistiqamah.com -D
2.	aller sur le site de l’hebergeur https://fr.000webhost.com/
3.	se connecter 
login : markezalistiqamah@gmail.com  
mot de passe : moualimarabya
4.	Cliquer sur « Gérer le site » dans le rectangle violet markezalistiqamah.com
5.	Cliquer sur File manager
6.	Séléctioner tous les éléments et supprimer les en cliquant sur la corbeille
7.	Cliquer sur « upload files » pour charger de nouveaux éléments
8.	Faire glisser le contenu du repertoire public et valider

Pour modifier les images du sites (décrivant les contenus des programmes) :
1.	Remplacer les nouvelles images par les anciennes dans le repertoire public/images
2.	Respecter l’extension png
3.	Les images doivent etre au format 850 x 1080px
4.	Lancer depuis votre terminal la commande  « hugo server -D » et visualiser le résultat
