<div align="center">

<img src="logo.png" alt="RapidTunes" width="128" />

# RapidTunes

**Lecteur média et téléchargeur audio/vidéo pour Windows.**

![Plateforme](https://img.shields.io/badge/Windows-10%2F11-0078D6?logo=windows&logoColor=white)
![Version](https://img.shields.io/github/v/release/Ghost-FaceFR/RapidTunes?color=6C5CE7&label=version)

[**Télécharger la dernière version**](https://github.com/Ghost-FaceFR/RapidTunes/releases/latest) · [Journal des modifications](CHANGELOG.md)

</div>

---

## Présentation

RapidTunes réunit deux outils dans une seule application :

- **Lecteur média** : bibliothèque locale, playlists, file de lecture, mini lecteur, égaliseur, lecture plein écran.
- **Media DL** : téléchargement et conversion de médias depuis un lien ou une recherche, avec file d'attente et historique.

## Fonctionnalités

### Media DL
- Téléchargement audio/vidéo depuis un lien ou une recherche (vidéo ou playlist)
- Formats MP3, MP4, WAV, FLAC, AAC, en plusieurs qualités
- File d'attente, pause / reprise, annulation, limitation de débit
- Vitesse en temps réel, progression et temps restant, historique des téléchargements

### Lecteur média
- Bibliothèque locale (dossiers, fichiers), playlists, file de lecture, lecture aléatoire, vitesse de lecture
- Édition des tags, pochettes et propriétés des médias
- Mini lecteur avec visualisation, option « Toujours au premier plan », lecture plein écran
- Égaliseur avec de nombreux préréglages
- Visualisations audio qui réagissent à la musique

### Application
- Thèmes de couleurs, interface en français, fenêtre sans bordure
- Mises à jour intégrées : téléchargement et installation en un clic

## Installation

1. Télécharge le fichier `RapidTunes_<version>_x64-setup.exe` depuis la page [**Releases**](https://github.com/Ghost-FaceFR/RapidTunes/releases/latest).
2. Lance-le et suis les étapes : options d'installation, raccourcis, progression.
3. Au premier lancement, RapidTunes installe seul les composants dont il a besoin (yt-dlp, ffmpeg, deno).

Si RapidTunes est déjà installé, l'installateur propose de mettre à jour, réparer ou désinstaller.

> Windows peut afficher un avertissement « éditeur inconnu » au lancement : l'installateur n'est pas encore signé numériquement. Tu peux vérifier l'empreinte SHA-256 du fichier affichée sur la page de la release.

## Versions

| Version | Notes |
| --- | --- |
| [1.2.0](https://github.com/Ghost-FaceFR/RapidTunes/releases/tag/v1.2.0) | Nouvel installateur, mini lecteur, visualisations |
| [1.1.0](https://github.com/Ghost-FaceFR/RapidTunes/releases/tag/v1.1.0) | Nouveau logo, repli automatique si le dossier est protégé |
| [1.0.2](https://github.com/Ghost-FaceFR/RapidTunes/releases/tag/v1.0.2) | Correctifs du dossier de destination |
| [1.0.1](https://github.com/Ghost-FaceFR/RapidTunes/releases/tag/v1.0.1) | Correctifs de démarrage |
| [1.0.0](https://github.com/Ghost-FaceFR/RapidTunes/releases/tag/v1.0.0) | Première version |

## Licence

RapidTunes est un logiciel propriétaire, **non open source**. Ce dépôt ne contient que l'installateur et les notes de version : le code source n'est pas public. Voir [LICENSE](LICENSE).

© 2026 **Ghost Industry**. Tous droits réservés.
