# Patterns d'écriture — Apprentissage automatique

Ce fichier est mis à jour automatiquement par la commande `/check-comment`
pour tracer les erreurs récurrentes et les préférences de style d'Ekko.

---

## Erreurs récurrentes identifiées

### 1. Tirets longs (—)
- **Fréquence** : 7 occurrences (2026-05-12)
- **Problème** : Les tirets longs donnent un style IA/académique lourd
- **Exemples problématiques** :
  - « Ce paradoxe — plus de temps disponible — suggère que... »
  - « L'audioguide — contrairement à ce qu'on pourrait penser — permet... »
- **Correction type** :
  - Utiliser deux points : « Ce paradoxe suggère une chose : ... »
  - Utiliser des parenthèses : « Ce paradoxe (plus de temps disponible) suggère... »
  - Couper en deux phrases : « Ce paradoxe existe. Plus de temps disponible... »
- **Date d'identification** : 2026-05-12

### 2. Formulations "style IA"
- **Fréquence** : 6 occurrences (2026-05-12)
- **Problème** : Texte qui sonne artificiel, trop lisse, pas incarné
- **Marqueurs typiques** :
  - « Il convient de souligner que... »
  - « Force est de constater que... »
  - « Ces formulations renvoient à un mécanisme documenté... »
  - « Ce paradoxe rejoint les observations de... »
  - Phrases très symétriques (« d'une part... d'autre part... »)
  - Usage excessif de connecteurs logiques ("ainsi", "en outre", "par conséquent")
- **Correction type** : Reformuler de manière directe, comme Ekko parlerait
- **Exemple** :
  - IA : « Ces observations suggèrent que les problèmes de conception ne sont pas les seuls en cause. »
  - Ekko : « Mais les problèmes de conception n'expliquent pas tout. »
- **Date d'identification** : 2026-05-12

### 3. Vocabulaire trop recherché
- **Fréquence** : 3 occurrences (2026-05-12)
- **Problème** : Mots compliqués là où un mot simple suffirait
- **Exemples** :
  - « corrobore » → « confirme »
  - « La littérature » → « Les études » ou « Les recherches »
  - « prégnant » → « présent » ou « marqué »
- **Date d'identification** : 2026-05-12

### 4. Phrases trop longues
- **Fréquence** : 2 occurrences (2026-05-12)
- **Problème** : Phrases de 3+ propositions difficiles à suivre
- **Règle** : Maximum 2-3 propositions par phrase. Si plus, couper.
- **Date d'identification** : 2026-05-12

### 5. Références annexes manquantes
- **Fréquence** : 5 occurrences (2026-05-12)
- **Problème** : Oubli de mentionner que le détail est en annexe
- **Contextes typiques** :
  - Protocoles d'entretien
  - Questionnaires complets
  - Tableaux d'analyse de corpus
- **Formulation type** : « (voir Annexe X pour le détail) » ou « Le protocole complet est disponible en Annexe X. »
- **Date d'identification** : 2026-05-12

---

## Préférences de style confirmées

### Voix d'Ekko
- **"Je"** assumé, pas de "nous" de majesté
- Formulations directes, engagées
- Capacité à affirmer une position personnelle
- Pas peur de la première personne dans un texte académique

### Références stylistiques (extraits du M1)
> « On pourrait penser que le problème vient de la technologie. Mais il semble
> plus juste de dire qu'il s'agit d'un problème d'usage, d'expérience, et plus
> encore de posture. »

> « En somme, ce qui fait la force de l'audioguide, c'est sa manière d'accompagner
> sans s'imposer. »

### À éviter absolument
- Tirets longs (—)
- « Il convient de... »
- « Force est de constater... »
- « On ne saurait... »
- Connecteurs lourds en série (« ainsi, de surcroît, en outre »)
- Symétrie artificielle (« d'une part... d'autre part... »)

---

## Historique des corrections

| Date | Fichier | Pattern | Correction appliquée |
|------|---------|---------|---------------------|
| 2026-05-12 | — | Initialisation | Fichier créé avec patterns de base |
| 2026-05-12 | 02-prob-hyp-methode.md | Vocabulaire | "La littérature" → "Les recherches" |
| 2026-05-12 | 02-prob-hyp-methode.md | Style IA | "livre un message cohérent" → "disent la même chose" |
| 2026-05-12 | 02-prob-hyp-methode.md | Phrase longue | Phrase Jarrier découpée en 3 |
| 2026-05-12 | 02-prob-hyp-methode.md | Tiret | "condition de possibilité —" reformulé |
| 2026-05-12 | 02-prob-hyp-methode.md | Annexes | 4 mentions annexes ajoutées |
| 2026-05-12 | 02-prob-hyp-methode.md | Style IA | "Je retiens ces entretiens..." reformulé |
| 2026-05-12 | 03-partie-I.md | Tirets | 5 tirets (—) remplacés par parenthèses ou coupures |
| 2026-05-12 | 03-partie-I.md | Vocabulaire | "corrobore" → "confirme" |
| 2026-05-12 | 03-partie-I.md | Traduction | "returning users" → ajout explication |
| 2026-05-12 | 03-partie-I.md | Rappels | "Le deuxième/troisième constat" → ajout origine |
| 2026-05-12 | 03-partie-I.md | Style IA | Paragraphe Bensaude-Vincent reformulé |
| 2026-05-12 | 03-partie-I.md | Style IA | "Ce paradoxe de la non-linéarité" reformulé |
| 2026-05-12 | 03-partie-I.md | SDK | Explication ajoutée |
| 2026-05-12 | 03-partie-I.md | Sens visuel | Passage reformulé proprement |
| 2026-05-13 | 02-prob-hyp-methode.md | Clarification | "Ben Nasr précise ce tableau" supprimé |
| 2026-05-13 | 02-prob-hyp-methode.md | Nuance | Littérature + biais études privées ajoutés |
| 2026-05-13 | 02-prob-hyp-methode.md | Données | Chiffre 2021 (530 apps) ajouté |
| 2026-05-13 | 02-prob-hyp-methode.md | Raccourcir | Passage H1-H5 condensé |
| 2026-05-13 | 03-partie-I.md | Style | Perception positive téléphone renforcée |
| 2026-05-13 | 03-partie-I.md | Déplacement | Verbatim batterie → section technique |
| 2026-05-13 | 03-partie-I.md | Clarification | Paragraphe 14 min réécrit |
| 2026-05-13 | 03-partie-I.md | Annexe | Mention tableau corpus ajoutée |
| 2026-05-13 | 03-partie-I.md | Fond | Plafond de verre + sources GECE/CREDOC |

---

## Notes pour amélioration continue

*Section mise à jour automatiquement lors des sessions `/check-comment`*

- Les patterns ci-dessus sont issus de l'analyse des 42 commentaires actuels
- Prochaine révision prévue : après traitement des commentaires en cours
