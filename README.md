# imc
Le code fourni
-crée un patient,
-lit son poids et sa taille depuis le clavier et les lui affecte ;
-affiche les données du patient ainsi que son IMC.

Les deux dernières étapes sont répétées tant que le poids et la taille ne sont pas nuls.

La définition de la classe Patient manque et c’est ce qu’il vous est demandé d’écrire.

Spécifications de la classe Patient

Un patient est caractérisé par un poids et une taille. Vous nommerez les attributs correspondants respectivement masse et hauteur (veuillez respecter strictement ces consignes).

Les méthodes spécifiques à un patient sont :

-une méthode init prenant en paramètre deux double, le premier pour initialiser le poids du patient et le second pour initialiser sa taille ;
ces données ne seront affectées aux attributs du patient que si elles sont toutes les deux positives ;
dans le cas contraire, la taille et le poids du patient seront tous deux initialisés à zéro ;
pour simplifier, il n’y a pas d’autre contrôle à faire sur ces données ;

-une méthode afficher permettant d’afficher sur le terminal les caractéristiques du patient en respectant strictement le format suivant :
Patient : <poids> kg pour <taille> m
où <poids> est à remplacer par le poids du patient et <taille> par sa taille ;
cet affichage sera terminé par un saut de ligne.

-une méthode poids retournant le poids du patient ;
-une méthode taille retournant la taille du patient ;
une méthode imc retournant l’IMC du patient : son poids divisé par le carré de sa taille ;
en cas de taille nulle, cette méthode retournera zéro.
