V8
démarrage *[2022.12.18]*
- [ ] section 1 : landing
- [X] ***12.22-00h30*** section 2 : recent works
- [X] ***12.30-19h20*** section 3 : filter
  - [ ] add quick play button next to video projects titles cards, which will popup the video embed to quickly watch the video
  - [X] ***12.31-11h30*** highlight selected filters in projects cards
  - [ ] "No projects found" message
  - [ ] finish each TODOs in the code
- [ ] projectPages
  - [ ] close with history
  - [ ] when clicking on a project, remember order of previous and next project so that we can switch to them with arrows at the end
- [ ] finish projects data-base
- [ ] section 4 : contact
- [ ] small menu : translate, quick social links, logo
  - [ ] use y-navBoom (rename) when clicking on buttons or opening menu
- [ ] fix overlayscrollbars backdrop-filter not working in chrome
- [ ] fix overlayscrollbars unable to scroll when mouse is on top of fixed elements
- [ ] loading screen for thumbnails & calculations checks (& until page loaded event), all spawn animations after removing loading screen
- [ ] small scroll snapping to : content-sections, recent projects cards

<br>

---

<br>

V7
démarrage *[2022.10.13]*
- [X] ***10.15-17h50*** - utiliser un bundler (babel + webpack)
- [X] ***10.23-16h00*** - site fonctionnel déployé
  - [X] ***10.17-20h30*** - dependencies
  - [X] ***10.17-23h00*** - virer les implicit globals
  - [X] ***10.23-15h45*** - build fonctionnel sur serveur
  - [ ] ~~build fonctionnel en local~~ Security Error: "May not load data from file:///" donc je vais aller me faire foutre ça marche pas en local :(
- [X] ***10.23-17h25*** - déployer sur l'url publique yolan.art
- [X] ***10.25-16h15*** - n'avoir qu'une seule page : logo fullscreen et avoir en-dessous la liste des projets
- [X] ***10.25-16h50*** - petit texte attaché au logo pour dire que c'est mon portfolio
- [X] ***10.25-17h00*** - y-navboom qui reste au maintient du clique
- [X] ***10.27-12h50*** - optimiser la création des ynavboom (changer le svg-circle pour une div border-radius) (raisons de performances)
- [ ] ***[later]*** - ~~optimiser la suppression des ynavboom (supprimer les booms par salve et non individuellement)~~
- [X] ***10.26-14h45*** - redesign scrollbar (plus fin, effet d'inversion monochrome)
- [ ] ***[later]*** - ~~corriger la scrollbar n'ayant pas d'animation d'apparition slide in depuis le côté quand la souris est déjà dans la zone de scroll~~
- [ ] refonte visuelle
- [ ] optimiser l'interface des fiches de projet sur mobile
- [ ] utiliser des unités en "em" et "rem" au lieu de "px"
- [X] ***10.27-13h40*** - permettre de fermer les fiches de projets en retournant en arrière dans l'historique
- [ ] rajouter des boutons de réseaux sociaux dans la zone landing (instagram, twitter, github) (le faire de manière à pouvoir en rajouter plus tard)
- [ ] scroll down notice, clickable
- [ ] système de filtrage : par catégorie, par date, par contexte, par filtre
  - [ ] juste au-dessus des catégories
  - [ ] au clique sur les étiquettes dans les fiches de projet
- [X] ***10.29-1h00*** - création des catégories par javascript (en fonction de la base de données)
- [X] ***10.31-21h00*** - création des projets par javascript (en fonction de la base de données)
- [ ] ***[later]*** - ~~utiliser les sous-catégories : spécifier donnée "level=2" pour projets à ranger dedans ; définir une nouvelle catégorie avec son nom de ainsi que son parent (dans le cas où elle n'existe pas, fallback sur default ; dans tous les cas créer sous catégorie dans la catégorie du projet si "level=2")~~
- [ ] refaire l'organisation des projets :
  - [X] ***10.28-15h20*** - utiliser un fichier externe
  - [X] ***10.28-20h00*** - filtres, paramètres de chaque projet (and fallback to default values)
  - [ ] réfléchir à une nouvelle arborescence
  - [ ] rajouter des nouveaux projets
  - [ ] réparer les vidéos décédées
- [ ] commenter tout le bordel de mon code javascript car c'est le zbeul pour s'y retrouver
- [ ] loading screen (until page loaded event), all spawn animations after removing loading screen
- [ ] synchronize both Y arrows for spawn animation
