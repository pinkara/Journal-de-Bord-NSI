# Projet NSI : Journal de Bord - Visite de la Cité des Télécoms

## 1. Description

Ce projet est un site web "one-page" (une seule page) créé dans le cadre d'un projet NSI. Il sert de journal de bord interactif suite à une visite à la Cité des Télécoms à Pleumeur-Bodou.

Le site résume les points clés de la visite, de l'histoire du Radôme aux effets spéciaux du cinéma, en proposant plusieurs modules interactifs pour illustrer les concepts vus sur place.

## 2. Fonctionnalités

Le site est divisé en plusieurs sections accessibles depuis la barre de navigation :

- **Accueil** : Page de présentation du projet.

- **Le Radôme** : Informations clés sur le Radôme et la première mondovision (Telstar).

- **Histoire (Section principale)** :

  - **Simulateur Morse** : Un manipulateur morse réaliste.

    - Retour sonore (bips) généré avec Tone.js.

    - Utilisation de la souris ou de la barre d'espace.

    - Une **bande télégraphique (canvas)** défile en continu de droite à gauche, dessinant les points et les traits en temps réel.

  - **Défi Morse** : Un mini-jeu pour s'entraîner à écrire des mots en morse, avec un retour visuel et des confettis en cas de succès.

  - **Animation Câble** : Visualisation animée (SVG) du tracé du premier câble transatlantique Telstar.

  - **Simulation Fibre Optique** : Un canvas interactif montrant la loi de la réfraction (Snell-Descartes). L'utilisateur peut changer l'angle d'incidence avec un curseur pour voir la réflexion totale (le principe de la fibre).

- **Effets Spéciaux (FX)** :

  - **Simulateur de Fond Vert (Chroma Key)** : Une zone interactive permettant de simuler l'incrustation.

  - **Choix d'acteurs** : L'utilisateur peut faire apparaître un "Dino", un "Bat-Cat" ou un "Dragon" (images SVG).

  - **Personnalisation** : Un sélecteur de couleur permet de changer la couleur de l'acteur.

  - **Drag-and-Drop** : Les acteurs peuvent être saisis et déplacés n'importe où sur l'écran.

  - **Fond personnalisé** : L'utilisateur peut coller l'URL d'une image pour remplacer le fond vert.

- **Quiz** :

Un quiz de 5 questions pour tester les connaissances acquises lors de la visite.

Le score final est affiché avec un message personnalisé.
