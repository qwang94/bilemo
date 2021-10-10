# BILEMO
OpenClassrooms Project -> Symfony blog

Voici quelques instructions très simples à suivre pour installer ce projet sur votre machine.

1.Aller sur le lien du repository GitHub :
https://github.com/qwang94/bilemo

2.Cliquer le bouton vert "Code"

3.Copier le lien HTTPS

4.Créer un dossier local dans lequel vous voulez installer ce projet sur votre machine et utiliser votre terminal pour naviguer dans ce dossier 

5.Saisissez la commande suivante pour initialiser votre dossier au git:
git init

6.Saississez ensuite la commande suivante pour cloner le projet dans ce dossier
git clone lienHTTPS

7.Faites enfin "composer install" dans votre ligne de commande pour installer toutes les dépendances

8.Vous devez également créer une base de donnée en faisant la commande suivante:
symfony console doctrine:database:create
ou bien 
php bin/console doctrine:database:create

9.Mainteant le projet devrait être correctement installé sur votre machine, vous pouvez consulter le site web en faisant un "symfony serve" ou "php bin/console server:start" pour lancer le projet.

10.Pour tester l'api, il vous suffit de télécharger un logiciel type Postman, puis aller ouvrir les fichiers de documentation technique de l'API pour voir les différentes méthodes que vous pouvez utiliser pour vous servir de l'API.

