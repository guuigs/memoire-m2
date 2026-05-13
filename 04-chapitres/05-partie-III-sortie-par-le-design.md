# Partie III — Y a-t-il une sortie par le design ?

## III.1 — Ce que les deux tensions impliquent pour la conception

### Ce que les Parties I et II ont établi

Les deux parties précédentes ont documenté une double tension qui pèse sur l'audioguide mobile.

La première tension, explorée en Partie I, est celle de **l'outil contre lui-même**. Le smartphone, en tant que support de médiation muséale, est structurellement pris dans une contradiction : il promet d'accompagner la visite, mais il consomme de l'attention ; il promet l'autonomie, mais il impose des parcours ; il promet la discrétion, mais il ne sait pas se faire oublier. Cette tension tient à la nature même du smartphone — objet multifonction, toujours sollicitant, toujours en concurrence avec ses propres usages (photos, messages, notifications). Elle tient aussi à des défauts de conception récurrents : ton neutre et pédagogique, interfaces visuelles consommatrices d'attention, absence de scénarisation globale, frictions techniques à l'*onboarding*.

La seconde tension, explorée en Partie II, est celle de **l'institution contre l'outil**. Les musées produisent des audioguides dans des conditions qui empêchent structurellement la qualité : modèle économique inadapté (gratuit = mal maintenu, payant = non adopté), chaîne de production fragmentée (conservation contre médiation, validation séquentielle, compromis à la baisse), dépossession à trois niveaux (technique, éditoriale, symbolique). Ces contraintes ne sont pas des accidents — elles sont le résultat de choix institutionnels, de rapports de force internes, et de modèles économiques hérités.

Face à ces deux tensions, la question qui ouvre cette troisième partie est simple à formuler, difficile à trancher : **y a-t-il une sortie par le design ?** Autrement dit, en assumant ces contraintes comme des données de départ (et non comme des obstacles à éliminer), que peut-on concevoir comme outil de médiation numérique qui soit à la fois viable, portable, et réellement adopté ?

### Ce qu'un designer peut résoudre

Commençons par ce qui relève du périmètre d'action du design — c'est-à-dire ce qu'un·e designer peut améliorer en intervenant sur l'interface, le contenu, et l'expérience d'usage.

#### 1. Le ton et l'incarnation du contenu

L'analyse du corpus (Partie I) a montré que 4 audioguides sur 5 adoptent un ton « neutre » et « pédagogique », là où les visiteurs demandent un contenu « ludique et incarné », « comme un podcast », « comme les vidéos YouTube ». Le seul audioguide du corpus qui se distingue par un ton narratif — le Pop Guide du Château de Langeais — montre qu'un contenu incarné est possible : voix engagée, intonations, récit qui accroche, indications spatiales qui maintiennent le lien avec l'espace physique.

Un designer (ou une équipe de conception incluant un·e rédacteur·rice, un·e sound designer, un·e narrateur·rice) peut **changer le ton**. Cela suppose de sortir du « modèle du déficit » identifié par Bensaude-Vincent (2010) — cette posture où le public est défini par ce qu'il lui manque, et où la médiation « descend » du savant vers l'ignorant. Incarner un contenu, c'est parler *avec* le visiteur, pas *au* visiteur. C'est adopter une voix identifiable, un rythme, une subjectivité assumée. C'est raconter plutôt que décrire.

Cette transformation est à la portée du design — mais elle requiert une condition préalable : que la chaîne de production permette à cette voix d'exister (voir infra).

#### 2. L'interface et la compétition attentionnelle

L'analyse du corpus a montré que les interfaces visuelles des audioguides mobiles **forcent le regard vers l'écran**, au détriment de l'expérience de l'œuvre. Cartes, menus, listes de parcours, écrans de sélection : autant de moments où le visiteur doit détourner son attention de ce qu'il est venu voir. Les visiteurs le disent clairement : « les gens n'aiment pas l'interaction avec écran pendant la visite ».

Un designer peut **réduire la place de l'écran** dans l'expérience. L'application Myse du Musée Marmottant-Monet, avec son approche « lectoguide » par scan de cartels, montre une piste : l'écran sert à déclencher le contenu, pas à le porter. Une autre piste serait de concevoir une interface **audio-first** : le contenu est audio, l'écran ne sert qu'à naviguer entre les points d'écoute, et cette navigation est aussi simple que possible (un geste, un tap, pas de menu complexe). L'idéal serait que l'écran puisse rester dans la poche pendant l'écoute — ce qui suppose un système de déclenchement alternatif (NFC, beacon, numéro à taper, scan rapide).

