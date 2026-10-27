À propos du projet :

j'ai créé une petite application avec Symfony 7 pour comprendre le fonctionnement de base du framework. 
J'ai écrit un contrôleur, HelloController, qui contient deux routes :
/hello, qui affiche un message par défaut, et /hello/{nom}, qui affiche le nom que l'on écrit dans l'URL. 
Le contrôleur envoie ensuite une variable name à un template Twig (index.html.twig) qui se charge de l'afficher dans la page. 

L'objectif du TP :
      comprendre le lien entre une route, un contrôleur et une vue.

Les étapes que j'ai suivies :
j'ai d'abord créé le projet Symfony, 
j'ai ajouté le contrôleur HelloController.php dans src/Controller/ avec ses deux routes. 
j'ai créé le template index.html.twig dans templates/hello/ pour afficher la variable name. 
J'ai lancé le serveur avec symfony server:start et j'ai testé les deux adresses dans le navigateur pour vérifier que tout fonctionnait. 
