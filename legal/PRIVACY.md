# Politique de confidentialité et données de RapidTunes

Version 1.0, 1er novembre 2026. Éditeur : Ghost Industry.

## En résumé

RapidTunes fonctionne sans compte. Il ne collecte aucune donnée personnelle pour le compte de l'éditeur, ne contient aucun outil de mesure d'audience ni de publicité, et n'envoie aucune donnée de ta bibliothèque ou de ton usage à l'éditeur.

## Données gardées sur ton ordinateur

Ces données restent sur ton ordinateur et ne sont jamais envoyées à l'éditeur.

- Réglages de l'application, thème, raccourcis, playlists, médias récents et dernier volume : stockés dans les données du moteur d'affichage de l'application, dossier `%LOCALAPPDATA%\com.rapidtunes.app`.
- Cache d'affichage : liste de ta bibliothèque, pochettes et vignettes, journal des modifications. Il accélère le démarrage et peut être supprimé sans risque.
- Journaux : dossier `%LOCALAPPDATA%\RapidTunes\logs` (journal général, journal de diagnostic, rapport de plantage). Ils contiennent des messages techniques, des chemins de dossiers et le résultat des analyses de la bibliothèque. Ils ne sont jamais envoyés automatiquement.
- Configuration et préférences système : `%LOCALAPPDATA%\RapidTunes` (accélération matérielle, dernière icône de fenêtre).
- Outils téléchargés : dossier `%LOCALAPPDATA%\RapidTunes\tools` (yt-dlp, FFmpeg, Deno).
- Historique des téléchargements, dossiers de destination et file d'attente.

Le suivi des performances de 30 secondes mesure l'utilisation du processeur et de la mémoire de RapidTunes et la fluidité de l'interface. Le résultat est écrit dans le journal de diagnostic, sur ton ordinateur. Il n'est partagé que si tu l'envoies toi-même.

## Connexions réseau

RapidTunes se connecte à Internet seulement dans les cas suivants.

- GitHub (api.github.com et github.com) : recherche de mises à jour, journal des modifications, téléchargement du programme d'installation d'une mise à jour, et téléchargement de yt-dlp, FFmpeg et Deno. GitHub reçoit les informations techniques d'une connexion web classique, comme ton adresse IP, et applique sa propre politique de confidentialité.
- YouTube et les sites que tu indiques (par yt-dlp) : quand tu colles un lien, fais une recherche, lis un aperçu ou lances un téléchargement, la demande part de ton ordinateur vers le site concerné, qui applique sa propre politique. Les miniatures des résultats sont chargées depuis i.ytimg.com.
- Microsoft WebView2 : le moteur d'affichage est un composant Microsoft, avec ses propres règles de données.

Il n'y a aucune autre connexion. Le programme d'installation d'une mise à jour est vérifié par son empreinte SHA-256 avant d'être lancé.

## Ce que l'éditeur ne fait pas

- Pas de compte, pas d'identifiant publicitaire, pas de profilage.
- Pas de transmission de ta bibliothèque, de tes lectures ou de tes téléchargements.
- Pas de vente ni de partage de données, puisqu'aucune n'est collectée.

## Supprimer tes données

- Désinstaller RapidTunes avec l'option « Supprimer aussi mes paramètres et autres données » efface les réglages, les playlists, l'historique, les journaux et le cache.
- Tu peux aussi supprimer à la main les dossiers `%LOCALAPPDATA%\RapidTunes` et `%LOCALAPPDATA%\com.rapidtunes.app`.
- Dans Paramètres, Système, Avancés, Diagnostic, le bouton « Ouvrir le dossier des journaux » donne accès aux journaux.

## Tes droits

L'éditeur ne détenant aucune donnée te concernant, il n'a rien à te communiquer, rectifier ou effacer. Pour toute question sur cette politique, ouvre une demande : https://github.com/Ghost-FaceFR/RapidTunes/issues

## Fonctions à venir : compte et abonnement premium

Une méthode de connexion et un abonnement premium sont prévus pour une version future. Ils ne sont pas disponibles aujourd'hui, et tout ce qui précède décrit la version actuelle, qui n'a ni compte ni paiement. Avant leur ouverture, cette politique sera complétée pour indiquer précisément les données concernées (identifiant de connexion, adresse électronique, état de l'abonnement), leur finalité, leur durée de conservation, les prestataires impliqués (connexion, paiement) et la façon d'exercer tes droits d'accès, de rectification, d'effacement et d'opposition. Une nouvelle information te sera présentée dans l'application avant toute collecte.

## Modifications

Cette politique peut évoluer avec l'application. La version en vigueur est celle qui accompagne la version de RapidTunes installée.
