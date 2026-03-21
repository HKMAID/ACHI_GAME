# Présentation
Achi est un jeu en 2D, programmé en langage C en se servant de la bibliothèque SDL (Simple DirectMedia Layer) pour le représenter graphiquement. 

Le jeu a deux modes, JvJ et joueur contre l'IA. Le jeu évidemment suit des règles précises et se déroule en deux phases définies.

# Compilation et exécution 
Depuis le terminal, en icluant la bibliothèque SDL et ses fichiers d'en-tête comme arguments.

Vous devez d'abord ajouter le chemin du dossier jeuachi\include dans les configurations du compilateur.

Vous allez vous déplacer vers le répertoire du projet (jeuachi) :
cd C:\...\...\jeuachi

Vous passez à la compilation, en utilsant la commande : gcc src/projet.c src/menu.c src/ai.c -o bin/prog -I include -L lib -lmingw32 -lSDL2main -lSDL2 -lSDL2_ttf

Lancez le fichier exécutable (prog.exe) de cette manière : .\bin\prog

# Affichage 
L'interface du jeu s'affichera à l'écran, où vous allez trouver un menu pour choisir le mode de jeu 
