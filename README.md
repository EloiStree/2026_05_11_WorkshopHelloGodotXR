**"Montrer de l'amour pour l'engine."** GDC, Cherif



---------------------


# Working on it:

To Do: 
- Godot XR Tools video and check list: https://github.com/EloiStree/HelloGodotXR/issues/25
- How to use Git on Quest3 and Android
- How to use Git an Quest 3 from a PC with Godot
- How to relocate a scene based on two flats point (ground-wall)
- How to rotate stuff.
- Ajouter au Keybword : https://github.com/EloiStree/HelloGodotEngineKeyword/issues/265


Video"
- Vous avez fait un projet Godot sur votre telephone android ?
  - Comment le sauver avec Git: https://youtu.be/Sy2_I87Rws0
- Vous avez recu un tablette android ?
  - Comment utilsier godot et git via termux : https://youtu.be/4-LGN76QHdE

About AI use:
- You need to be the fail safe of it:
  - https://youtu.be/dbMXi9q78Tk?t=843

--------------------

> Apprenons à faire une application XR avec Godot 😁 et Git 🍻  

# Avertissement de départ

⚠️ Le but de la formation est de vous préparer à un emploi. Bien que ce cours vous apprenne à créer des jeux, l’objectif principal est de vous préparer à travailler pour un employeur XR dans l’industrie du temps réel. L’un n’empêche pas l’autre, mais l’accent est mis sur l’applicatif et non sur le jeu classique destiné aux magasins en ligne. Demande du/des centres de formation. ⚠️

**Les qualités nécessaires pour un développeur :**
* être autodidacte
* être rigoureux dans ses projets
* être discipliné dans son apprentissage
* savoir travailler en équipe
* **vouloir apprendre et se former toute sa vie**

**Exemples d’applications XR :** visites dans les musées, simulations de physique et de chimie en sciences, analyse de données, simulation de pilotage, éducation, entraînement, visites 3D, construction, architecture, outils pour chirurgiens, rééducation musculaire… La liste est bien longue.

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

**Dates :**

* 6 avril au 8 mai : Unity XR
* 11 mai au 5 juin : Godot XR
* 8 juin au 3 juillet : Unreal Engine XR
* 6 juillet au 14 août : Atelier de groupe

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

En très résumé :
* Faire un jeu 2D de Brackeys dans le Quest 3
* Placer des scenes Godot en AR avec des feuilles A4.
* Créer des macros pour pratiquer le XR Toolkit
* Petite game jam avec les artistes
  * Se préparer tout du long à pouvoir travailler avec les artistes


### **Pre-Semaine Git**

**But : apprendre à utiliser Git**

Voir: https://github.com/EloiStree/2026_04_07_WorkshopArtsAndGit/tree/main


### **Première semaine**, nous allons créer un jeu 2D dans le Quest

**But : faire nos premiers pas sur Godot**

**Publications :**

* [ ]  Comment faire une application 2D sur PC
* [ ]  Comment faire une application 2D directement dans le Quest

**Points de passage :**

* [ ]  Faire la vidéo de Brackeys sur un chevalier en 2D
* [ ]  Jouer avec les UI et les inputs (en format NES)
* [ ]  Ajouter la capacité de tirer des flèches
* [ ]  Finir un niveau solo
* [ ]  Exporter l’application 2D solo sur le Quest 3
* [ ]  Écouter les inputs des manettes du Quest 3
* [ ]  Bonus: Rendre le jeu jouable avec du code (voir S2W)
* [ ]  Hors-sujet, challenge:  Faire un niveau à la TowerFall jouable avec 16 manettes NES

**Validation de compétences :**

* Finir un niveau jouable en solitaire
* Savoir utiliser Git avec une branche `main`
* Bonus: Faire un niveau multijoueur à la TowerFall
* Hors-sujet, challenge C#:  savoir finir son niveau avec du code C# et UDP


### **Deuxième semaine**, de la 2D à la 3D en XR

**But : charger une scène Godot dans la vraie vie via une feuille A4**

**Publications :**

* [ ] Comment faire une application XR sur PC
* [ ] Comment faire une application XR directement sur le Quest


