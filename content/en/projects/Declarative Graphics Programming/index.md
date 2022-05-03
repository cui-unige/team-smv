---
title: "Declarative Graphics Programming"
weight: 2
resources:
    - src: schema-patl.png
      params:
          weight: -100
---

Master thesis  
Author: Patrick Sardinha  
Language: French  
Document available [here](/team-smv/projects/Patrick_s_master_thesis.pdf)

## Abstract

La programmation graphique permet de créer des applications 3D et est notamment utilisée pour la conception de jeux vidéo ainsi que pour la modélisation. A l'heure actuelle, la spécification OpenGL est l'une des plus utilisées pour la création d'applications graphiques et offre un ensemble de fonctions donnant la possibilité aux programmeurs de déclarer et de manipuler des objets 3D ainsi que des images. Cependant, l'utilisation d'une telle spécification demande de coder à relativement bas niveau et de bonnes connaissances dans la programmation graphique. Il est de ce fait assez compliqué de concevoir ce type d'applications. L'utilisation d'un langage de programmation haut niveau incluant des abstractions sur les types est un moyen de faciliter la conception de ces dernières.  Le but de ce travail est de créer un nouveau langage nommé PATL, ayant pour but d'être complètement déclaratif, de proposer une implémentation par blocs et de permettre l'utilisation d'abstractions pour la création des applications et la représentation des objets 3D. Il s'agit d'un \textit{Domain-Specific Language} (DSL) orienté Swift inspiré d'un langage déclaratif: React. Ce nouveau langage de programmation a pour but de permettre la création et l'utilisation de types abstraits et d'ajouter une couche déclarative à Rendery, un moteur de rendu 2D/3D moderne qui est écrit en Swift et basé sur OpenGL. L'utilisation de PATL avec Rendery vise à ne pas avoir à manipuler les fonctions OpenGL et ainsi de créer des applications graphiques de manière simplifiée tout en utilisant le langage Swift.