Cette transformation est à la portée du design — mais elle se heurte à une limite structurelle : le smartphone reste un objet sollicitant même quand on ne regarde pas l'écran (voir infra).

#### 3. La non-linéarité et l'équilibre guidage/autonomie

L'analyse du corpus a montré un paradoxe récurrent : les audioguides **proclament offrir une liberté de parcours**, mais dans les faits, ils imposent des contraintes fortes (rappels à l'ordre si on dévie, interfaces qui « conseillent de suivre la proposition de l'application »). À l'inverse, les audioguides qui laissent une liberté totale (Myse, MAD) peuvent générer de la désorientation.

Un designer peut **concevoir un équilibre entre guidage et autonomie**. Cela suppose de distinguer plusieurs modes d'usage : un mode « guidé » pour les visiteurs qui veulent être accompagnés, un mode « libre » pour ceux qui veulent butiner, et des transitions fluides entre les deux. Cela suppose aussi de repenser les indications spatiales : au lieu de « suivez le parcours prévu », des formulations comme « si vous êtes devant [œuvre], vous pouvez écouter ceci » — qui informent sans contraindre.

Cette transformation est à la portée du design — et elle ne se heurte pas aux mêmes limites structurelles que les précédentes.

#### 4. L'*onboarding* et la réduction des frictions

L'analyse du corpus a montré que l'*onboarding* — le moment où le visiteur découvre et prend en main l'audioguide — est une source de frictions majeures : téléchargement lourd, permissions intrusives, tutoriels trop longs, connexion wifi défaillante, écran illisible en plein soleil. Ces frictions interviennent au moment décisif où le visiteur décide s'il va investir du temps et de l'attention dans l'application.

Un designer peut **réduire drastiquement les frictions à l'*onboarding***. Cela suppose de minimiser le poids de l'application (ou de proposer une webapp sans téléchargement), de limiter les permissions demandées (pas de géolocalisation si elle n'est pas indispensable), de supprimer les tutoriels au profit d'une interface auto-explicative, et de garantir un fonctionnement hors ligne (pas de dépendance au wifi du musée).

Cette transformation est à la portée du design — et elle a un impact direct sur le taux d'adoption.

### Ce qu'un designer ne peut pas résoudre seul

Mais le design a ses limites. Plusieurs des problèmes documentés en Parties I et II **ne relèvent pas du périmètre d'action du designer** — ou plutôt, ne peuvent pas être résolus par le design seul, sans transformation des conditions institutionnelles et économiques.

#### 1. Le modèle économique

L'impasse économique documentée en II.3 n'est pas résoluble par le design. On peut concevoir la meilleure application du monde, elle se heurtera toujours à la question : **qui paie pour la développer, qui paie pour la maintenir ?**

- Si l'application est gratuite, elle ne génère pas de recettes, donc pas de budget de maintenance, donc elle se dégrade (cas de Dijon, 3,3/5 avec bugs récurrents).
- Si l'application est payante, elle n'est pas téléchargée dans l'écosystème mobile actuel où la gratuité est la norme.
- Si l'application est financée par la collecte de données (comme le Louvre avec Flurry Analytics et Ubudu), elle pose des questions éthiques que le design ne peut pas évacuer.

Un designer peut proposer des pistes (webapp sans téléchargement, intégration dans une plateforme multi-sites, financement par mécénat), mais il ne peut pas **décider** du modèle économique. Cette décision relève de la direction du musée, de la tutelle, et des arbitrages budgétaires institutionnels.

#### 2. La chaîne de production du contenu

La chaîne de production fragmentée documentée en II.2 n'est pas résoluble par le design. On peut concevoir une interface parfaite, si le contenu est produit dans une logique de « compromis à la baisse » (conservation contre médiation, validation séquentielle, externalisation standardisante), il restera **neutre, désincarné, sans voix**.

Le verbatim de Pauline à la Cité de l'Architecture est éclairant : pour produire un contenu un peu plus libre, elle a dû **contourner la conservation** (« c'est pour les touristes, ça ne vous concerne pas »). Le fait qu'elle qualifie de « grosse avancée » le simple fait de dialoguer avec la conservation montre que le cloisonnement reste la norme.

Un designer peut plaider pour un ton plus incarné, proposer des formats narratifs, écrire des scripts engagés — mais si ces propositions sont ensuite **validées, relues, reformatées** par une chaîne qui valorise la neutralité scientifique, elles perdront leur voix. La question n'est pas « comment écrire un bon contenu », c'est « qui a le pouvoir d'écrire, et sous quelle contrainte de validation ».

