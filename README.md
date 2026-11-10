# bureau-avatars

Ressources 3D d'un tableau de bord privé : des personnages en volume, animés, affichés dans un navigateur avec three.js.

## Contenu

- `avatars/` : maillages au format GLB (squelette inclus, sans texture), convertis depuis la bibliothèque
  [Microsoft Rocketbox](https://github.com/microsoft/Microsoft-Rocketbox).
- `anims/anims.json` : quelques mouvements de la même bibliothèque (attente, marche, course, assis, etc.),
  rééchantillonnés à 15 images par seconde et compactés.
- `equipe/<nom>/` : textures de personnages fictifs (tête, tenue, mèches), en WebP 1024 et 512, dérivées des
  textures de la bibliothèque. Les visages viennent de portraits générés par ordinateur : ce ne sont pas des
  personnes réelles.

## Licence

Les avatars, les animations et les textures d'origine sont l'oeuvre de Microsoft, publiés sous licence MIT
(voir `LICENSE.md`, « Copyright (c) 2020 Microsoft »). Les fichiers de ce dépôt en sont des versions converties ou
retouchées, redistribuées sous la même licence.
