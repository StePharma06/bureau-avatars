# bureau-avatars

Ressources 3D d'un tableau de bord privé : des personnages en volume, animés, et un décor de bureaux, affichés dans
un navigateur avec three.js.

## Contenu

- `avatars/` : maillages au format GLB (squelette inclus, sans texture), convertis depuis la bibliothèque
  [Microsoft Rocketbox](https://github.com/microsoft/Microsoft-Rocketbox).
- `anims/anims.json` : quelques mouvements de la même bibliothèque (attente, marche, course, assis, etc.),
  rééchantillonnés à 15 images par seconde et compactés.
- `equipe/<nom>/` : textures de personnages fictifs (tête, tenue, mèches), en WebP 1024 et 512, dérivées des
  textures de la bibliothèque. Les visages viennent de portraits générés par ordinateur : ce ne sont pas des
  personnes réelles.
- `figurants/<avatar>/` : textures d'origine de quatre avatars de la bibliothèque (passants à vélo, à moto et en
  scooter), en WebP 512.
- `decor/textures/` : parquet, bois, terrasse, herbe, bitume, écorce et touffe de feuilles (avec transparence), en
  WebP, étalonnés ou composés depuis des textures de [Poly Haven](https://polyhaven.com).
- `decor/modeles/` : plantes en pot, bac en bois, fauteuil de salon, table basse et suspension industrielle (GLB
  allégés et leurs textures), depuis des modèles de Poly Haven.

## Licences

- Avatars, animations et textures de personnages : oeuvre de Microsoft, licence MIT (voir `LICENSE.md`,
  « Copyright (c) 2020 Microsoft »). Les fichiers de ce dépôt en sont des versions converties ou retouchées,
  redistribuées sous la même licence.
- Textures et modèles du décor : Poly Haven, domaine public (CC0). Versions converties et allégées, elles aussi
  placées dans le domaine public (CC0).
