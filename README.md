# Card Game

Ce jeu de cartes a été réalisé dans le cadre du projet : "".

L'objectif de ce projet était de développer une plateforme présentant différents concepts du langage Javascript à des utilisateurs débutants en programmation web. Pour illustrer ces concepts et expliquer comment ils peuvent être mis en pratique, nous avons créé un jeu de cartes. Ce jeu a ensuite été divisé en modules, chaque module présentant une notion différente du langage Javascript pour aider l'utilisateur à comprendre comment ces notions peuvent être appliquées.

## Règle du jeu

Une partie de blackjack se joue entre le croupier et un certain nombre de joueurs. L’objectif de chaque joueur est de battre le croupier, ces derniers ne s’affrontent pas entre eux. C’est pour cela qu’il n’est pas dérangeant que chacun des joueurs voie les cartes de ses adversaires. Les joueurs doivent obtenir un score supérieur à celui du croupier tout en ne dépassant pas 21 : il faut donc s’approcher le plus possible de 21 sans dépasser cette valeur. 

Nous avons structuré le jeu en manches. À chaque début de manche, le croupier reçoit une carte face visible et une autre face cachée. Ensuite les joueurs constituent leur set de cartes l’un après l’autre : ils reçoivent d’abord deux cartes piochées de manière aléatoire, ensuite ils ont la possibilité de piocher d’autres cartes ou de simplement passer leur tour. Ils ont 10 secondes pour réaliser leur choix, le compteur se relance lorsque le joueur choisit de piocher, il est clairement visible en haut de la page. 

Chaque carte apporte un certain nombre de points correspondant à sa valeur, par exemple :  l’as donne 1 point, le 3 de pique apporte 3 points, le 8 de trèfle et le 8 de cœur donnent 8 points, enfin les valets, reine et roi apportent 10 points chacun. 

Afin de retirer le système de pari d’argent du Blackjack, nous avons mis en place un système de vie pour les joueurs. Tous les joueurs commencent avec un certain nombre de vies personnalisable.  

À l’issue d’une manche, un joueur perd une vie si son score est inférieur au croupier ou si son score est supérieur à 21. La partie se termine lorsqu’il ne reste qu’un seul joueur en vie, il peut donc ne pas y avoir de gagnant si tous les joueurs perdent en même temps. 

## Overview
