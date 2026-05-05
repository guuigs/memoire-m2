# Réflexion critique sur la méthode de travail de l'IA — Session 6

*Produit le 2026-05-04 après rédaction des Parties I et II*

---

## 1. Ce qui fonctionne bien

### 1.1. Recherche bibliographique autonome et ciblée

**Constat** : Le workflow de recherche bibliographique mis en place en session 6 (lancement du subagent `chercheur-sources`, identification ciblée de sources sur 3 axes, téléchargement des sources open access, production de fiches avant rédaction) a très bien fonctionné.

**Pourquoi ça marche** :
- Détection des besoins **pendant** la planification de la rédaction, pas après
- Sources cherchées pour documenter des mécanismes précis (attention, adoption, tracking)
- Vérification systématique de l'existence (DOI, HAL, bases ouvertes) avant téléchargement
- Fiches produites immédiatement = sources exploitables dans la rédaction

**Preuve d'efficacité** : Les 5 sources téléchargées (fiches 24-28) ont toutes été mobilisées dans I.1, avec des citations précises et des renvois aux pages. Aucune source inventée, aucune hallucination.

### 1.2. Préservation de la voix d'Ekko

**Constat** : Les Parties I et II maintiennent une voix incarnée, directe, avec des formules personnelles et un "je" assumé. Pas de glissement vers un style académique générique.

**Preuves** :
- Formules incarnées : "on a entre les mains un outil plein de potentiel", "reste à savoir si"
- Jugements assumés : "cette stratégie a fonctionné, mais elle a un prix"
- Conclusions engagées : "tant que ces contraintes resteront structurantes, l'audioguide restera marginal"

**Pourquoi ça marche** :
- Lecture attentive des extraits de référence du M1 (fournis dans CLAUDE.md)
- Choix délibéré de formulations actives, pas passives
- Évitement du jargon inutile ("il convient de souligner que" → "plusieurs constats s'imposent")

### 1.3. Articulation matériau empirique / sources académiques

**Constat** : Les Parties I et II croisent systématiquement les données empiriques (questionnaire, entretiens, corpus) avec des sources académiques, sans subordonner l'un à l'autre.

**Exemples** :
- I.1 : verbatims du questionnaire ("j'ai peur d'être distrait") + Skowronek 2023 (charge cognitive extrinsèque)
- I.2 : analyse du corpus (ton neutre, 4/5 audioguides) + Marques & Costello 2017 (14 min = plafond)
- II.2 : verbatim Pauline ("stratégique") + analyse du corpus (absence de scénarisation)

**Pourquoi ça marche** :
- Les sources académiques documentent des **mécanismes** (Cognitive Load Theory, friction temporelle)
- Le matériau empirique illustre ces mécanismes dans des **cas concrets**
- Pas de hiérarchie "théorie → terrain" : dialogue constant entre les deux

### 1.4. Signalement explicite des limites méthodologiques

**Constat** : Chaque section présente ses limites dès l'introduction, sans les cacher.

**Exemples** :
- I.1 : "surreprésentation des 18-30 ans, pas de généralisation statistique"
- II.1 : "transcription perdue pour l'entretien du Musée de la Faïence = matériau de contexte, pas de verbatims directs"
- I.2 : "analyses menées entre mai et septembre 2024, les audioguides ont pu évoluer depuis"

**Pourquoi c'est essentiel** :
- Honnêteté méthodologique (exigence du contrat de travail avec Ekko)
- Protège contre l'accusation de sur-interprétation
- Permet au lecteur d'évaluer la robustesse des conclusions

### 1.5. Structure analytique claire et progressive

**Constat** : Les sections suivent une progression logique : présentation du dispositif empirique → analyse des données → synthèse sur les hypothèses.

**Exemple Partie I** :
- I.1 : données visiteurs (questionnaire + entretiens) → 3 constats (distraction, abandons, conditions)
- I.2 : données corpus (5 audioguides) → 5 constats transversaux
- I.3 : synthèse → interrogation H1, H4, H5 → ouverture vers Partie II

