# Ohmyfood

Troisième projet du parcours "Développeur web" chez OpenClassrooms. 

L'objectif est d'intégrer et dynamiser une page web avec des animations CSS en utilisant le préprocesseur Sass. 

- [Cahier des charges](./public/notes/Ohmyfood%20-%20Brief%20Cr%C3%A9atif.pdf)

- [Aspect visuel du site](./public/notes/Ohmyfood%20-%20Aspect%20visuel.pdf)

![screenshot du site](./public/notes/Ohmyfood%20-%20readme%20cover.jpg)

# Compétences évaluées

1. Développer un site proposant le menu de 4 restaurants.
2. Implémenter une interface responsive en mobile first.
3. Mettre en œuvre des effets/animations CSS graphiques avancés
4. Utiliser un système de versioning pour le suivi du projet et son hébergement.
5. Assurer la cohérence graphique d'un site web.
6. Mettre en place son environnement Front-End.
7. Mettre en place une structure de navigation pour un site web.

# Technologies
**Utilisées:** 
- CSS : Animations, Mediaqueries ...
- Sass : Mixins, Variables, Keyframes, Loops, Nesting ...
- Post CSS Autoprefixer 
- NPM scripts

**Interdites:** 
- Javascript 
- Framework CSS (Bootstrap, Tailwind)


# Scénario

Vous venez d’être recruté chez Ohmyfood!, en tant que développeur junior. 

Ohmyfood! est une jeune startup qui voudrait s'imposer sur le marché de la restauration. L'objectif est de développer un site 100% mobile qui répertorie les menus de restaurants gastronomiques. En plus des systèmes classiques de réservation, les clients pourront composer le menu de leur repas pour que les plats soient prêts à leur arrivée. 

Le site contiendra 4 menus dans un premier temps. Voici le [brief](https://s3.eu-west-1.amazonaws.com/course.oc-static.com/projects/Front-End+V2/P3+CSS+animations/DW+P3+-+Brief+creatif+-+Ohmyfood!.pdf) que vous établissez avec le CTO, Paul. De retour à votre bureau, vous trouvez un mail de Fanny qui vous envoie les maquettes du site.

Pour ce projet, vous versionnez tout votre code sur Github avec des commits réguliers pour suivre son avancement et publier le site en ligne plus facilement.

Vous avez désormais tous les éléments pour construire ce site mobile. 

# Livrables
## Pages à intégrer selon les maquettes :
- **Page d’accueil** 
1. Affichage de la localisation des restaurants. À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu. 
2. Une courte présentation de l’entreprise. Une section contenant les 4 menus sous forme cartes. Au clic sur la carte, l’utilisateur est redirigé vers la page du menu. 

- **Pages de menu (x4)**
1. 4 pages contenant chacune le menu d’un restaurant.

- **Footer**
1. Le footer est identique sur toutes les pages.
2. Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.

- **Header**
1. Le header est présent sur toutes les pages.
2. Sur la page d’accueil, il contient le logo du site.
3. Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil


# Effets graphiques et animations
**Boutons**
- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.
- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, unbouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol au lieu du clic.

**Page d’accueil**
- Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini,toute proposition est donc la bienvenue tant qu’elle est cohérente avec la chartegraphique du site.

**Pages de menu**
- À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.
- Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser dela droite vers la gauche. Pour cette première version, l’effet peut apparaître au survolau lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension. Un exemple de l’effet attendu est fourni  

# Notes 
**Polices :**
- Logo & titres: Shrikhand
- Texte: Roboto

**Couleurs :**
- Primaire: #9356DC
- Secondaire: #FF79DA
- Tertiaire: #99E2D0

**Contraintes :**
- Approche mobile-first: oui
- Maquette mobile : oui
- Maquette desktop : à improviser
- Validation W3C HTML : à passer, warning autorisés
- Validation W3C CSS : à passer, warning autorisés
- Compatibilité : Dernières versions de Chrome, Firefox & Safari

