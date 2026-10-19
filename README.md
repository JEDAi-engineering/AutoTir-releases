# AutoTir — téléchargements

Installeurs d'**AutoTir**, l'éditeur interactif de pneus Magic Formula de [JEDAi](https://www.jedai.fr/).
Ce dépôt ne contient que les fichiers d'installation ; le code source n'y est pas.

## ⬇️ [Télécharger la dernière version](https://github.com/JEDAi-engineering/AutoTir-releases/releases/latest)

| Poste | Fichier |
|---|---|
| Mac Apple silicon (M1 et suivants) | `AutoTir-<version>-arm64.dmg` |
| Mac Intel | `AutoTir-<version>-x64.dmg` |
| Windows 10 / 11 (64 bits) | `AutoTir-Setup-<version>.exe` |

## Installation

- **macOS** : ouvrir le DMG et glisser AutoTir dans Applications. L'app n'est pas notarisée par Apple : au premier lancement, taper `xattr -cr /Applications/AutoTir.app` dans le Terminal, ou aller dans Réglages Système › Confidentialité et sécurité › **Ouvrir quand même** (détail dans `LISEZMOI-macOS.txt`, inclus dans le DMG).
- **Windows** : l'installeur n'est pas signé. Sur l'écran SmartScreen, cliquer **Informations complémentaires** › **Exécuter quand même** (voir `LISEZMOI-Windows.txt` dans chaque release).
- **Licence** : AutoTir demande une licence liée au poste. Au premier lancement, l'app affiche l'identifiant machine à envoyer à JEDAi ([admin@jedai.fr](mailto:admin@jedai.fr)).

## Mises à jour automatiques

À partir de la version 1.2.2, AutoTir vérifie une fois par jour s'il existe une nouvelle version dans ce dépôt. Elle s'installe en un clic (About › Updates), après vérification de la signature JEDAi du fichier (Ed25519, `update-manifest.json`). Une nouvelle version mineure (1.2 → 1.3) demande une nouvelle licence : l'app l'indique au lieu de l'installer.

Chaque release donne le SHA-256 de chaque fichier.

---

© JEDAi. AutoTir est un logiciel sous licence ; la redistribution des fichiers de licence est interdite.