**Points de passage :**

### Exercice minimum :

* [ ] C’est quoi un Vector3 ?
* [ ] C’est quoi une direction ?
* [ ] C’est quoi une rotation ?
* [ ] C’est quoi, déjà, la trigonométrie ?
* [ ] Accéder aux points des manettes
* [ ] Savoir dessiner une ligne dans l’espace 3D
* [ ] Relocaliser les calculs en `Vector.ZERO`
* [ ] Charger une scène selon la distance entre deux points
* [ ] Relocaliser la scène sur la feuille A4

### Exercice secondaire :

Voir : [https://300-gaming-space.itch.io/initiation-au-mtier-de-game-artist-3d](https://300-gaming-space.itch.io/initiation-au-mtier-de-game-artist-3d)

* [ ] Refaire l’outil de visualisation 3D de Maude
* [ ] Charger l’outil sur la feuille
* [ ] **Challenge Junior :**

  * [ ] Charger les informations du modèle 3D depuis des ressources
* [ ] **Challenge Medior :**

  * [ ] Charger les informations depuis les fichiers : `.glb`, `README.md`, `.toml`
  * [ ] Charger un `.fbx` avec son animation par défaut
  * [ ] Ajouter un bouton 3D pour parcourir les animations du modèle

**Validation des compétences :**

* **Minimum :** Avoir une application Quest 3 qui charge une scène depuis une feuille A4 et A5.
* **Medium :** Avoir une application Quest 3 qui charge des modèles 3D d’artistes.
* **Senior :** Avoir une application Quest 3 qui charge des modèles 3D depuis un dossier sur le device.
* **Hors-sujet, challenge :** Refaire le menu Gaming Space 300 de Maude pour la XR et y placer les objets 3D des artistes.

### **Troisième semaine**, pratiquez Godot XR et son toolkit via un outil industriel de QA testing 

**But : pratiquer le XR toolkit dans le casque**

**Publications :**

* [ ]  Comment utiliser GitHub dans le Quest
  
**Points de passage :**

* [ ] Explorer ce que permet le Godot XR Toolkit comparé à VRTK, MRTK et XRTK de Unity
  * [ ] Comment bouger et se téléporter dans un niveau
  * [ ] Avec les deux manettes : bouger, tourner et zoomer dans un niveau
  * [ ] Attraper et déplacer des objets du niveau
  * [ ]  Interagir avec les objets du niveau
  * [ ]  Afficher des menus 2D
* [ ]  Composer une macro avec des objets 3D
*  [ ] Tester votre macro sur le jeu jouable de la semaine précédente
  *  [ ] Savoir les sauvegarder et les exécuter en les touchant (activation)
* [ ]  Bonus : jouer avec les contenus des artistes de cette semaine via Git sur Godot
* [ ]  Bonus : écouter à des devices bluetooth
  * [ ]  une manette Xbox et Playstation
  * [ ]  un clavier et une souris
  * [ ]  un scanner de bare code
  * [ ]  utiliser les mains pour interagir

**Validation de compétences :**

* Faire un logiciel de macro 3D XR pour jouer au jeu de la semaine précédente


### **Quatrième semaine**, début : explorons ce qu’il nous manquerait pour la game jam avec les artistes

**But : savoir travailler avec les artistes**

On ne peut pas tout étudier en trois semaines. Voyons donc ce qu’il nous manque pour que la game jam Godot avec les artistes se passe bien.

* [ ]  Vérifier les concepts de base : texture, shader, matériaux, mesh, triangle, animation 3D, state machine, lumière, VFX, particules…
* [ ]  Savoir importer et ajuster des modèles riggés, des textures et des SVG
* [ ]  Voir si nous arrivons à intégrer dans Godot tous les assets que les artistes ont produits depuis le début de la formation XR sur le Quest

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



_________________


# Un peu trop gaming.

La formation est un peu trop gaming.
Sur la semaine deux.

Une alternative est que je recreer un tutorial sur la triangulation par les manettes, voir:
- https://github.com/EloiStree/2025_06_05_TwoPointsQuadLoader

Ce qui ferait un bon cours sur le Vector3, Direction, Quaternion et rotation.