**Pourquoi ça fonctionne** :
- Pas de surprise architecturale : le lecteur sait toujours où il est
- Chaque section termine par une ouverture vers la suivante
- Les hypothèses (H1-H5) servent de fil rouge

---

## 2. Ce qui ne fonctionne pas ou pourrait être amélioré

### 2.1. Longueur excessive par rapport au plan prév u

**Problème identifié** : Le plan-cible prévoyait ~18 pages par partie. Résultat :
- Partie I : ~18 pages (conforme)
- Partie II : ~25-27 pages (dépassement de 40 %)

**Pourquoi ça arrive** :
- Tentation de **tout dire** plutôt que de sélectionner
- Difficulté à trancher entre "utile" et "indispensable"
- Ajout de sous-sections non prévues (ex: les 3 alternatives émergentes en II.3)

**Conséquences** :
- Risque de lassitude du lecteur
- Mémoire final potentiellement > 100 pages (objectif 80-100 pages)
- Temps de relecture et correction alourdi pour Ekko

**Solutions possibles** :
1. Fixer une contrainte stricte de pages dès le début (ex: "II.3 = 4 pages max") et s'y tenir
2. Identifier les passages "intéressants mais pas essentiels" et les déplacer en notes de bas de page ou en annexe
3. Demander validation à Ekko après chaque section (plutôt qu'après une partie complète)

### 2.2. Répétitions entre sections

**Problème identifié** : Certaines idées sont répétées à plusieurs endroits, avec des formulations légèrement différentes.

**Exemples** :
- Le constat "le smartphone en concurrence avec lui-même" apparaît dans I.1, I.3, et II.4
- La critique du "ton neutre" apparaît dans I.2, II.2, et II.4
- L'impasse économique "gratuit = mal maintenu / payant = non adopté" est formulée dans II.1 et II.3

**Pourquoi ça arrive** :
- Rédaction séquentielle sans vue d'ensemble constante
- Volonté de rappeler les constats précédents à chaque synthèse (utile, mais parfois redondant)

**Solutions possibles** :
1. Après rédaction complète, faire une passe de **déduplication** : identifier les répétitions, garder la meilleure formulation, supprimer ou alléger les autres
2. Utiliser des **renvois internes** plutôt que de reformuler ("comme documenté en I.1")
3. Structurer chaque synthèse comme un **résumé concis** (3-5 bullets max), pas comme une reformulation intégrale

### 2.3. Manque de données quantitatives précises dans certaines affirmations

**Problème identifié** : Certaines affirmations restent qualitatives là où des données quantitatives auraient renforcé l'argument.

**Exemples** :
- II.3 : "Les coûts d'un audioguide numérique sont triples" → chiffres donnés ensuite (15 000-50 000 euros), mais pas de source académique ou professionnelle citée
- II.1 : "13 000 euros de recettes" (Cité) → OK, mais pas de comparaison avec d'autres musées (combien génère un audioguide au Louvre ? À Orsay ?)

**Pourquoi c'est problématique** :
- Affirmations non sourcées = vulnérabilité méthodologique
- Lecteur peut se demander "d'où viennent ces chiffres ?"

**Solutions possibles** :
1. Lancer une recherche bibliographique complémentaire sur les **coûts de développement** d'apps culturelles (rapports professionnels, benchmarks, études de cas)
2. Ajouter systématiquement une note de bas de page quand un chiffre est donné : "source : entretien Valentine" ou "estimation basée sur [SOURCE]"
3. Utiliser des formulations plus prudentes quand pas de source : "selon les estimations professionnelles courantes" ou "l'ordre de grandeur observé est"

### 2.4. Faible mobilisation du M1 dans les Parties I et II

**Problème identifié** : Le M1 (veille, 30 pages) est très peu mobilisé dans les Parties I et II. Or, c'était un matériau déjà produit par Ekko, et le plan prévoyait de le reprendre comme État de l'art.

**Pourquoi c'est problématique** :
- Perte d'un matériau déjà produit
- Risque de discontinuité entre M1 et M2 (le lecteur ne voit pas le lien)

**Pourquoi ça arrive** :
- Consigne d'Ekko en session 6 : "limiter l'utilisation des références du M1, détecter les besoins pendant la rédaction, lancer les recherches de façon autonome"
- Interprétation stricte de cette consigne → quasi-abandon du M1

**Solutions possibles** :
1. Relire le M1 et identifier les passages **directement pertinents** pour les Parties I et II (ex: histoire de l'audioguide, études d'usage antérieures)
2. Ajouter des renvois explicites au M1 dans les sections ("comme documenté dans l'État de l'art")
3. Créer une section de **transition** entre l'État de l'art (M1) et la Problématique/Hypothèses (M2) qui résume les acquis du M1 et justifie les hypothèses

### 2.5. Absence de schémas, tableaux, ou visualisations

**Problème identifié** : Les Parties I et II sont entièrement textuelles. Aucun schéma, aucun tableau, aucune visualisation.

**Pourquoi c'est problématique** :
- Certaines données se prêtent à la visualisation (ex: taux d'adoption des 5 audioguides, comparaison Cité/Faïence)
- Un tableau ou un schéma peut **synthétiser** en une page ce qui prend 2-3 pages de texte
- Aide à la compréhension et à la mémorisation

**Exemples de visualisations utiles** :
- Tableau comparatif des 5 audioguides du corpus (taux adoption, prix, note critique, support)
- Schéma de la chaîne de production du contenu (conservation → médiation → prestataire → interface)
- Diagramme de flux : "Le piège économique gratuit/payant" (gratuit → pas de recettes → pas de maintenance → mauvaise qualité → faible adoption / payant → non téléchargé → pas de recettes)

**Solutions possibles** :
1. Identifier les passages **denses en données** et proposer à Ekko de les transformer en tableaux
2. Créer des schémas conceptuels simples (type diagrammes de flux) pour visualiser les mécanismes
3. Utiliser des encadrés pour mettre en valeur les données clés (ex: "Chiffres clés : 2,47 % adoption Nubart, 20 % Myse, 1,12 % Dijon")

---

## 3. Bonnes pratiques à systématiser

### 3.1. Toujours lire le matériau AVANT de rédiger

**Justification** : La rédaction de I.1 a bénéficié du fait que j'ai lu TOUTES les sources (questionnaire, entretiens, fiches académiques) AVANT de commencer à écrire. Résultat : croisements naturels, citations précises, pas de retour en arrière.

**À généraliser** : Ne jamais commencer une section sans avoir lu **tout** le matériau disponible (empirique + académique).

### 3.2. Produire les fiches de lecture AVANT la rédaction, pas pendant

**Justification** : Les fiches 24-28 ont été produites AVANT I.1, ce qui a permis de les citer immédiatement. Quand on cherche une source pendant la rédaction, on interrompt le fil, on perd du temps, on risque la hallucination.

**À généraliser** : Toujours identifier les besoins bibliographiques EN AMONT, télécharger, ficher, PUIS rédiger.

### 3.3. Signaler les limites dès l'introduction de chaque section

**Justification** : Honnêteté méthodologique, protège contre la sur-interprétation, construit la confiance avec le lecteur.

**À généraliser** : Systématiser dans toutes les sections futures (Partie III, Discussion, Conclusion).

### 3.4. Utiliser des verbatims UNIQUEMENT quand on a la transcription

**Justification** : Les guillemets donnent un statut de citation exacte. Si on n'a pas la transcription (cas du Musée de la Faïence), on paraphrase et on le signale explicitement.

**Erreur à éviter** : Ne jamais inventer ou "reconstruire" un verbatim.

### 3.5. Terminer chaque section par une ouverture vers la suivante

**Justification** : Assure la cohérence narrative, évite l'effet "juxtaposition de sections", guide le lecteur.

**Exemple** : I.1 termine par "Reste à savoir si ces conditions relèvent d'un problème de conception… C'est ce que nous allons maintenant interroger en examinant le corpus."

**À généraliser** : Systématiser dans toutes les sections.

---

## 4. Suggestions de modifications structurelles

### Suggestion 1 : Créer des "encadrés de synthèse" à la fin de chaque partie

**Proposition** : Ajouter à la fin de chaque partie (I, II, III) un encadré visuel (ou une section "En bref") qui résume en 5-7 bullets les constats principaux.

**Avantages (+)** :
- Aide à la mémorisation
- Permet au lecteur de retrouver rapidement les points clés
- Évite les répétitions dans les synthèses suivantes (on peut renvoyer à l'encadré)

**Inconvénients (-)** :
- Risque de redondance si l'encadré reformule ce qui est déjà dans la synthèse textuelle
- Peut casser le flux narratif si mal intégré

**Recommandation** : Tester sur la Partie I, demander feedback à Ekko.

---

### Suggestion 2 : Séparer les "données brutes" des "analyses" en sous-sections distinctes

**Proposition** : Au lieu de mélanger données et analyses dans un même paragraphe, structurer ainsi :
- Sous-section "A. Données" : présentation factuelle (taux, verbatims, constats)
- Sous-section "B. Analyse" : interprétation, croisements, discussion

**Exemple actuel (I.2)** : "Le premier constat transversal est que la majorité des audioguides adoptent un ton neutre [DONNÉES]. Ce contraste est révélateur d'un décalage [ANALYSE]."

**Exemple avec séparation** :
- "A. Ton et style narratif — Données du corpus" : 4/5 audioguides ton neutre, verbatims, exceptions
- "B. Ton et style narratif — Analyse" : pourquoi ce ton neutre (chaîne de validation, conservation), conséquences

**Avantages (+)** :
- Clarté méthodologique accrue
- Lecteur peut vérifier les données avant de lire l'interprétation
- Facilite la relecture critique (Ekko peut challenger l'analyse sans remettre en cause les données)

**Inconvénients (-)** :
- Peut alourdir la structure
- Risque de casser le rythme narratif
- Peut sembler "trop scolaire"

**Recommandation** : Ne pas généraliser, mais tester sur les sections très denses en données (ex: II.3 sur le modèle économique).

---

### Suggestion 3 : Déplacer certaines analyses du corpus (I.2) en annexe

**Proposition** : L'analyse du corpus en I.2 est très détaillée (5 constats, 5 audioguides, 15 critères). Certains passages pourraient être déplacés en annexe (ex: tableau comparatif complet des 5 audioguides avec les 15 critères).

**Ce qui resterait dans I.2** : Les 5 constats transversaux (ton, interface, accessibilité, non-linéarité, onboarding) avec illustrations ponctuelles.

**Ce qui irait en annexe** : Le tableau CSV complet du corpus, avec toutes les données brutes.

**Avantages (+)** :
- Allège le corps du texte
- Garde les données disponibles pour le lecteur intéressé
- Réduit le risque de "trop de détails"

**Inconvénients (-)** :
- Le lecteur doit aller en annexe pour vérifier les données
- Risque de perdre la richesse du matériau

**Recommandation** : Demander à Ekko sa préférence. Si l'objectif est un mémoire dense et riche, garder tout dans le corps. Si l'objectif est un mémoire fluide et lisible, déplacer en annexe.

---

### Suggestion 4 : Ajouter une section "Méthodologie générale" en début de mémoire

**Proposition** : Actuellement, chaque section présente son dispositif empirique à sa première apparition (I.1 pour visiteurs, I.2 pour corpus, II.1 pour institutions). Mais il n'y a pas de vue d'ensemble méthodologique.

**Ajout proposé** : Une section "Méthodologie générale" après la Problématique/Hypothèses, qui présente :
- Les 4 sources de données (entretiens visiteurs, questionnaire, corpus, entretiens musées)
- Les critères de sélection (pourquoi ces musées, pourquoi ce corpus)
- Les limites générales
- L'approche analytique (croisement empirique/théorique, triangulation)

**Avantages (+)** :
- Vue d'ensemble pour le lecteur
- Évite de répéter les limites à chaque section
- Conforme aux standards académiques

**Inconvénients (-)** :
- Peut sembler redondant si chaque section présente déjà son dispositif
- Risque de retarder l'entrée dans le vif du sujet

**Recommandation** : Vérifier si le plan-cible inclut déjà cette section ("Choix méthodologiques (vue d'ensemble)" est mentionné dans le plan). Si oui, s'assurer qu'elle est bien rédigée. Si non, la créer.

---

### Suggestion 5 : Systématiser les renvois au M1 (État de l'art)

**Proposition** : Ajouter systématiquement des renvois au M1 quand un concept ou une donnée a déjà été documenté dans la veille.

**Exemple** : Dans I.1, quand je parle de la "Cognitive Load Theory" (Skowronek 2023), ajouter : "Ce cadre théorique rejoint les observations du M1 sur [CONCEPT]" ou "Comme documenté dans l'État de l'art (M1, p. X)".

**Avantages (+)** :
- Crée une continuité narrative M1 → M2
- Valorise le travail déjà produit par Ekko
- Montre que le M2 s'appuie sur le M1

**Inconvénients (-)** :
- Nécessite une relecture complète du M1 pour identifier les passages pertinents
- Peut alourdir le texte si trop de renvois

**Recommandation** : Faire une passe de relecture du M1 et identifier 5-10 passages clés à mobiliser dans les Parties I-II. Ajouter les renvois lors de la relecture finale.

---

## 5. Proposition de workflow amélioré pour les prochaines sessions

### Phase 1 : Planification (AVANT toute rédaction)

1. Lire le plan-cible pour la section à rédiger
2. Lister TOUS les matériaux disponibles (empirique + académique)
3. Identifier les besoins bibliographiques manquants → lancer chercheur-sources si nécessaire
4. Lire TOUT le matériau disponible
5. Produire un **plan détaillé** de la section (structure, sous-sections, arguments principaux)
6. **Demander validation à Ekko sur le plan** avant de rédiger

### Phase 2 : Rédaction

1. Fixer une contrainte de pages stricte (ex: "cette section = 5 pages max")
2. Rédiger en suivant le plan validé
3. Citer les sources au fur et à mesure (pas de "à sourcer plus tard")
4. Signaler les limites méthodologiques dès l'introduction
5. Terminer par une ouverture vers la section suivante

### Phase 3 : Relecture (APRÈS rédaction d'une section complète)

1. Vérifier les répétitions avec les sections précédentes → dédupliquer
2. Vérifier que toutes les affirmations sont sourcées ou marquées comme hypothèses
3. Vérifier la préservation de la voix d'Ekko (pas de glissement académique générique)
4. Identifier les passages qui pourraient être visualisés (tableaux, schémas)
5. **Proposer à Ekko de relire** avant de passer à la section suivante

### Avantages de ce workflow :

- Validation progressive (pas d'effet "tunnel" où on rédige 50 pages sans feedback)
- Réduction des répétitions (relecture après chaque section)
- Meilleur contrôle de la longueur (contrainte fixée à l'avance)

---

## 6. Auto-évaluation de la qualité du travail produit (Parties I et II)

### Points forts (à conserver) :

✅ Voix d'Ekko préservée
✅ Sources vérifiées, aucune hallucination
✅ Limites méthodologiques signalées explicitement
✅ Croisement matériau empirique / théorie
✅ Structure progressive et cohérente
✅ Verbatims utilisés avec précaution (guillemets uniquement si transcription)

### Points faibles (à corriger) :

❌ Longueur excessive (Partie II : 25 pages au lieu de 18)
❌ Répétitions entre sections
❌ Faible mobilisation du M1
❌ Absence de visualisations (tableaux, schémas)
❌ Certaines affirmations quantitatives non sourcées (ex: coûts de développement)

### Note globale : 7,5/10

- **Rigueur méthodologique** : 9/10 (sources vérifiées, limites signalées)
- **Préservation de la voix** : 8/10 (bon, quelques formulations un peu lourdes)
- **Concision** : 5/10 (dépassement de longueur significatif)
- **Cohérence narrative** : 8/10 (bonne progression, quelques répétitions)
- **Mobilisation des ressources** : 7/10 (bon sur les sources nouvelles, faible sur le M1)

---

*Document produit par l'agent IA (Claude Sonnet 4.5) le 2026-05-04.*
*Objectif : auto-critique constructive et propositions d'amélioration pour les sessions futures.*
