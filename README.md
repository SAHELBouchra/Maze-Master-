# Maze Master 🤖🏁

Maze Master est un projet visant à développer un robot autonome capable de résoudre un labyrinthe en utilisant l'algorithme de remplissage par inondation (Flood Fill Algorithm). Le robot utilise des capteurs à ultrasons pour détecter les obstacles et construire une carte de l'environnement tout en trouvant et suivant le chemin le plus court jusqu'à la sortie.

<h2>Fonctionnalités 📋</h2>

Navigation autonome : Le robot se déplace de manière indépendante dans un labyrinthe inconnu, sans intervention humaine.

Détection des obstacles : Utilisation de capteurs à ultrasons pour détecter les murs et les ouvertures.

Exploration et cartographie : Création d'une carte virtuelle en temps réel grâce à l'algorithme Flood Fill.

Optimisation du chemin : Résolution du labyrinthe en identifiant et en empruntant la route la plus courte vers la sortie.

<h2>Technologies et outils utilisés 🛠️</h2>

Matériel :
Robot mobile équipé de capteurs à ultrasons
Microcontrôleur (Arduino ou similaire)

Logiciel :
MATLAB pour la simulation et la validation de l'algorithme.

Programmation en C++ ou Python pour le contrôle embarqué.

<h2>Algorithme de remplissage par inondation (Flood Fill) 🧩</h2>

Initialisation : Le robot commence au point de départ, enregistre sa position et initialise une carte vierge du labyrinthe.

Détection des obstacles : Les capteurs à ultrasons détectent les murs et les ouvertures pour mettre à jour la carte virtuelle.

Exploration : Le robot explore les chemins disponibles en suivant des règles prédéfinies pour évaluer les options à chaque embranchement.

Marquage : Les zones visitées sont marquées pour éviter les répétitions et optimiser les mouvements.

Retour en arrière : En cas de point mort, le robot revient sur ses pas pour explorer les chemins restants.

Résolution : Une fois la cartographie terminée, le robot identifie la sortie et emprunte le chemin le plus court pour sortir du labyrinthe.

## Contact

If you would like more information about this project, feel free to contact me at:  
**Email**: [bouchrasahel43@gmail.com](mailto:bouchrasahel43@gmail.com)

