# One-Life (Prototype)

**One-Life** est un prototype de jeu solo développé en C# avec MonoGame.
Il s’agit d’un projet exploratoire démontrant une architecture modulaire, des systèmes de zones et la gestion avancée de scènes et d’UI.

---

## Concept

- Le joueur contrôle un personnage qui peut se déplacer dans une maison (3 pièces) et un village.
- Lorsqu’il est dans une pièce, les autres pièces sont masquées, sans chargement.
- Menu principal, écran des options et des crédits inclus.
- Intro et transitions fluides entre les zones.

---

## Technologies

- Langage : C#
- Framework : MonoGame
- Architecture : multi-projets, patterns (Singleton, Factory, ServiceLocator, Managers)
- Contrôle version : Git / GitHub

---

## Organisation du projet

- `Core` : logique principale du jeu
- `CoreScenes` : gestion des scènes (menus, gameplay, UI)
- `UIScenes` : interfaces et menus interactifs
- `World` : définition du monde (maisons, village, zones)
- `ZoneSystems` : gestion des zones et transitions entre elles
- `Tower` : fonctionnalités spécifiques du prototype (éventuellement modules futurs)

---

## Points techniques

- Multi-projets séparés pour modularité et maintenabilité
- Patterns : Singleton, Factory, ServiceLocator
- Managers personnalisés pour polices, textures, scènes, UI
- Chargement dynamique et masquage des zones pour fluidité

---

## Licence & Contact

- Auteur : Dominique Lacombe
- Portfolio : https://www.lacombedominique.com/
- LinkedIn : https://www.linkedin.com/in/lacombe-dominique/
