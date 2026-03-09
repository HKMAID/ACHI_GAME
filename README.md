# Présentation :
Achi est un jeu en 2D, programmé en langague C en se servant de la bibliothèque SDL (Simple DirectMedia Layer) pour le représenter graphiquement. Le jeu a deux modes, le premier, le joueur joue contre un autre joueur, et l'autre, le joueur joue contre l'IA. Le jeu a évidemment suit des règles précises et se déroule en des deux phases définies. Pour le mode IA, l'algorithme de recherche MINMAX a été implémenté, nécessitant l'utilisation de structures de données et les concepts algorithmiques traitéés tout au long de mon parcours universitaire (Arbres, récursevité, graphes,etc.). 

# Compilation et exécution :
Depuis le terminal, en icluant la bibliothèque SDL et ses fichiers d'en-tête comme arguments.

Vous devez d'abord ajouter le chemin du dossier jeuachi\include dans les configurations du compilateur.

Vous allez vous déplacer vers le répertoire du projet (jeuachi) :
cd C:\...\...\jeuachi

Vous passez à la compilation, en utilsant la commande : gcc src/projet.c src/menu.c src/ai.c -o bin/prog -I include -L lib -lmingw32 -lSDL2main -lSDL2 -lSDL2_ttf

Lancez le fichier exécutable (prog.exe) de cette manière : .\bin\prog

# Affichage :
L'interface du jeu s'affichera à l'écran, où vous allez trouver un menu pour choisir le mode de jeu 
