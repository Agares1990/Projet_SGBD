# 🌳 B-Tree avec interface graphique

Ce projet de cours développé en Java a pour but de simuler un [*B-Tree*](https://fr.wikipedia.org/wiki/Arbre_B) avec assistance d'une interface graphique. Son fonctionnement est assez simpliste et a pour but de travailler les algorithmes de fonctionnement afin d'ajouter plusieurs clés en une seule transaction, mais aussi une clé après l'autre, effacer ou modifier des clés, et enfin sauvegarder ou charger un arbre contenant des clés existantes.

Ayant comme base le [programme de base](https://gitlab.com/fsgbd/b-tree/) fourni par l'enseignant, les fonctionnalités étendues sur l'applications étaient de charger des clés depuis le système de fichiers (par exemple un numéro de sécurité sociale mais aussi des prénoms/noms), ces données étaient représentées dans un fichier sous format CSV pour plus de simplicité. Cette première partie consistait donc à la manipulation des clés ainsi que des index afin de construire une représentation graphique sur l'interface.

Dans un second temps, le programme devait proposer une solution efficace afin d'accélérer le temps de recherche et de stérialisation des arbres afin de pouvoir effectuer des modifications ainsi que des recherches beaucoup plus aisément. Cela devait être réalisé en prenant en compte le temps d'exécution d'une recherche séquentielle classique afin de produire des statistiques de performances.

#### Réalisé par Brahim LAMJARAD, Emre ERSOY, Abdenour ACHOURI, Yannis BAILI et Imane EL MOUNTASSER