#### 3. La nature du smartphone

La compétition attentionnelle structurelle du smartphone, documentée en I.1 et I.3, n'est pas résoluble par le design. On peut concevoir une interface minimale, audio-first, discrète — le smartphone **restera un objet sollicitant**.

Les travaux de Skowronek et al. (2023) montrent que la simple présence d'un smartphone, même éteint, réduit les performances attentionnelles de 8,5 %. Ce n'est pas l'interface de l'application qui pose problème — c'est **l'objet lui-même**, avec son potentiel de sollicitation permanent (notifications, messages, réseaux sociaux). Le visiteur doit fournir un effort cognitif pour *ne pas* regarder son téléphone, et cet effort entre en concurrence avec l'attention portée aux œuvres.

Un designer peut atténuer ce problème (interface discrète, mode « ne pas déranger » suggéré, contenu audio qui libère le regard), mais il ne peut pas **éliminer** la charge cognitive liée à la présence du smartphone. C'est une limite structurelle du support.

#### 4. La légitimité symbolique de l'audioguide

La dépossession symbolique documentée en II.4 n'est pas résoluble par le design. L'audioguide est traité par les institutions comme un **objet technique** (coûts, prestataires, statistiques d'usage), non comme une **œuvre de médiation** (auteur·rices identifié·es, vision éditoriale, évaluation de la transmission du savoir).

Cette réduction au technique se traduit par des décisions pragmatiques (« on a fait un benchmark », « on a choisi Tonvelte pour la robustesse »), non par des décisions éditoriales (« quelle voix voulons-nous porter ? », « quel récit voulons-nous raconter ? »). Tant que l'audioguide n'aura pas de **légitimité symbolique** au sein de l'institution — tant qu'il ne sera pas reconnu comme porteur de la voix du musée, au même titre qu'un livret d'exposition ou qu'une visite guidée — il restera un outil marginal, orphelin, sous-investi.

Un designer peut plaider pour cette reconnaissance (en proposant des crédits visibles, une signature auctoriale, une charte éditoriale), mais il ne peut pas **décider** que l'institution valorisera l'audioguide. Cette décision relève de la gouvernance muséale et de la politique culturelle.

### Ce que le design peut faire : assumer les contraintes comme données de départ

Si le design ne peut pas résoudre les problèmes structurels (modèle économique, chaîne de production, nature du smartphone, légitimité symbolique), que peut-il faire ?

La réponse que je propose est la suivante : **le design peut assumer ces contraintes comme des données de départ, et concevoir en fonction d'elles** — plutôt que de faire semblant qu'elles n'existent pas.

Concrètement, cela signifie :

1. **Concevoir pour un budget de maintenance nul ou minimal**. Si l'on sait que l'application ne sera pas maintenue (parce que le modèle économique ne le permet pas), il faut concevoir une application qui **ne nécessite pas de maintenance** : contenu statique, pas de dépendance à des services externes, pas de fonctionnalités complexes qui risquent de casser. C'est une contrainte forte, mais c'est la réalité de la plupart des musées de taille moyenne.

2. **Concevoir pour une chaîne de production fragmentée**. Si l'on sait que le contenu sera validé par la conservation et reformaté par un prestataire, il faut **intégrer cette contrainte dans le processus de conception** : écrire des scripts qui restent incarnés même après relecture, proposer des formats qui résistent à la standardisation, ou inversement, accepter que le contenu soit neutre et compenser par d'autres éléments (scénarisation, navigation, design sonore).

3. **Concevoir pour un smartphone sollicitant**. Si l'on sait que le visiteur sera distrait par son téléphone quoi qu'il arrive, il faut **concevoir pour cette distraction** : contenus courts qui supportent l'interruption, reprise facile après une pause, mode « je reviens plus tard » explicite. L'idéal n'est pas un visiteur qui écoute tout d'une traite (ce qui n'arrivera pas), c'est un visiteur qui peut écouter ce qu'il veut, quand il veut, sans culpabilité.

4. **Concevoir pour un outil sans légitimité symbolique**. Si l'on sait que l'audioguide ne sera pas reconnu comme œuvre de médiation, il faut **lui donner cette légitimité par le design lui-même** : crédits visibles (« écrit par X, lu par Y »), signature éditoriale (« ce parcours a été conçu par l'équipe de médiation de Z »), ton assumé qui dit « je suis une voix, pas une notice ».

Cette posture — assumer les contraintes plutôt que les nier — est ce que Schmitt et Meyer-Chemenska (2015) appellent le **« post-numérique »** : le moment où la technologie devient **invisible**, intégrée, non-spectaculaire. L'audioguide idéal ne serait pas une application tape-à-l'œil avec réalité augmentée et chatbot IA — ce serait un outil **discret et efficace**, qui fait ce qu'il promet (accompagner la visite) sans s'imposer, sans consommer d'attention, sans prétendre être autre chose qu'un compagnon temporaire.

### Hypothèses de conception issues des Parties I et II

À partir des constats documentés et des limites identifiées, je formule quatre hypothèses de conception qui guideront le prototype présenté dans la section suivante :

**HC1 — Minimiser l'écran, mais ne pas imposer l'audio.** L'écran est une source de friction et de compétition attentionnelle — mais l'audio narratif linéaire peut aussi être vécu comme invasif. Une visiteuse de 32 ans (R3) décrit l'audioguide comme « quelqu'un qui me parle dans l'oreille et qui m'empêche d'être tranquille » ; un retraité de 68 ans (R4) dit « j'en ai marre qu'on me parle » et préfère « voir des trucs ». L'hypothèse initiale d'un audioguide **audio-first** doit donc être nuancée. Deux pistes émergent : (a) une approche **audio-first** où le contenu principal est audio, l'écran ne servant qu'à naviguer — c'est ma conviction personnelle, car l'audio libère le regard pour l'œuvre ; (b) une approche **visuel court + audio optionnel**, où le contenu par défaut est un texte bref scannable, avec possibilité d'écouter pour ceux qui le souhaitent. Dans les deux cas, l'enjeu est de **ne pas s'imposer** : laisser le visiteur choisir son mode de consultation, ne jamais forcer l'écoute linéaire.

**HC2 — Incarner le contenu.** Le ton neutre et pédagogique est une conséquence de la chaîne de production, mais c'est aussi un **choix de design** que l'on peut contester. Un contenu incarné (voix identifiable, narration, subjectivité assumée) engage davantage le visiteur, même s'il est plus difficile à faire valider par la conservation.

**HC3 — Accepter l'interruption.** Le visiteur sera distrait, interrompu, sollicité par d'autres usages de son téléphone. Plutôt que de concevoir pour une écoute linéaire et continue (qui n'arrivera pas), il faut concevoir pour **l'interruption et la reprise** : contenus autonomes, pas de dépendance à un ordre d'écoute, reprise facile après une pause.

**HC4 — Assumer la modestie du dispositif.** L'audioguide ne résoudra pas les problèmes structurels du musée (modèle économique, gouvernance, légitimité). Il peut, au mieux, **accompagner une visite** — et c'est déjà beaucoup. Assumer cette modestie, c'est renoncer aux promesses excessives (« expérience immersive », « visite personnalisée », « médiation augmentée ») pour se concentrer sur ce qui compte : **être utile sans s'imposer**.

**HC5 — Proposer un onboarding conceptuel.** Les entretiens révèlent un besoin rarement couvert : un **cadrage initial** qui prépare le visiteur à ce qu'il va voir. Un chef de projet digital (R6) le formule en termes UX : « T'arrives, t'es lâché, démerde-toi. Alors qu'un onboarding visiteur ça serait pas con. » Ce besoin ne concerne pas seulement les frictions techniques (téléchargement, wifi), mais un déficit plus profond : le visiteur novice manque de **clés d'entrée** pour comprendre pourquoi ce qu'il regarde vaut le coup. Un audioguide pourrait proposer un module d'introduction court (2-3 minutes) qui pose le contexte, donne des repères, et amorce l'intérêt — avant même de parler des œuvres individuelles.

**HC6 — Penser l'après-visite.** Les applications actuelles sont pensées pour accompagner la visite en cours, pas pour prolonger l'expérience. Or une visiteuse (R3) exprime un besoin clair : « Après, quand je rentre, des fois j'ai envie de me souvenir de ce que j'ai vu, et là j'ai plus rien. » L'étude de Marques et Costello (2017) montre que l'engagement est meilleur hors site qu'en galerie. Un audioguide pourrait intégrer une fonction de **trace** : sauvegarder les œuvres consultées, permettre de les retrouver après la visite, proposer des approfondissements pour ceux qui veulent « reprendre » l'expérience chez eux.

Ces six hypothèses de conception guideront le prototype présenté en III.2.

