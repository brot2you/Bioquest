# BIOQUEST V8 — Foundation Edition

Cette version **reprend intégralement la V7** (20 missions, enquêtes, laboratoire, carnet, maîtrise SVT et correctif d’indices) et fiabilise son moteur.

## Correctifs V8
- Conservation du focus clavier lors du rafraîchissement des boutons d’association et des écrans.
- Une seule zone de retour pour les indices de mission ; retour annoncé aux technologies d’assistance.
- Protection contre les identifiants de mission inconnus et les indices inexistants.
- Import de sauvegarde contrôlé (format, taille, structure des champs) ; confirmation avant remplacement.
- Signalement interne d’échec de stockage ; protection contre les exceptions de stockage.
- Ajustements tactiles et réduction des animations.
- Cache busting `?v=8` pour les ressources.

## Installation GitHub Pages
Décompressez le ZIP, puis copiez **tout son contenu** à la racine du dépôt (et non le dossier englobant). Aucune API ni serveur nécessaire.

## Tests
Les contrôles automatisés de syntaxe, d’archives et de références de fichiers sont possibles localement. Le test interactif sur Safari iPhone et les scénarios de progression doivent encore être validés sur appareils réels.

## Limites
La V8 consolide la V7 : elle ne constitue pas encore la couverture intégrale des programmes de SVT.
