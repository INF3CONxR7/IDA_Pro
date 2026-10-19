# IDA Pro 7.5 — EBOOT.BIN PS3 & PS4

Ce dépôt regroupe des informations sur l'**analyse et la modification de fichiers `EBOOT.BIN`** de jeux **PlayStation 3 et PlayStation 4** avec **IDA Pro 7.5**.

## Utilisation

- Ouvrir et analyser le code d'un `EBOOT.BIN` compatible.
- Rechercher des **fonctions, adresses mémoire et offsets**.
- Étudier le fonctionnement d'un jeu à l'aide du désassemblage.
- Préparer et vérifier des **modifications binaires (patchs)**.

## Prérequis

- **IDA Pro 7.5**, à obtenir séparément auprès de son éditeur.
- Une copie du `EBOOT.BIN` que vous êtes autorisé à analyser.
- Si nécessaire, un outil adapté pour préparer le format du fichier avant son analyse.

## Compatibilité

| Console | Architecture principale |
| --- | --- |
| **PS3** | PowerPC (PPU) |
| **PS4** | x86-64 |

Les méthodes d'analyse et les offsets varient selon la **console, le jeu et sa version**.

## Informations importantes

- Toujours conserver une **sauvegarde du fichier original** avant toute modification.
- Un changement d'extension en `.elf` ne convertit pas automatiquement un `EBOOT.BIN`.
- Une modification incorrecte peut empêcher le jeu de fonctionner.
- Aucun logiciel IDA Pro ni fichier de jeu n'est fourni dans ce dépôt.

**Ce dépôt est indépendant et n'est pas un projet officiel d'IDA Pro ou de ses éditeurs.**
