**Présentation du projet Puissance 4 - Python**

Ce projet a été réalise dans le cadre de la validation du cours de Python donné par Selim Mellouk par Stephen Claco, Adrien Demaegdt, Aldin Steeve Houssou et Arthur Souchon

Plusieurs modes de jeu sont disponibles et sont présentés ci-dessous:

**Joueur vs Joueur - Joueur vs IA**
Un joueur humain peut jouer au jeu de puissance 4. Lorsqu'il va lancer la partie, il devrait à chaque fois écrire un entier de 1 à 7 (les inputs sont blindés) afin de sélectionner la colonne dans laquelle il veut jouer. Une fenêtre va s'ouvrir afin d'afficher le tableau. Cependant on ne peut pas cliquer dessus pour sélectionner sa colonne, c'est pourquoi on vous conseille de jouer en écran scindé entre la fenêtre de jeu et le notebook.

**IA vs IA**
On peut également faire s'affronter des IA entre elles pendant plusieurs parties. Il y a trois IA différentes :

Une **IA Aléatoire** qui joue de manière totalement aléatoire entre les sept colonnes du Puissance 4. Elle est donc simple à battre.
Une **IA pas trop bête** qui optimise ses coups en fonctions des alignements et qui essaie de jouer plutôt vers le centre afin de se laisser le plus d'options possibles. A chaque coup, elle simule ce que donnerait le tableau en jouant dans chaque colonne et choisit la colonne qui lui donne le meilleur tableau possible.
Une **IA Intelligente** qui reprends les mêmes principes que l'IA précedente, sauf qu'elle anticipe aussi les coups de l'adversaire et donc elle peut essayer de contrer ce qu'il va faire.
Rapport de fin de match
A la fin d'un affrontement (potentiellement plusieurs matchs), vous aurez un petit rapport vous indiquant le nombre de parties jouées, et le nombre de parties remportées par chacun des joueurs. Vous trouverez également un graphique, réalisé avec matplotlib, indiquant l'évolution du winrate de chacun des deux joueurs.

Ce qu'on vous conseille de tester
Etant donné que certains tests peuvent durer longtemps, voilà ce qu'on vous conseille de tester (entre chaque test il sera nécessaire de relancer le kernel) :

Un match en Joueur vs Joueur ou Joueur vs IA (pensez à vous mettre en écran scindé entre la fenêtre de jeu et le notebook)
Une simulation IA Aléatoire vs IA Intelligente (environ 50-100 parties pour pas que ça soit trop long, mais pour voir que l'IA Intelligente écrase l'IA Aléatoire)
Une simulation de plus grande ampleur entre l'IA Aléatoire et l'IA pas trop bête (200-300 matchs ? )
Si vous avez envie de tester un match entre l'IA pas trop bête et l'IA intelligente, allez-y, mais étant données que ces IA sont régies par des règles déterministes, toutes les parties entre ces IA sont exactement identiques.
