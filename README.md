# Ohmyfood

2ème projet du parcours "Développeur Web" chez OpenClassrooms. Ce projet a été réalisé en avril 2021. 

![Accueil](https://user-images.githubusercontent.com/77798378/133880658-576b79f7-49a2-4171-8216-e22f88a3519a.png)
![Menu - À la française](https://user-images.githubusercontent.com/77798378/133880700-61b8e038-5faf-45d0-be69-2758858efc47.png)

[Cliquez ici](https://www.youtube.com/watch?v=YsiGPGa0_Cc) pour voir la vidéo du projet

## Identité graphique
- Polices Logo et titres: Shrikhand Texte: Roboto 
- Couleurs: Primaire: #9356DC | Secondaire: #FF79DA | Tertiaire: #99E2D0 

## Fonctionnement
### Technologies
- Le développement a été fait en CSS, sans JavaScript
- Utilisation de SASS
- Aucun code CSS via un atribut style dans le HTML

### Compatibilité
- La cible étant les personnes connectées et pressées, le site a été développé en utilisant l’approche mobile-first. Pour cette raison, seules des maquettes mobiles ont été réalisées. 
- Sur tablette et desktop, le site s’adapte, mais ces supports n’étant pas prioritaires, leur mise en page était libre. 
- L’ensemble du site est responsive sur mobile, tablette et desktop. 
- Les pages devront passe la validation W3C en HTML et CSS sans erreur. 
- Le site est parfaitement compatible avec les dernières versions desktop de Chrome et Firefox. 


## Enjeux

- Développer un site proposant le menu de 4 grands restaurants parisiens
- Permettre la réservation en ligne et la composition de menu

## Livrables 

### Contenu des pages

#### Pages d'accueil (x 1)
- Affichage de la localisation des restaurants. À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu. 
- Une courte présentation de l’entreprise. 
- Une section contenant les 4 menus sous forme cartes. Au clic sur la carte, l’utilisateur est redirigé vers la page du menu.  

#### Page de menu (x 4)
- 4 pages contenant chacune le menu d’un restaurant. 

#### Footer
- Le footer est identique sur toutes les pages. 
- Au clic sur “Contact”, un renvoi vers une adresse mail est effectué. 

#### Header 
- Le header est présent sur toutes les pages. 
- Sur la page d’accueil, il contient le logo du site. 
- Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil 

### Effets graphiques et animations 

Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils utilisent les animations ou transitions CSS, pas de JavaScript ni de librairie. 

#### Boutons
- Au survol, la couleur de fond des boutons principaux s'éclaircit légèrement. L’ombre portée est plus visible.  
- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il  se remplira progressivement. Pour cette première version, l’effet peut être apparaître au survol sur desktop au lieu du clic. 

#### Page d'accueil
- Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, vous pourrez voir un aperçu. Il va apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site. 

#### Page de menu
- À l’arrivée sur la page, les plats apparaîtront progressivement avec un léger décalage dans le temps. Ils apparaitront un par un. Un exemple de l’effet attendu est fourni. 
- Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet apparaîtra au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il sera rogné avec des points de suspension. Un exemple de l’effet attendu est fourni. 


## Compétences 

- Mettre en place une structure de navigation pour un site web 
- Mettre en oeuvre des effets CSS graphiques avancés
- Assurer la cohérence graphique d'un site web
