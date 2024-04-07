![Logo](/screen/fa6becb9ae0d10c00020bd40edfdd6cb.png)

# Sortir.com

Une plateforme de réseau social destinée à la communauté de l'ENI École Informatique, facilitant l'organisation et
la participation à des activités de détente hors du temps de formation.


## Objectif
Créer un espace numérique où stagiaires actuels et anciens de l'ENI peuvent facilement organiser,
partager et s'inscrire à des sorties, renforçant ainsi les liens et favorisant les échanges au sein
de la communauté éducative.

## Présentation du projet
Ce projet vise à tranformer la manière dont les membres de l'école ENI interaggissent en dehors des
heures de formation. En remplaçant l'ancien système d'affichage papier par une plateforme web intuitive, il répond à un besoin croissant de connexion et d'interaction. 
Facilitant la diffusion d'informations et l'inscription aux activités, cette initiative est destinée à enrichir l'expérience étudiante et à maintenir un lien solide entre tous les membres de l'école, actuels et anciens, en créant un espace dédié au partage, à la détente et à la découverte mutuelle.


## Technologies :
- Symfony v6.4.5
  - Twig
- Composer
- WAMPServer
- Bootstrap

## Pré-requis :
- Composer
- Symfony CLI 
- Symfony v6.4.5

## Installation :
- git clone git@github.com:MatthieuSKRZYPCZAK/Sortir.git
- cd Sortir
- composer install
- Configurez DATABASE_URL
- Création de la base de données : symfony console doctrine:database:create
- Création des tables dans la base de données en appliquant les fichiers de migration :  symfony console doctrine:migrations:migrate
- Lancez les fixtures pour peupler la base de données avec un ensemble de données de test : symfony console doctrine:fixtures:load
- symfony server:start

## Screenshot :

![Logo](/screen/Screenshot%202024-04-07%2011.21.21.png)
![Logo](/screen/Screenshot%202024-04-07%2011.32.22.png)