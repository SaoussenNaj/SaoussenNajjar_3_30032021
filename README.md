
## ProjetN°3: Dynamiser un site web avec des animations CSS


## ***Objectif:***

- Ohmyfood! est une entreprise de commande de repas en ligne. Le concept permet aux utilisateurs de composer leur propre menu et réduire leur temps d’attente. 

## Contraintes techniques:

- La cible étant les personnes connectées et pressées, le site sera développé en utilisant l’approche mobile-first. 
- Pour cette raison, seules des maquettes mobiles seront réalisées. Sur tablette et desktop, le site devra s’adapter, mais ces supports n’étant pas prioritaires, leur mise en page est libre.
- L’ensemble du site devra être responsive sur mobile, tablette et desktop. 
- Les pages devront passer la validation W3C en HTML et CSS sans erreur. 
- Le site doit être parfaitement compatible avec les dernières versions desktop de Chrome et Firefox

## Technologies utilisées:

 - Le développement devra se faire en CSS, sans JavaScript. 
 -  Aucun framework ne devra être utilisé, en revanche l’utilisation de SASS serait un plus. 
 - Aucun code CSS ne devra être appliqué via un attribut style dans une balise HTML
- La police du site est Shrikhand.
- Texte: Roboto

## Fonctionnalités:

 ### Page d’accueil (x1):
 
 ● Affichage de la localisation des restaurants. 
 ● Une courte présentation de l’entreprise.
 ● Une section contenant les 4 menus sous forme cartes. 
 Au clic sur la carte, l’utilisateur est redirigé vers la page du menu. 
 
 ### Pages de menu (x4) :
 
 ● Quatres pages contenant chacune le menu d’un restaurant. 
 #### Footer 
 - Le footer est identique sur toutes les pages. 
 - Au clic sur “Contact”, un renvoi vers une adresse mail est effectué. 
 #### Header 
- Le header est présent sur toutes les pages. 
- Sur la page d’accueil, il contient le logo du site. 
- Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil

## Effets Graphiques:

Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils devront utiliser les animations ou transitions CSS, pas de JavaScript ni de librairie.

### Boutons:

- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible. 

- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Au survol, il devra se remplir progressivement.

### Page d'accueil:

Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.

### Page de menu:

À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”.
Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension. Un exemple de l’effet attendu est fourni.
