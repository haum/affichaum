# AffichHAUM

Un afficheur 4x7 segments utilisable réutilisable pour de nombreux projets à
base de microcontrôleurs.

## Utilisation

Le protocole de communication microcontrôleur ↔ microcontrôleur retenu est le
protocole SPI pour sa simplicité de mise en œuvre et son faible impact sur la
charge du contrôleur.

Le maitre SPI peut demander à l'écran d’afficher des éléments de différentes
manières :

 - Affichage de caractères ASCII ;
 - Affichage d’entiers (ou de flottants à virgule fixe, ce qui revient au
   même) ;
 - Affichage manuel en choisissant les segments à allumer ou éteindre pour des
   cas particuliers (animations personnalisées, …).
