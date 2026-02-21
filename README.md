> Apprenons à faire une application XR avec Godot 😁 et Git 🍻  

# Avertissement de départ

⚠️ Le but de la formation est de vous préparer à un emploi. Bien que ce cours vous apprenne à créer des jeux, l’objectif principal est de vous préparer à travailler pour un employeur XR dans l’industrie du temps réel. L’un n’empêche pas l’autre, mais l’accent est mis sur l’applicatif et non sur le jeu classique destiné aux magasins en ligne. Demande du/des centres de formation. ⚠️

**Les qualités nécessaires pour un développeur :**
* être autodidacte
* être rigoureux dans ses projets
* être discipliné dans son apprentissage
* savoir travailler en équipe
* **vouloir apprendre et se former toute sa vie**

**Exemples** d'application XR: visite dans les musée, simulation de physique et chimie en science, data analytics, simulation de pilotage, éducation, entraînement, visites 3D… La liste est bien longue.

_Nous accélérons votre apprentissage grâce à la formation, mais c’est à vous d’apprendre activement pour votre propre carrière.  
Cela étant dit, allons apprendre à faire de la XR avec Godot._


----------------------

# Introduction : Hello Godot XR

Nous avons la chance de pouvoir donner une première formation Godot 🪄 !!!

Je ne vous dis pas à quel point, pour [Maude](https://www.linkedin.com/in/maudelhoir/) et [Bryan](https://www.linkedin.com/in/bartolonibryan/), c’est magique que ça arrive.   
Je me suis mis à Godot l’année passée. Je suis encore novice dessus, mais avec 14 ans de Unity3D derrière moi…     
On va s’en sortir 😋    Voici la version corrigée :

À noter que cette formation suit une initiation à Unity et C# donnée par Arnaud Jopart et Cherif Younis,  
et est suivie par une formation Unreal Engine avec Cherif Younis et Vincent Leroy.  

Godot est assez magique.     
Super léger, il tourne littéralement sur votre téléphone.     
Tellement léger qu’une partie de ce cours aura lieu directement dans le casque 😉.    
_(Attention, il n’y a pas d’IA sur le casque pour vous aider ;) il faut bien pratiquer le cours)_  

Godot est open source et communautaire.     
Créé par des Argentins, il se veut utilisable sur des ordinateurs dits « patates » pour être accessible à tous.     
Il est coder par **Juan Linietsky** et **Ariel Manzur**, leurs collègues et la communauté.    

Mon choix de passer sur Godot s’est fait pour ces raisons :  
* Il tourne directement dans les casques XR !!!
* Il est multilingue* sur des PC : Python, Rust, C#, Lua…
  * Et ça, pour enseigner la programmation, c’est une vraie folie.
* Je sais qu’à mes 70 ans, dans 34 ans, il existera toujours.
* L’éditeur tourne sur : Linux, Mac, Raspberry Pi, Windows, Android, HoloLens, Magic Leap, SteamOS…
* Grâce au GDScript, qui est interprété, vos jeux sont modables à souhait.


## Quatre semaines pour apprendre

### **Première semaine**, nous allons créer un jeu pour les salles de cinéma :

**But : faire nos premiers pas sur Godot**

**Publications :**

* Comment faire une application 2D sur PC
* Comment faire une application 2D directement dans le Quest

**Points de passage :**

* Faire la vidéo de Brackeys sur un chevalier en 2D
* Jouer avec les UI et les inputs (en format NES)
* Ajouter la capacité de tirer des flèches
* Finir un niveau solo
* Faire un niveau à la TowerFall jouable avec 16 manettes NES
* Exporter l’application 2D solo sur le Quest 3
* Écouter les inputs des manettes du Quest 3
* Rendre le jeu jouable avec du code (voir S2W)

**Validation de compétences :**

* Finir un niveau jouable en solitaire
* Faire un niveau multijoueur à la TowerFall
* Savoir utiliser Git avec une branche `main`
* Challenge C# bonus : savoir finir son niveau avec du code C#


### **Deuxième semaine**, de la 2D à la 3D XR :

**But : apprendre à faire un projet 3D**

**Publications :**

* Comment faire une application XR sur PC
* Comment faire une application XR directement dans le Quest

**Points de passage :**

* Faire un archer dans le style de Hordes.io, jouable à la NES avec la vue caméra d’Arc Raiders
* Changer le comportement de la caméra si le jeu est en XR ou en 3D classique

  * Changer la skybox pour passer en mode passthrough en XR
* Savoir bouger et tourner des objets en 3D

  * Vector3, Quaternion, rotate et translate
* Savoir frapper à l’épée et tirer des flèches en 3D en format NES
* Passer en revue tous les mots-clés réservés de Godot vs C#
* Passer en revue tous les mots-clés importants des vidéos de Brackeys sur Godot
* Rendre le jeu jouable avec du code (voir S2W)

**Journée bonus :**

* Faire le menu de Maude pour la XR et y placer les objets 3D des artistes

**Passer en revue :**
Barrer des mots dans une checklist et en pratiquer un maximum.

**Validation de compétences :**

* Avoir un jeu 3D passthrough « flottant » compatible Quest 3
* Challenge : savoir orienter la flèche pour pratiquer les rotations en Godot


### **Troisième semaine**, nous étudierons Godot XR et son toolkit via un outil industriel de QA testing :

**But : pratiquer le XR toolkit dans le casque**

**Publications :**

* Comment utiliser GitHub sur un Quest
* Exporter depuis le Quest

**Points de passage :**

* Explorer ce que permet le Godot XR Toolkit comparé à VRTK, MRTK et XRTK de Unity

  * Comment bouger et se téléporter dans un niveau
  * Avec les deux manettes : bouger, tourner et zoomer dans un niveau
  * Attraper et déplacer des objets du niveau
  * Interagir avec les objets du niveau
  * Afficher des menus 2D
  * Composer une macro avec des objets 3D
* Tester votre macro sur le jeu jouable de la semaine précédente

  * Savoir les sauvegarder et les exécuter en les touchant (activation)
* Bonus : jouer avec les contenus des artistes de cette semaine via Git sur Godot

**Validation de compétences :**

* Faire un logiciel de macro 3D XR pour jouer au jeu de la semaine précédente


### **Quatrième semaine**, début : explorons ce qu’il nous manquerait pour la game jam avec les artistes.

**But : savoir travailler avec les artistes**

On ne peut pas tout étudier en trois semaines. Voyons donc ce qu’il nous manque pour que la game jam Godot avec les artistes se passe bien.

* Vérifier les concepts de base : texture, shader, matériaux, mesh, triangle, animation 3D, state machine, lumière, VFX, particules…
* Savoir importer et ajuster des modèles riggés, des textures et des SVG
* Voir si nous arrivons à intégrer dans Godot tous les assets que les artistes ont produits depuis le début de la formation XR sur le Quest

**Validation de compétences :**

* Passer sur les checklists A4 des mots-clés à connaître pour être junior

  * Barrer une fois si vous vous souvenez
  * Barrer deux fois si vous pensez savoir réutiliser
  * Barrer trois fois si vous maîtrisez

    * Attention : je peux vous mettre à l’épreuve pour valider.


### **Quatrième semaine**, fin : à vous de jouer. Petite game jam de groupe avec les artistes.

**But : pratiquer et valider votre apprentissage.**

*"Show me what you got"*

**Validation de compétences :**

* Finir un jeu en moins de 5 jours sur Git avec des artistes, sur Godot.

