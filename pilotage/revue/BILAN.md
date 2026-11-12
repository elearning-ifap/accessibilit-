# Bilan de revue du prototype

12 novembre 2026. Priorité engagement et interface. Trois lectures spécialisées et une passe de corrections. Temps total non chronométré, aucune durée précise annoncée.

| Section | Avant | Après | Charge cognitive estimée | Contrôle |
|---|---|---|---|---|
| Quiz | Révélation au premier clic | Choix modifiable puis validation explicite | Faible, une action supplémentaire explicitée | Test Chrome : choix B puis A, validation A |
| Reprise | Pas de distinction sélection/validation | Sauvegarde de ces deux états | Faible | Actualisation avant validation, choix conservé |
| Relance quiz | Ancienne complétion pouvait être restaurée | Réinitialisation immédiatement mémorisée | Faible | Recommencer puis actualiser, question 1 vierge |
| Accès rapide | Titre masqué ciblé | Question visible ciblée | Faible | Cible et focus observés dans navigateur |
| Navigation | Menu latéral fixe et trois bandeaux | Menu replié, barre compacte, bandeau redondant masqué | Estimation faible, effet à mesurer | État replié observé au chargement |
| Évaluation finale | Continuer permettait de sauter les cas | Commande générale masquée pendant les cas | Moyenne, préservée | Absence de Continuer sur cas 1 observée |
| Consigne 02.5 | Que pouvez-vous conclure ? | Que pouvez-vous leur proposer ? | Estimation faible | Cohérence consigne/options relue |
| Sources et contrôles | Cinq questions avec explications | Conservées, sources après réponse | Moyenne | Cinq questions parcourues |

## Justification et limites
Les instructions explicites et les libellés correspondent aux recommandations W3C WAI (https://www.w3.org/WAI/tutorials/forms/instructions/). Les recherches sur la pratique de récupération justifient de préserver les réponses actives et leurs retours (https://doi.org/10.1007/s10648-021-09595-9). Elles ne prouvent pas un gain pour ce prototype. Aucune donnée apprenant disponible, aucune conformité WCAG globale revendiquée.

## Points signalés ou différés
- Tester mobile, zoom 200 %, clavier de bout en bout et lecteurs d’écran.
- Vérifier la matrice source exacte, la fiche réflexe PDF et la vidéo proposée.
- Quelques distracteurs restent trop évidents et demandent une validation pédagogique.
- Les autres activités qui reconstruisent leur contenu doivent encore faire l’objet d’un contrôle complet du focus.
- Trois maquettes restent soumises aux collègues. Aucun choix fait à leur place.
- Collecte des avis encore manuelle.

## Décision proposée
Itérer après relecture par les collègues et premiers essais apprenants. Le prototype est une version de relecture, sa préparation à la production n’est pas démontrée.

## WHY THIS COULD STILL BORE THE LEARNER
Cinq estimations numériques successives peuvent devenir répétitives. Des réponses manifestement inadaptées permettent parfois de deviner le bon choix sans analyser la situation. Observer ces points auprès des apprenants avant de modifier les contrôles.
