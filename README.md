![separe](https://github.com/studoo-app/.github/blob/main/profile/studoo-banner-logo.png)
# Cyber forensic
[![Version](https://img.shields.io/badge/Version-1.0.0-blue)]()

## Description
Projet proposant une initiation aux méthodes de Digital Forensic (techniques numériques d'enquêtes).
Ces techniques ont pour but d'enquêter sur des crimes et établir des faits.
## Installation
### Démarrage du conteneur
`docker compose up -d`
### Connexion à la console
`docker exec -it investigation-toolbox /bin/bash`
### Lancement du script d'installation des outils
- Se positionner dans le dossier `/home/scripts`
- Autoriser l'éxécution du script `install-tools.sh`
    ```bash
        chmod +x install-tools.sh
    ```
- Executer le script `install-tools.sh`
    ```bash
        ./install-tools.sh
    ```

> ##### Attention
> Si vous ne parvenez pas a éxéuter le script d'installation, vous devez passez à l'installation manuelle des outils.
> Pour ce faire, éxécuter les commandes situées dans le fichier `/scripts/install-tools.sh`.

## Mise en situation
### Contexte et mission
Vous êtes technicien de la police scientifique, section cybercriminatilité. Vous êtes solicité dans le cadre d’une
affaire d’enlèvement.
Votre mission consiste  à extraire le maximum d’info des pièces informatiques fournies et de fournir un rapport détaillé de 
vos conclusions aux enquêteurs.

## Pièces fournies
### Documents numériques
- une copie certifiée conforme du la demande de rançon
- Une extraction de l'image insérée dans la demande de rançon
### Informations administratives des suspects potentiels

> ##### Manon Dubois
> - Adresse connue : 44 avenue Victor Hugo 75016 Paris
> - Travaille en tant que consultant informatique pour une ESN parisienne

> ##### Alexandre Leroux
> - Adresse connue : 5 rue saint marc 75002 Paris
> - Connu sur les plateformes de jeux en ligne sous le pseudo de POWNED-234

> ##### Elise Lefevre
> - Adresse connue : 14 rue vaugirard 75006 PARIS
> - Connue des services de polices pour traffic de stupéfiants

> ##### Maxime Dupont
> - Adresse connue : 51 Rue du Couëdic 75014 Paris
> - Aucune activité numérique notable connue

