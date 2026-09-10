# 01 — Du programme au circuit FHE

Concrete compile un programme manipulant des valeurs chiffrees vers un graphe d operations FHE.
Les types, plages et precisions declarees guident le choix des encodages et parametres.
Une borne incorrecte peut produire erreur, surcout ou comportement hors domaine.
Le compilateur optimise le graphe, mais la fonction metier attendue doit rester explicite.
La revue commence par les plages d entree et les conversions.
Source : [`frontends`](https://github.com/zama-ai/concrete/tree/main/frontends).

[Suite](02-bruit-et-parametres.md)
