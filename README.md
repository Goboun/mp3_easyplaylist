# Manuel d'Utilisation

## Groupe 05
- **BENCHOUBANE Sid-Ali**
- **BANDOIS--CERVEAU Henri-Emmanuel**
- **TRINH Gia Tâm**

## Introduction

Cette application permet de :
- Explorer des fichiers musicaux MP3 et FLAC.
- Extraire et modifier leurs métadonnées.
- Ecouter des fichiers audios.
- Créer des playlists au format XSPF, importer ou exporter ces playlists.
- Rechercher des informations sur des albums via une API.

Le programme est utilisable en **mode console (CLI)** ou en **mode graphique (GUI)**.

---

## Installation

### Prérequis
- Python 3 requis ou supérieur.
- Bibliothèques nécessaires (installer avec `pip`):
  ```bash
  pip install tinytag
  pip install playsound
  pip install python-magic
  pip install music-tag
  pip install pygame
  pip install requests
  ```
  
## Utilisation

### Mode Console
Le programme est utilisable en **mode console (CLI)** ou en **mode graphique (GUI)**.
- -f : Permet de spécifier un fichier (MP3 ou FLAC).
- -d : Permet de spécifier un répertoire pour analyser tous ses fichiers musicaux.
- -o : Permet d'indiquer un fichier de sortie pour sauvegarder une playlist au format XSPF.
- -h ou --help : Affiche l'aide avec toutes les options disponibles.
  
### Exemples
```bash
- python3 cli.py -h

- python3 cli.py -f music.mp3

- python3 cli.py -d ./music/

- python3 cli.py -d ./music/ -o playlist.xspf

- python3 cli.py
```
### Mode GUI
```bash
- python3 gui.py
```
