# Analyse d'une phrase (Algorithme)

## Objectif

Créer un algorithme qui lit une phrase caractère par caractère (se terminant par un point) et qui détermine :

La longueur de la phrase
Le nombre de mots
Le nombre de voyelles

## Principe

L’algorithme utilise trois variables comme compteurs :

longueur : nombre de caractères
mots : nombre de mots (séparés par un espace)
voyelles : nombre de voyelles

Chaque caractère est analysé un par un jusqu’au point final.

## Fonctionnement
On lit chaque caractère
On augmente :
la longueur à chaque caractère
le nombre de mots quand on rencontre un espace
le nombre de voyelles si le caractère est une voyelle

## Remarque

Le dernier caractère de la phrase est toujours un point.
