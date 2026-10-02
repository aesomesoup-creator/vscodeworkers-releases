# VSCodeWorkers

**Garde un œil sur tes agents.** VSCodeWorkers donne un petit personnage à chacune de tes
discussions Claude Code. Sur Mac, ils se rangent autour de l'encoche ; sous Windows, dans une
barre au bord de l'écran. D'un coup d'œil, tu sais laquelle a fini, et laquelle t'attend.

Le film de présentation et chaque fonction, étape par étape :
**[vscodeworkers.aesomesoup.com](https://vscodeworkers.aesomesoup.com)**

## Télécharger

Gratuit. Il te faut VS Code et Claude Code.

| | |
| --- | --- |
| **macOS** | [VSCodeWorkers-mac.dmg](https://github.com/aesomesoup-creator/vscodeworkers-releases/releases/latest/download/VSCodeWorkers-mac.dmg) : puce Apple et Intel |
| **Windows** | [VSCodeWorkers-windows.exe](https://github.com/aesomesoup-creator/vscodeworkers-releases/releases/latest/download/VSCodeWorkers-windows.exe) : 64 bits |

Ces deux liens mènent toujours à la dernière version. Les précédentes sont dans les
[Releases](https://github.com/aesomesoup-creator/vscodeworkers-releases/releases).

## Installer

1. **Installe.** Sur Mac, ouvre le fichier `.dmg` et glisse VSCodeWorkers dans Applications. Sous
   Windows, lance l'installateur.
2. **Lance l'app.** Elle installe ses hooks toute seule. Sur Mac, autorise l'Accessibilité quand
   elle le demande : c'est ce qui lui permet de retrouver tes fenêtres VS Code.
3. **Ouvre une discussion Claude Code.** Sa bulle apparaît. Celles qui étaient déjà ouvertes la
   rejoignent une fois redémarrées.

## Première ouverture : ton système demande confirmation

**macOS.** L'app n'est pas encore notarisée par Apple : macOS la bloque au premier lancement.
Ouvre Réglages Système, puis Confidentialité et sécurité, et clique « Ouvrir quand même ». Sur un
macOS plus ancien : clic droit sur l'app, puis Ouvrir. Si macOS la dit « endommagée », lance dans
le Terminal :

```bash
xattr -cr /Applications/VSCodeWorkers.app
```

**Windows.** L'installateur n'est pas encore signé : Windows affiche « Windows a protégé votre
ordinateur ». Clique « Informations complémentaires », puis « Exécuter quand même ».

## Ce dépôt

Il ne contient que le site (dossier `docs/`) et, dans ses Releases, les fichiers d'installation.
Le code de l'app n'y est pas publié.

Créé par [@aesomesoup](https://www.instagram.com/aesomesoup/). Projet indépendant, sans lien avec
Anthropic, Microsoft ni Apple.
