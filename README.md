# Installer la bdd

http://votreip/public/install.php

n'oubliez pas de changer le mot de passe de votre mysql dans config.php.

#Projet Analyser

Le projet analyser est celui de julie https://github.com/Madylune/Blog

#Quelles sont les methodes utilisées pour trouver des failles ?

Dans un premier temps j'ai essayer d'insérer dans un champ  un <script> alert ("test") </script>
Ensuite j'ai fait une InjectionSQL avec SELECT title FROM articles dans un second champ.

Il n'y a pas d'include, donc j'ai pas trouver de faille dans le temps imparti.
