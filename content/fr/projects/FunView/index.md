---
title: "FunView"
weight: 6
resources:
    - src: shapes.jpg
      params:
          weight: -100
---

Travail de bachelor  
Auteur: Matthieu Vos  
Langue: Français  
Document disponible [ici](/team-smv/projects/Travail_de_Bachelor_Matthieu_Vos.pdf)

## Abstract

À l’heure actuelle, l’informatique est omniprésente. Qu’on l’utilise à des fins de loisirs ou de manière professionnelle, tout le monde emploie un outil informatique. 
Cependant, dans le système scolaire, l’informatique et son enseignement sont souvent relié aux mathématiques. Beaucoup y voient un amas de formules.
Cependant, l’informatique peut très bien être utilisée pour résoudre des problèmes sans calcul. 
Il suffit de voir tous les domaines dans lesquels un outil informatique est présent.
La photographie, le sport, les jeux vidéo et la communication sont des exemples parmi d’autres.
Le data mining est un domaine de l’informatique utilisé dans de nombreux contextes par exemple. 
On l’utilise pour l’étude du comportement humain ou animal ou afin de prédire la météorologie.
Dans le cadre d’un remaniement de l’enseignement de l’informatique dans les collèges de Genève, des cours ayant pour but d’introduire l’informatique sans utiliser les mathématiques ont été aménagés. 
Pour ce faire, de nouveaux instruments pédagogiques doivent être développés. FunBlocks est un outil développé dans le but de sensibiliser l’élève à la programmation informatique.
Il consiste à manipuler des termes et des expressions, sous forme de blocs, afin de représenter des données et des instructions.
FunBlocks utilise la programmation fonctionnelle contrairement à d’autre programmes visant à offrir un environnement visuel de programmation qui est basé sur la programmation impérative.
La programmation fonctionnelle qui consiste à représenter le programme sous la forme de fonctions composées d’expressions plus complexes. 
Le but est ainsi de mieux pouvoir définir et manipuler des structures de données. Cette représentation se rapproche beaucoup de la manière dont l’algèbre est enseignée au collège de Genève.
FunBlocks permet d’avoir un moyen intuitif d’écrire un programme afin de représenter un état et ses dérivations.
Les blocs sont une représentation simple et claire, mais pas forcément familière pour un jeune élève. 
Que représente un bloc dans un autre bloc? Pourquoi deux blocs sont équivalents? 
Il a donc été suggéré d’introduire une image qui donnerait une interprétation des blocs. 
Ainsi, l’utilisateur aura un outil plus familier pour comprendre les mécanismes que FunBlocks présente. 
L’extension FunView a pour objectif de rajouter une représentation graphique à l’état présent dans FunBlocks. 
Il a donc été nécessaire de trouver une illustration simple d’un bloc, mais gardant des structures très présentes en informatique comme des listes.

Ces objectifs en tête, il a donc fallu comprendre le fonctionnement de FunBlocks pour construire FunView et définir son domaine. 
Une grammaire permettant de représenter un état sous une forme graphique a été créée. 
Cette grammaire définit l’ensemble des représentations graphiques réalisables à l’aide de FunView. 
FunView peut traduire un bloc accepté par cette grammaire en une série d’instructions. 
Ces instructions sont envoyées à un canvas qui crée la représentation graphique.