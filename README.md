# SamplePlugin

SamplePlugin est un exemple minimal de plugin Spigot pour Minecraft.
Il vise à servir de base de départ pour développer vos propres extensions.

## Fonctionnement
- Enregistrement d'un listener `SamplePluginEvents` au démarrage.
- Affichage dans la console d'un message à l'activation et à la désactivation du plugin.

## Fichiers de configuration
### plugin.yml
- `name` (string) – Nom du plugin utilisé par Spigot.
- `author` (string) – Auteur du projet.
- `version` (string) – Version actuelle du plugin.
- `main` (string) – Classe principale chargée par Spigot.
- `api-version` (string) – Version de l'API cible.

## Compilation / Installation
Le projet utilise **Maven**. Pour compiler le plugin :
```bash
mvn package
```
Le fichier JAR généré se trouve dans le dossier `target/`. Copiez-le dans le dossier `plugins/` de votre serveur Spigot.

## Fichiers importants
- `SamplePlugin.java` – Classe principale du plugin.
- `SamplePluginEvents.java` – Gère les événements (actuellement vide).
- `plugin.yml` – Déclaration du plugin pour Spigot.

## Utilisation rapide
1. Compilez le projet avec Maven.
2. Placez le JAR obtenu dans `plugins/`.
3. Lancez votre serveur Spigot : le message « Plugin ON! » doit apparaître dans la console.

## Licence et contributions
Aucune licence ou guide de contribution n'a été fourni dans ce dépôt.
