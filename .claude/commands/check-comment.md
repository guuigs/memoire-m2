Vérification et traitement des commentaires Side Note d'Ekko.

## Workflow

1. **Lire les commentaires actifs**
   Lis le fichier `.obsidian/plugins/side-note/data.json` pour récupérer
   tous les commentaires non résolus (`resolved: false` ou absent).

2. **Lire le fichier des patterns appris**
   Lis `07-meta/patterns-ecriture.md` pour connaître les erreurs récurrentes
   déjà identifiées et les préférences de style d'Ekko.

3. **Trier les commentaires par fichier**
   Regroupe les commentaires par `filePath` pour traiter fichier par fichier.

4. **Pour chaque commentaire, identifier le type** :
   - **"tirets" / "—"** : Ekko n'aime pas les tirets longs. Proposer une
     reformulation sans tirets (parenthèses, deux points, nouvelle phrase).
   - **"trop IA" / "style IA" / "formulation IA"** : Le texte sonne artificiel.
     Proposer une version plus directe, incarnée, dans la voix d'Ekko.
   - **"plus simple" / "autre mot"** : Simplifier le vocabulaire académique.
   - **"phrase trop longue"** : Découper en phrases plus courtes.
   - **"dispo en annexe" / "annexe"** : Ajouter une mention des annexes.
   - **"pas compris" / "pas clair"** : Clarifier le passage concerné.
   - **Question ouverte** : Engager une discussion avec Ekko.

5. **Traiter les commentaires**
   - Lis le fichier source concerné (`filePath`)
   - Localise le passage (`selectedText`)
   - Propose une correction adaptée au type de commentaire
   - Demande validation à Ekko avant d'appliquer

6. **Après validation**
   - Applique la correction via l'outil Edit
   - Mets à jour `07-meta/patterns-ecriture.md` si c'est une erreur récurrente
   - Marque le commentaire comme résolu dans `.obsidian/plugins/side-note/data.json`
     en ajoutant `"resolved": true` et `"resolvedAt": <timestamp>` au commentaire
   - Ekko devra recharger Obsidian (Ctrl+R) pour voir les commentaires disparaître

7. **Apprentissage**
   Si tu détectes un nouveau pattern récurrent (3+ occurrences du même type
   de commentaire), ajoute-le dans `07-meta/patterns-ecriture.md` avec :
   - Description du pattern
   - Exemples de texte problématique
   - Correction type
   - Date d'identification

## Règles de style d'Ekko (référence rapide)

Voir `07-meta/patterns-ecriture.md` pour la liste complète. Règles de base :
- Pas de tirets longs (—) → utiliser deux points, parenthèses, ou nouvelles phrases
- Pas de formules creuses ("il convient de", "force est de constater")
- Voix directe, engagée, qui assume un "je"
- Préférer les mots simples aux synonymes recherchés
- Phrases courtes, pas plus de 2-3 propositions

## Statistiques de session

À la fin du traitement, affiche :
- Nombre de commentaires traités
- Patterns les plus fréquents
- Suggestions d'amélioration globale si pertinent
