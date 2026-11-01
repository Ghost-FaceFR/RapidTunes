# Sécurité de RapidTunes

## Responsable

Ghost Industry est responsable de la sécurité de RapidTunes, de son installateur et des mises à jour publiées sur https://github.com/Ghost-FaceFR/RapidTunes

## Signaler une faille

Pour signaler une faille de sécurité, utilise le signalement privé de GitHub : onglet Security du dépôt https://github.com/Ghost-FaceFR/RapidTunes, puis « Report a vulnerability ». N'ouvre pas de demande publique pour une faille : elle serait visible de tous avant d'être corrigée.

Indique la version de RapidTunes, ce que tu as constaté, les étapes pour le reproduire et l'effet possible.

## Pendant tes recherches

- N'accède pas aux données d'autres personnes et ne dégrade pas leur ordinateur.
- Ne publie rien avant que la correction soit disponible : laisse le temps de corriger.
- Un signalement ne donne pas droit à une récompense, il n'y a pas de programme de primes.

## Ce que RapidTunes fait pour te protéger

- Les mises à jour ne sont téléchargées que depuis le dépôt officiel de RapidTunes, et leur empreinte SHA-256 est vérifiée avant l'installation.
- yt-dlp, FFmpeg et Deno sont vérifiés par empreinte après leur téléchargement.
- L'interface applique une politique de sécurité de contenu stricte : pas de scripts externes, pas de cadres intégrés.
- Aucune donnée n'est envoyée à l'éditeur, voir Confidentialité et données.

## Failles des composants tiers

Les failles de yt-dlp, FFmpeg, Deno, Microsoft WebView2 ou Windows concernent leurs auteurs : signale-les directement chez eux.
