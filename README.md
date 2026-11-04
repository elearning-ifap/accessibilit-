# Tableau de bord — sensibilisation au handicap en emploi

Version du portail : 0.1 · Mise à jour : 4 novembre 2026. Le portail regroupe le prototype HTML v0.7, le cahier des charges v0.2, le storyboard v0.3 et la grille de relecture v0.1.

## Important — confidentialité

**GitHub Pages n'est pas un extranet privé.** Sur les configurations courantes, un site Pages est public, même si le dépôt est privé. Les fichiers placés dans ce dossier (documents, prototype et ressources) deviendront accessibles depuis le site publié. Avant toute mise en ligne, faites valider la diffusion de ces documents de travail par les responsables du projet. Ne publiez aucune donnée personnelle ou sensible. Si l'accès doit être limité à Aurore et Jérôme, choisissez un hébergement avec authentification (SharePoint/Teams, par exemple), ou un dispositif GitHub Enterprise configuré pour des Pages privés si disponible.

## Prévisualisation en local

1. Décompresser l'archive ZIP sur votre ordinateur.
2. Ouvrir `index.html` dans un navigateur récent.
3. Les liens vers le prototype et les documents sont relatifs et fonctionnent depuis le dossier décompressé. Le bouton de copie de lien sera surtout utile une fois le site hébergé.

## Publication sur GitHub Pages (après accord de diffusion)

1. Sur GitHub, créer un nouveau dépôt, par exemple `pilotage-handicap-ifap`.
2. Extraire le ZIP et ajouter **tout son contenu** à la racine du dépôt (pas le dossier conteneur). Conserver `index.html`, `.nojekyll`, `prototype/`, `documents/` et `assets/`.
3. Dans le dépôt, ouvrir **Settings → Pages**.
4. Sous **Build and deployment**, choisir **Deploy from a branch** ; sélectionner `main` et `/(root)`, puis enregistrer.
5. Une fois le déploiement effectué, utiliser l'adresse affichée dans **Pages → Visit site** et la partager avec les personnes autorisées selon la décision de diffusion.
6. Pour actualiser le projet, remplacer les fichiers et modifier la chronologie et les ressources dans `index.html`, puis pousser une nouvelle révision.

Si le dépôt est public, les documents peuvent être indexés ou partagés sans contrôle, malgré la balise `noindex` : celle-ci n'est **pas** un mécanisme de confidentialité.

## Arborescence

- `index.html` — tableau de bord, avec graphiques d'avancement, séquences, profils et accès aux livrables.
- `cahier-des-charges.html` — lecture confortable du CDC original v0.2, avec avertissement sur les arbitrages ultérieurs.
- `prototype/index.html` — **copie exacte** du démonstrateur HTML v0.7, non modifiée.
- `documents/` — storyboard et grille PDF + Word, CDC Markdown.
- `assets/` — petites prévisualisations et favicon.
- `.nojekyll` — publication des fichiers statiques sans traitement Jekyll.

## Mise à jour des statuts et des rôles

Le portail est **statique**, sans serveur ni base de données : les indicateurs correspondent aux jalons connus au 4 novembre 2026, ils ne se mettent pas à jour automatiquement. Les choix de rôle servent à afficher les attentes, **pas** à collecter les avis. Utilisez la grille Word pour adresser les observations à Marc par vos canaux habituels. Aucun questionnaire n'est envoyé par ce site.

## Validation

- Tableau de bord conçu pour une réunion de travail, pas pour des apprenants.
- Storyboard : proposition v0.3, relecture collective le 18 novembre 2026.
- Prototype : démonstrateur v0.7, non SCORM.
- CDC : version 0.2 antérieure aux arbitrages du 4 novembre 2026.
- Points nécessitant vérification avant la diffusion du module : textes juridiques locaux, statistiques, accès aux aides, ressources externes, droits médias, accessibilité et intégration Moodle.
