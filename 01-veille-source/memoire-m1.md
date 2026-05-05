


## Université Sorbonne Paris Nord
Master Design d’Interface Multimédia et Internet | M1








Entre promesse d’accessibilité culturelle et réalité d’un
usage limité, comment expliquer l’adoption relative des
dispositifs numériques de médiation muséale ?


## Guilhem Terrier
## 2024-2025






Directeur de mémoire : Benoît Berthou         |          Numéro étudiant : 12400185



## Remerciements

Je tiens à exprimer ma profonde gratitude à toutes les personnes qui ont contribué, de près ou
de loin, à l’élaboration de ce mémoire.
Je remercie tout d’abord Benoît Berthou pour son accompagnement rigoureux, ses conseils
avisés et son suivi bienveillant tout au long de ce travail. Son encadrement a été d’une grande
aide et d’un véritable soutien.
Je souhaite également remercier l’ensemble de mes professeurs et mes camarades, dont les
remarques, les suggestions et les échanges ont enrichi ma réflexion et nourri ce mémoire.
Un grand merci à mes collègues du C2 pour leurs précieux conseils, leur disponibilité et leur
soutien tout au long de ce parcours.
Je remercie tout particulièrement mon père, pour sa relecture attentive et ses conseils toujours
pertinents, qui m’ont permis d’améliorer considérablement la qualité de ce travail.
Enfin, je tiens à adresser un remerciement profond et sincère à Flore, pour sa présence
constante, ses encouragements, ses conseils et son soutien indéfectible, sans lesquels ce
mémoire n’aurait pas vu le jour dans les mêmes conditions.

À toutes et à tous, merci.

Article de mémoire - DIMI - 2024/2025                                                                                  3


Résumé (FR)
Cet état de l’art se penche sur les enjeux contemporains de la médiation muséale en France,
avec un focus particulier sur l'intégration des dispositifs numériques dans les institutions
culturelles et notamment les dispositifs d’audioguide.
En partant d'une analyse historique, je retrace l'évolution de la médiation, de ses débuts
jusqu'à son rôle actuel dans les musées. Je m'intéresse notamment à la manière dont les outils
numériques, tels que les audioguides ou les applications mobiles, transforment l'expérience
des visiteurs, et comment ceux-ci sont reçus par le public. Ces dispositifs, bien qu'ils offrent
des possibilités inédites de personnalisation et d'interactivité, soulèvent également des
questions importantes: enrichissent-ils réellement la visite ? Permettent-ils une meilleure
compréhension des œuvres, ou risquent-ils de détourner l'attention ?
En m'appuyant sur des études récentes, des statistiques et des exemples concrets, je mets en
lumière les débats autour de la médiation, et les enjeux que posent l’intégration des
dispositifs numériques dans les espaces muséaux. Enfin, je propose succinctement des pistes
d'amélioration pour ces dispositifs, cette partie sera approfondie lors de ma deuxième année
de master. Cet état de l'art, pose les bases nécessaires d'une réflexion sur les possibilités de
l’application mobile comme dispositif de médiation muséale réussie et pertinente.

Mots clés :
médiation | musée | audioguide | application mobile | interface utilisateur | expérience
utilisateur

Article de mémoire - DIMI - 2024/2025                                                                                  4


Abstract (ENG)
This review looks at contemporary issues in museum mediation in France, focusing on
integrating digital devices in cultural institutions, especially audio guides.
Starting with a historical analysis, I trace the evolution of mediation, from its beginnings to
its current role in museums. In particular, I look at how digital tools such as audioguides and
mobile applications transform the visitor experience, and how the public receives these.
Although these devices offer unprecedented possibilities for personalization and interactivity,
they also raise important questions: Do they enrich the visit? Do they enhance understanding
of the works of art, or do they run the risk of diverting attention?
Drawing on recent studies, figures, and concrete examples, I highlight the debates
surrounding mediation and the issues raised by integrating digital devices in museum spaces.
Finally, I succinctly suggest ways in which these devices can be improved. This part will be
explored in greater depth during my second year of the Master's program. This
state-of-the-art work lays the necessary foundations for a reflection on the possibilities of
successful integration of the mobile application as a museum mediation device.

Key words :
mediation | museum | audioguide | mobile application | user interface | user experience

Article de mémoire - DIMI - 2024/2025                                                                                  5


Table des matières

Remerciements...........................................................................................................................3
Résumé (FR)..............................................................................................................................4
Abstract (ENG)..........................................................................................................................5
Table des matières......................................................................................................................6
Introduction................................................................................................................................7
Partie 1 : Caractéristiques et écosystème de la médiation culturelle..........................................9
A) Comment la médiation s'est installée dans les missions de l'institution culturelle ?.......9
B) Débats et réflexions sur la médiation en France............................................................13
C) La compréhension des publics, essentielle pour développer un discours adapté..........16
Partie 2 : Quels enjeux pour la médiation numérique ?...........................................................20
A) Une révolution en théorie, les aspects du bouleversement numérique.........................20
B) L'audioguide, un outil largement plébiscité..................................................................22
C) Questionnement et perspectives d'amélioration pour la médiation mobile...................26
Conclusion................................................................................................................................28
Bibliographie / Webographie....................................................................................................30
Liste des figures.......................................................................................................................34

Article de mémoire - DIMI - 2024/2025                                                                                  6


## Introduction
« Le problème du médiateur, c’est le médiateur. »
## — Denis Guedj, 1992


Cette affirmation, pouvant paraître quelque peu radicale, dit en réalité beaucoup sur la
tension qui anime la médiation : comment faire lien sans faire obstacle ? En d’autres termes,
comment accompagner une expérience sans la parasiter ou l’alourdir ? Dans le domaine
muséal, cette interrogation est d’autant plus actuelle que les dispositifs et les formats de
médiation se multiplient, portés notamment par la révolution numérique. Celle-ci apporte
dans le domaine muséal le dispositif de l’audioguide, bientôt suivis d’un ensemble d’autres
dispositifs numériques. La médiation se fait mobile, intéractive, immersive, etc. Le
changement pour les institutions est inédit et significatif, sans commune mesure et celles-ci
sont poussées à se réinventer, repenser leur rôle et leurs missions.
Le musée, tel que défini par le Larousse,
## 1
est un lieu de conservation et de présentation
d’objets culturels, scientifiques ou artistiques. Le musée se distingue de toute autre entité
culturelle par le fait qu’elle est par nature tournée vers le visiteur. Un musée doit par essence
s’intéresser au visiteur et à ses comportements pour adapter l’expérience proposée. Ainsi,
l’ère numérique, de la vulgarisation et de la circulation de l’information, impose aux
institutions de faciliter et de repenser le discours entre le musée et le(s) public(s). C’est ici
qu’intervient la notion de médiation. Selon Wikipédia
## 2
, la médiation vise à « faciliter la
circulation d’informations » ou à « rétablir des relations ». Lorsqu’elle se fait numérique ou
culturelle, elle devient le maillon qui relie le visiteur à l'œuvre. La médiation, profondément
reliée à l’humain et à ses besoins, est une notion extrêmement évolutive.
L’expérience de la visite est une expérience relationnelle unique : avec les œuvres, avec les
autres visiteurs, avec soi-même, avec le récit proposé. Quel qu’il soit, il y a toujours un
discours, un échange dans une visite de musée. Dans ce cadre, l’interface de médiation joue
un rôle d’intermédiaire, mais aussi d’éventuel perturbateur. Elle est là pour faire lien, mais sa
## 2

https://fr.wikipedia.org/wiki/M%C3%A9diation

## 1

https://www.larousse.fr/dictionnaires/francais/mus%C3%A9e/53378
Article de mémoire - DIMI - 2024/2025                                                                                  7


seule présence implique déjà un ajout, une intervention, si bien que, pour reprendre Guedj,
elle est toujours en tension avec elle-même.
La réflexion autour de la place que doit prendre la médiation et ses dispositifs n’est pas
neuve, mais elle prend une nouvelle importance dans un contexte où les institutions
culturelles multiplient les tentatives de démocratisation via le numérique. La promesse est
alors celle d’une culture plus accessible, plus personnalisée, plus engageante. Mais la réalité
de terrain est plus contrastée : usages partiels, rejet de certains formats, surinformation, ou
encore désengagement progressif. Ainsi, entre promesse d’accessibilité culturelle et réalité
d’un usage limité, comment peut-on expliquer l’adoption relative des dispositifs numériques
de médiation muséale ?
J’ai pris le parti, dans cet exercice, de travailler avec un système d’entonnoir. La médiation
muséale est un sujet très largement traité, débattu et je risque de partir dans des axes de
réflexion qui me détourne de mon problème. Afin de pallier ce problème, je me propose de
reprendre la médiation à la base : son apparition, ses principaux débats, etc. Je passerai
ensuite aux enjeux numériques et particulièrement au dispositif de l’audioguide. Mes sources
sont variées, venant de différents milieux, pays et formats afin de diversifier le plus possible
mes informations pour garantir la qualité de mon écrit.
Il est important de garder à l’idée que cet article s’inscrit dans une logique d’état de l’art : il
ne vise pas à évaluer ou critiquer les dispositifs en place, mais à poser un cadre de
compréhension général. Ce détour par les origines et les bases idéologiques de la médiation
est nécessaire pour éviter de poser des diagnostics trop rapides : comprendre la médiation,
c’est d’abord prendre le temps d’en observer les usages, les erreurs et les critiques.
Enfin, étant donné le contexte dans lequel se fait la rédaction de ce mémoire, il me paraît utile
d’apporter quelques précisions concernant l’usage que j’ai pu faire de l’intelligence
artificielle (IA). Certaines références mentionnées ont été identifiées à l’aide d’IA, en
particulier Perplexity AI, qui m’a permis d’élargir mon champ de recherche plus efficacement
que par les moyens classiques. Cela étant dit, les réflexions développées ici, les choix de
sources, d’angles et de formulation restent le fruit d’un travail personnel, guidé par une
lecture attentive et une appropriation critique des contenus mobilisés.


Article de mémoire - DIMI - 2024/2025                                                                                  8








## Partie 1 :
Caractéristiques et écosystème de la médiation culturelle







A) Comment la médiation s'est installée dans les missions de l'institution
culturelle ?

Quel est le rôle d'un musée ? N'ayant pas le temps ou l'ambition dans ce mémoire de répondre
à cette question, je reprendrais simplement les propos de Elisabeth Caillet, muséologue et
docteure en sciences de l'éducation
## 3
. Celle-ci identifie trois grandes missions du musée : la
conservation des œuvres / la mise en valeur des œuvres / la médiation auprès du visiteur. Plus
simplement, la différence essentielle entre le musée et la collection privée est l'idée de
l'ouverture au public et donc, de la mise en place d'un dialogue, quel qu'il soit, entre
l'institution accueillante et le visiteur. Je me penche ainsi dans ce mémoire sur la question de
la forme de ce dialogue, en particulier avec les outils numériques.

## 3
Caillet, É. (1995). À l’approche du musée : la médiation culturelle. Presses Universitaires de Lyon.
Article de mémoire - DIMI - 2024/2025                                                                                  9


Il convient, avant d'aller plus loin dans notre analyse, de faire une mise en contexte de
l'apparition de la notion de médiation. Afin de faire ce rapide historique de la médiation en
milieu culturel, je me suis principalement aidé du podcast en 4 épisodes "Histoire de musées"
sur France Radio
## 4
## .

En parallèle de la révolution industrielle, le musée se démocratise et s'ouvre peu à peu au
grand public. Cette ouverture des collections privées transforme l'expérience de visite,
jusqu'alors savante et basée sur une accumulation d'objets dans les salles. L'exposition des
œuvres doit se réinventer. Cette transformation  passe dans un premier temps par une
épuration des salles d'exposition et une volonté de "partage" du savoir. Cette épuration à lieu
sur la seconde moitié du XIXème siècle, principalement en Angleterre et aux Etats-Unis, on
parle alors d'une volonté "d'épistémologie de l'objet". Il faut comprendre par cette expression
la volonté de mettre l'objet au cœur du discours institutionnel, de faire parler l'objet. Le rôle
du musée est alors d'être l'intermédiaire le plus discret possible entre le visiteur et l'objet.

Vient ensuite au début du XXème siècle une seconde évolution : la démocratisation au grand
public du musée. Pour mieux comprendre les enjeux suivants, il est important de comprendre
le contexte muséal aux Etats-Unis, qui jouent un rôle important dans notre histoire. Aux
Etats-Unis, le musée est principalement financé par ses visiteurs et par des donateurs privés,
il n'y a pas la "tradition" européenne des subventions d'état. Le musée américain étant donc
obligé de se réinventer, ces institutions seront précurseurs dans les études des publics, les
innovations pour attirer de nouveaux publics, et assumer les enjeux de rentabilité. Ainsi, au
début du XXème siècle aux Etats-Unis, les musées cherchent toujours à augmenter leur
fréquentation et la société cherche de plus en plus des moyens de se divertir, le cinéma n'est
toujours pas disponible au grand public et le musée joue alors sur la mise en contexte de
l'objet dans son environnement. Apparaît alors là un des premiers dispositifs de médiation
complexe : le diorama. Le diorama consiste en une mise en contexte d'un objet dans un
environnement stéréotypé, une coiffe indienne sera ainsi posée sur la tête d'un mannequin,
dans un tipi avec un calumet de la paix. Si ce dispositif est souvent critiqué par les conservateurs pour ses raccourcis et ses stéréotypes, il n'a pas totalement disparu : les salles de reconstitution avec son et lumière en perpétuent l'esprit, sous des formes renouvelées. Le musée est alors vu comme attractif, car divertissant.

## 4
France Culture. (2021). Podcast « Histoire de musées ».
Article de mémoire - DIMI - 2024/2025                                                                                  10



Figure 1 : Le Diorama du village Pequot, Mashantucket Pequot Museum and Research Center. © Noémie
## Étienne

En “pause” pendant les 2 guerres mondiales, le milieu muséal connaît néanmoins de
nombreuses évolutions dans l’entre-deux guerres. L'europe voit alors naître un mouvement
qui l'impactera dans bien des domaines : le Bauhaus. Les artistes / architectes du Bauhaus
amènent une nouvelle vision de l'espace et de son utilisation dans le contexte des expositions.

Aux Etats-Unis, la tendance est au "mur blanc"/"white wall", où l'idée est de valoriser l'objet
par l'effacement du dispositif. Concrètement, on développe un décor le plus aseptisé possible,
d'une certaine manière minimaliste. Ce "décor vide" a pour objectif de laisser le visiteur seul
devant l'œuvre, dans une contemplation ou rien ne vient parasiter l'expérience. Ici, la place de
la médiation est donc minime, voire absente. L'institution ne porte que le rôle d'entremetteur
entre l'œuvre et le visiteur.

À la sortie de la guerre, la société occidentale devient réellement une société de
consommation, et les musées adoptent eux aussi les logiques marketing. Les États-Unis
(encore et toujours) développent de véritables expositions "blockbuster", invitent des stars à
prêter leur voix aux audioguides, etc. Le musée fait alors un mix et doit trouver un équilibre
entre deux idéologies : le musée de la consommation et le musée de la contemplation.
Article de mémoire - DIMI - 2024/2025                                                                                  11



Aujourd'hui, il existe de nombreux types de supports et de formats de médiation, ayant pour
chacun des spécificités amenant à une forme de dialogue unique et une réception plus ou
moins efficace des publics. Selon le baromètre 2024 des publics des musées et des lieux
patrimoniaux, réalisé par l’agence GECE
## 5
, les outils de médiation intégrés aux espaces
d'expositions (cartels et panneaux) sont encore largement utilisés par les visiteurs, car ils ne
coupent pas les interactions sociales, n'imposent rien au visiteur. Les outils numériques
présents dans les salles sont également largement utilisés, plus que les audioguides et encore
plus que les applications mobiles.

La médiation peut également passer par le médiateur humain avec la visite guidée. Ce mode
de médiation est très intéressant car il permet de garder une expérience de sociabilité,
d'interactivité humaine tout en apportant une quantité et une qualité de connaissances
impossible via les panneaux classiques présents dans les salles. Cette expérience, bien que
largement appréciée, déclenche bien souvent un coût supplémentaire et est souvent limitée
par le manque de médiateurs disponibles.

On identifie donc comme types de support de médiation aujourd'hui :
- Les outils de médiation physiques présents dans les salles
- Les outils numériques présents dans les salles
- Les audioguides classiques
- Les audioguides sur téléphone
- La visite guidée physique
La médiation est donc aujourd'hui bien installée dans le paysage institutionnel, mais elle reste
source de débats et de réflexions afin de la rendre toujours plus pertinente.




## 5
GECE. (2024). Baromètre 2024 des publics des musées et des lieux patrimoniaux. Agence GECE.
Article de mémoire - DIMI - 2024/2025                                                                                  12



B) Débats et réflexions sur la médiation en France

Dans son cours de muséologie à l'école du Louvre, Anne Jonchery
## 6
évoque la question d'une
médiation nécessaire. Cela nous renvoie, dans l'histoire de la médiation, à la question de la
visite contemplative ou de consommation. Certains vont plus loin : la création d'une œuvre
implique la vision d'un artiste et donc ce qu'il souhaite exprimer. L'œuvre devient son propre
médiateur car l'œuvre exprime exactement ce que l'artiste veut qu'elle exprime. La médiation
d'un acteur extérieur (ici le musée) peut être vue comme un parasite de l'expérience. En quoi
l'institution est-elle "légitime" pour fournir des informations sur une œuvre alors même que
l'artiste l'a produite telle qu'elle est, sans complément ?

La question que cela pose également, est celle de la liberté du visiteur. Le visiteur est il
"contraint" par l'institution ou l'artiste à suivre un certain parcours, une certaine manière
d'aborder les œuvres ? Je pense qu'il est important de garder en tête que le public reste
toujours libre de vivre sa propre expérience. Denis Guedj exprime très clairement cette
importance de la liberté du visiteur dans une interview de 1992
## 7


“Il n’y a pas d’exhaustivité à un moment de culture. On peut se permettre qu’il
manque quelque chose. Il y a de la nécessité et il y a de la liberté. [...]  Les gens n’ont pas
parlé devant les œuvres. C’est de l’idéologie. Le problème du médiateur, c’est le médiateur.
L’art, la connaissance, le savoir, ce sont des activités importantes, plus que profanes, un peu
sacrées. Quelque chose qui donne de la joie et du bonheur, c’est le seul but du médiateur.”
Denis Guedj, écrivain français, 1992

Dans cette même interview, Denis Guedj évoque la question d'une médiation comme facteur
d'apprentissage. C'est d'ailleurs là le cœur de son propos et de sa critique. En effet, la
médiation proposée par le musée doit elle instruire ? éduquer ? divertir ? Rentre-t-on dans un
## 7
Caillet, É. (1995). À l’approche du musée : la médiation culturelle. Presses Universitaires de Lyon.
## 6
Jonchery, A. (2024). Introduction à la médiation et aux publics. Cours à l’École du Louvre, communication
orale.
Article de mémoire - DIMI - 2024/2025                                                                                  13


musée pour "apprendre" ? Cette question est la source de nombreux débats. Sur ce sujet,  je
me suis aidé du livre d’Elisabeth Caillet : A l'approche du musée, la médiation culturelle.
Enfin, comment ne pas nommer Michel Serrez, grand penseur de l’humain et des interactions
humaines avec les sciences, le savoir.

“Effectivement, la médiation n’est pas un apprentissage, mais il y a dans la médiation
comme une mise en condition, une mise en position d’apprendre ou de goûter qui se
rapproche de la conception que le philosophe se fait du bon instituteur.”
Michel Serres, philosophe et historiens des sciences, 1991

Ce que l'on peut retenir donc, c'est que le musée n'a pas comme objectif essentiel d'instruire,
et le terme est important, le public. Bien que cela ne soit pas sa mission, il y a également des
attentes du public d'obtenir des clés de déchiffrement d'une œuvre, et là-dessus, le musée se
doit d'aider son public. C'est ici qu'intervient la question de la **vulgarisation scientifique**, qui n'est pas annexe mais bien cardinale dans les problématiques de médiation muséale. Comment transmettre un savoir complexe, fruit de recherches parfois longues et minutieuses, sans le réduire à quelques images simplistes ? La vulgarisation pose une tension fondamentale entre accessibilité du discours et fidélité au savoir. Certains auteurs ont pu parler de « décadence » de la vulgarisation, craignant qu'elle n'altère le message scientifique ; d'autres y voient au contraire la condition même de la démocratisation culturelle.

Le dispositif de transmission doit donc réussir à donner des clés de déchiffrement à ceux qui le souhaitent, tout en s'invisibilisant le plus possible afin de laisser libre cours à la visite selon le bon vouloir du visiteur qui reste maître de son parcours.

Aujourd'hui, le débat glisse progressivement de la question de l'apprentissage au musée à
celle du musée divertissement, l'expérience "spectacle". On assiste au renouveau de la
médiation avec des dispositifs parfois polémiques comme les cités de l'histoire, proposant une
histoire parfois orientée, stéréotypée, mais qui connaît une réelle adhésion du grand public.
En dehors de toute considération politique ou idéologique, il est intéressant de constater que
le public se tourne de plus en plus vers une culture "plus accessible" et "spectaculaire" (voir
également le succès du Puy du Fou).

Article de mémoire - DIMI - 2024/2025                                                                                  14



Figure 2 : Bateau viking et scène de La Légende de Saint Philibert (1997-2004). © Wikipédia

Dans Apports de L’application Mobile Aux Connaissances et à L’évasion Mentale Induites
par L’expérience Muséale : Rôle de L’attention Focalisée et de la Distorsion du Temps, les
auteurs évoquent les recherches antérieures, qui ont longtemps conduit à considérer
l’expérience muséale comme prioritairement une expérience d’apprentissage. Aujourd'hui,
avec les différents outils numériques à disposition des musées, les agences spécialisées dans
les dispositifs immersifs, le musée a à sa disposition un vecteur de renouvellement de l’offre
muséale et un instrument de différenciation dans un environnement concurrentiel rude : les
outils numériques pour une médiation plus divertissante. Ces dispositifs numériques vont
enrichir les pratiques de médiation en offrant de nouvelles possibilités d'interaction avec les
publics (par exemple, des visites virtuelles, des ateliers en ligne, des applications éducatives).

Cette approche du musée spectacle est bien sûr soumise à de nombreuses critiques, on verra
d'ailleurs que l'expérience immersive n'est pas forcément un succès dans le cadre muséal. Il
reste important de garder en tête la liberté du visiteur dans l'expérience, et le spectacle est par
essence une expérience guidée, cadrée, chronométrée. Ce que ce nouveau courant nous
rappelle en fait, c'est la question de la compréhension du/des publics par le musée afin
d'adapter son offre de médiation.
Article de mémoire - DIMI - 2024/2025                                                                                  15



C) La compréhension des publics, essentielle pour développer un discours
adapté

Avant d'aller plus loin, une clarification terminologique s'impose. Les spécialistes ne s'accordent pas toujours sur la distinction entre « publics », « visiteurs » et « usagers ». Le terme de *public* renvoie souvent à une approche sociologique, héritée des travaux sur la sociologie des publics culturels. Le *visiteur* désigne davantage l'individu dans l'espace muséal, avec ses comportements et ses parcours. L'*usager*, enfin, est un terme plus fonctionnel, qui met l'accent sur l'interaction avec un dispositif ou un service. Dans ce mémoire, j'utilise principalement le terme de *visiteur* lorsque je parle de l'expérience in situ, et celui de *publics* (au pluriel) pour désigner la diversité des profils et des attentes.

Selon le baromètre GECE 2024 sur les publics de musée en France
## 8
, 78% des visiteurs
viennent dans un musée pour enrichir leurs connaissances, 55% pour voir des œuvres
uniques, 42% pour se déconnecter du quotidien, 36% pour passer du temps avec leurs
proches, 32% pour se divertir. Aujourd'hui, ce genre de statistiques est inhérent à la création
d'un dispositif de médiation. Comme  une entreprise privée, le musée doit comprendre sa
cible pour adapter sa proposition et maximiser l'efficacité de sa mission.

Il est devenu essentiel dans la démocratisation des musées de comprendre le public, ou les
publics présents afin d'adapter le discours et la scénographie du musée. Afin de traiter cette
question des publics au musée, je m'appuie prioritairement sur le cours de Anne Jonchery
donné à l'école du Louvre sur la médiation muséale
## 9
## .

Dans l'étude et la compréhension des publics, les États-Unis sont encore une fois en avance.
En effet, les musées américains, dans une logique commerciale et économique de rentabilité,
appliquent les modèles d'études marketing et d'enquête de la consommation dans le milieu
culturel. Ces musées sont financés par des donateurs privés et par leurs entrées à l'inverse de
l'Europe qui fonctionne beaucoup plus sur la subvention d'État.

L'Europe, et plus précisément la France, apporte une nouveauté dans l'enquête en la personne
de Bourdieu et de la sociologie. Bourdieu publie en 1966  "L'amour de l'art" qui redéfinit la
compréhension que les musées français ont de leur(s) public(s). Pour lui, la fréquentation des
musées est liée au niveau d'éducation et cela entraîne une hiérarchisation des pratiques
culturelles, et notamment du musée qui devient donc une pratique réservée inconsciemment à
une "élite culturelle". Maintenant que nous comprenons l'importance de la sociologie dans
## 9
Jonchery, A. (2024). Introduction à la médiation et aux publics. Cours à l’École du Louvre, communication
orale.
## 8
GECE. (2024). Baromètre 2024 des publics des musées et des lieux patrimoniaux. Agence GECE.
Article de mémoire - DIMI - 2024/2025                                                                                  16


l'étude des publics, il convient de définir les critères d'étude, et c'est là que la chose se
complique tant les possibilités sont variées :

- La sociabilité de la visite : en groupe (scolaire)/ indiv (famille)
- L'origine géo : touriste étrangers, nationaux, public local
- L'âge : enfants, ado, adultes, seniors, aînés
- Le handicap : moteur, sensoriel, mental, psychique
- La familiarité avec musée ou sphère muséale
- Adapter la médiation au format numérique
- Intemporel et non-spatial

Anne Jonchery ajoute dans son cours que le visiteur moyen a majoritairement tendance à se
sous-estimer vis à vis d'un "public type", le visiteur ne pense pas avoir les codes nécessaires,
et c'est peut-être sur ce point que les outils comme l'audioguide sont le plus utiles. L'étude des
dispositifs numériques devient donc un enjeu presque concurrentiel, du moins primordial. Sur
cet aspect de l'enquête sur les dispositifs numériques, nous approfondirons l'année prochaine
sur des propositions plus spécifiques, nous pouvons cependant prendre en exemple l'enquête
menée dans Une Mesure des Effets de L’utilisation D’un Outil Numérique Sur L’expérience
de Visite Muséale
## 10
. Cette enquête réalisée en 2019 nous révèle plusieurs points intéressants :
- Le jeune public perçoit l’audioguide comme favorisant l’appropriation intellectuelle
et spatiale.
- La borne multimédia mono-usager est perçue comme un outil ludique permettant de
faire la synthèse des connaissances pour les non initiés et les jeunes.
- Le public habitué a tendance à privilégier la visite libre, associée au plaisir esthétique
et à l'activité rhétorique.

La compréhension du public et de son comportement ne suffisent cependant pas, il nous faut
maintenant comprendre ses attentes afin de mieux anticiper et de mettre en place la meilleure
médiation possible. Sophie Deshayes l'exprime très bien dans sa publication L'usage des
## 10
Jarrier, E., Bourgeon-Renault, D., & Belvaux, B. (2019). Une mesure des effets de l’utilisation d’un outil
numérique sur l’expérience de visite muséale. Management & Avenir, 108(2), 107–126.
Article de mémoire - DIMI - 2024/2025                                                                                  17


supports mobiles au musée, des audioguides classiques au multimédia nomade, le public a
des attentes qu'il ne connaît parfois même pas, la création de nouveaux outils de médiation
doit donc nécessairement s'inscrire dans une forme de continuité avec les outils précédents
afin de faciliter son assimilation. Le musée est un contexte, une expérience, dans laquelle les
publics souhaitent majoritairement être guidés, accompagnés par l’institution
## 11
, surement
d'ailleurs car ne s'estimant pas apte/capable (de nouveau la question de la sous-estimation des
publics vis à vis du milieu). Aujourd'hui, il semble que le public plébiscite très largement les
outils de médiation à la visite libre et sans interférence. Les publics ont donc une attente
centrale, l'accompagnement du musée dans la visite via la médiation.

La médiation sous quel format ?
Pour Sophie Deshayes, le public recherche avant tout la parole du guide, son discours
et sa manière de le transmettre. Le guide a le pouvoir d'incarner le contenu, de le rendre plus
vivant et donc plus simple à intégrer pour le visiteur par le biais de petites anecdotes,
d'exemples. A l’inverse de cette spontanéité d’une visite avec un guide, il est à noter
qu’aujourd’hui, la médiation muséale est souvent validée par un conservateur qui est “tout en
haut de la hiérarchie” et pratiquement jamais au contact du public ! Le conservateur, expert
de son sujet, précise et reprécise ses éléments de langage et, de ce fait, perd en naturel et perd
son public.

Avec quels dispositifs ?
Selon les chiffres du Baromètre de GECE
## 12
, en France, lors de leur visite en musée,
38% des visiteurs utilisent des outils de médiation proposés par le musée, 35% s'aident
également de leur téléphone et seulement 19% indique ne pas utiliser d'outil d'aide à la visite,
adoptant donc une visite plus contemplative ou sociale du musée. On le voit, les chiffres nous
indiquent la nécessité de la présence d'une médiation dans un musée.

Alors que nous arrivons à la fin de ce passage sur les enjeux des publics, il convient de nous
interroger sur les enjeux actuels et les tendances émergentes pour les prochaines années.
Comme le dit Elisabeth Caillet dans A l'approche du musée, la médiation culturelle
## 13
, la
## 13
Caillet, É. (1995). À l’approche du musée : la médiation culturelle. Presses Universitaires de Lyon.
## 12
De nouveau le Baromètre 2024 des publics des musées et des lieux patrimoniaux
## 11
GECE. (2024). Baromètre 2024 des publics des musées et des lieux patrimoniaux. Agence GECE.
Article de mémoire - DIMI - 2024/2025                                                                                  18


question du format du dialogue du musée se doit d'être liée à son époque, avec les codes de
ses contemporains. En d’autres termes, le musée se doit d'être “actuel” pour être pertinent.

La révolution internet que nous connaissons depuis plus de 20 ans est sans précédent et rebat
complètement les cartes de l'accès à l'information, de la vulgarisation de la connaissance, du
divertissement, mais aussi de la place et du rôle du musée. Aujourd'hui, les visiteurs ne se
contentent plus de connaître le nom de l’artiste, de l’œuvre ou bien sa date de création
(Giusti, 2008), mais souhaitent aller au-delà de la contemplation de l'œuvre avec une
information plus personnalisée et une expérience plus émotionnelle. Avec la puissance de la
révolution internet, nous avons aujourd'hui la possibilité de casser la barrière de la parole du
guide vivant à travers un outil numérique afin que chacun puisse, sans contraintes, vivre
l'expérience de visite guidée vivante via un dispositif numérique.



Article de mémoire - DIMI - 2024/2025                                                                                  19







## Partie 2 :
Quels enjeux pour la médiation numérique ?







A) Une révolution en théorie, les aspects du bouleversement numérique

La démocratisation des outils numériques dans les musées représente aujourd’hui une
révolution qu'il serait difficile d'ignorer : elle constitue un véritable bouleversement dans la
manière de concevoir, de transmettre et de vivre l’expérience au musée. En effet, le
numérique comme outil/dispositif de médiation, offre des perspectives de développement
jusqu'alors inenvisageable, en particulier sur la personnalisation de l'expérience. Ces
multiples bouleversements posent aussi la question du sens de la visite à l'heure du
numérique.

Pourquoi dit-on que les outils numériques repensent la médiation ? En soit, la réponse n'est
pas forcément innée et il mérite que je précise ce point. Il est important de garder en tête
également que les atouts proposés dans cette sous-partie sont des arguments théoriquement
Article de mémoire - DIMI - 2024/2025                                                                                  20


applicables sur l'utilisation du numérique, nous verrons ensuite que ce n'est pas toujours le
cas...

Là où la médiation physique impose souvent un parcours unique, une transmission linéaire du
savoir, le numérique autorise une personnalisation accrue de l'expérience. Cette expérience
était jusqu'alors réservée au médiateur humain, ayant alors seul la capacité de créer un lien,
une interaction entre le musée et le visiteur. Grâce à des technologies interactives,
contextuelles et adaptatives, chaque visiteur peut désormais construire un rapport singulier à
l’œuvre ou à l’exposition. Une carte interactive, une reconstitution 3D ou encore une
interface tactile permettent de s’approprier le contenu à son propre rythme, selon ses intérêts,
son niveau de connaissance, sa langue, voire ses contraintes physiques ou sensorielles. Ce
mouvement ouvre la voie à une médiation plus inclusive, mieux adaptée aux visiteurs
étrangers ou en situation de handicap, tout en abaissant les barrières symboliques à l’entrée
dans l’univers culturel.

Le numérique introduit également une autre temporalité de la visite. Là où celle-ci était
restreinte, logiquement, au temps passé dans l’espace muséal, les dispositifs numériques
(applications mobiles, tablettes, QR code, contenus téléchargeables, ...) permettent
aujourd’hui de prolonger l’expérience au-delà des murs du musée. L’utilisateur peut donc
revisiter des œuvres, approfondir un propos ou simplement revivre une contemplation, dans
une ambiance, une émotion, une disponibilité différente. Cette accessibilité renforcée s’inscrit
bien sûr dans une volonté de démocratisation culturelle, qui consiste à porter le musée au plus
près du quotidien, sur des supports connus et maîtrisés par le plus grand nombre et surtout par
ceux qui ne sont pas initialement à l'aise avec les codes muséaux. Autrement dit, les outils
numériques peuvent représenter une forme de bouée qui sert à rendre plus simple la visite.

Autre aspect essentiel : l’interactivité. En intégrant des logiques issues des autres activités
numériques, où le visiteur devient acteur, les dispositifs numériques instaurent une nouvelle
forme de dialogue entre le visiteur et les œuvres. Le musée devient un lieu où on explore, on
choisit quoi faire, on manipule. Cette logique permet d'amener de nouvelles appropriations du
musée, que l'institution elle-même n'aurait pas imaginé ou n'aurait pas pu faire elle-même.
Cette logique peut se traduire par exemple par l'explosion des contenus de vulgarisation
Article de mémoire - DIMI - 2024/2025                                                                                  21


culturelle sur les réseaux sociaux qui forcent les musées à repenser la manière de distribuer et
de faire le contenu, mais je reviendrai sur cet enjeu plus tard.

Cependant, il serait ambitieux, voire naïf, de penser que ces dispositifs peuvent être
simplement appliqués dans le cadre domestique comme dans le muséal. Le musée garde des
éléments qui lui sont propres et ne peuvent (pas encore) être remplacés : contexte d’usage
scénographie, densité des visiteurs, attention exigée... Tout cela impose une réflexion sur les
formats et les interfaces proposées : par exemple on ne peut pas proposer une vidéo YouTube
de vulgarisation dans un musée, il faut faire un mix entre tradition de médiation et habitudes
de contenus numériques, comme je l'indiquais en fin de première partie : pour créer un
nouvel outil, il est primordial de s'inspirer de l'existant.

Certaines expériences numériques se sont d'ailleurs retrouvées peu concluantes, comme les
expériences d'immersion, qui sortent le lieu de visite de son caractère libre au profit d'une
expérience de "spectacle". Le musée, en tant qu'environnement à caractère social,
contrairement au cadre domestique, oblige à penser l'outil numérique dans sa dimension
relationnelle, nécessitant une forme de discrétion afin de ne pas déranger les personnes
autour.

Les recherches de Schmitt et Meyer-Shemenska sur les vingt dernières années de numérique muséal montrent d'ailleurs des cycles récurrents : une période où l'écran est en monstration et remplace presque l'exposition, suivie d'une période où le tactile devient central, puis d'une phase où le dispositif doit s'effacer et se faire discret. On assiste alors à un retour des audioguides, avant que de nouveaux dispositifs (immersifs, puis IA) ne relancent le cycle. C'est ce que l'on pourrait appeler une « course à l'échalote » technologique, où un dispositif en chasse un autre.

De ces contraintes et de ces cycles, un objet/dispositif sort du lot, ayant fait assez largement ses preuves mais ne cessant de se réinventer au gré des évolutions techniques : l'audioguide.

B) L'audioguide, un outil largement plébiscité

Avant d’entrer dans le détail, il faut d’abord définir ce qu’est un audioguide dans le cadre
muséal. Selon le Dictionnaire de muséologie de François Mairesse, un audioguide est un
appareil portatif mis à disposition par un musée, qui fournit des commentaires pendant la
visite, le but est d'accompagner le visiteur tout au long de son parcours, en apportant des
explications sur les objets exposés. Ce type d’outil répond à un besoin simple : beaucoup de
visiteurs se retrouvent face à des œuvres sans forcément avoir les connaissances ou les
repères pour les comprendre. L’audioguide vient alors combler ce manque et accompagne
personnellement le visiteur tout au long de la visite. Il aide à donner du sens aux œuvres, à
expliquer leur histoire, leur valeur. Il offre des "clés" pour décoder ce que l’on voit.

Article de mémoire - DIMI - 2024/2025                                                                                  22


L'audioguide prendra plusieurs formes tout au long de son histoire. Prenons ici le temps de
faire un petit rappel de l'histoire de l'apparition de cet outil et de sa démocratisation, je m'aide
pour ce petit rappel de l'ouvrage Estudios sobre públicos y museos. Volumen I. Públicos y
museos: ¿Qué hemos aprendido ? (Source trouvée et traitement assisté par Perplexity AI)
## 14


Le tout premier modèle d'audioguide est mis en place en 1952 au Stedelijk Museum
d’Amsterdam. Il s’agissait alors d’un magnétophone portable avec seulement deux boutons
pour le volume. En 1961, le Phoenix Art Museum aux États-Unis propose un audioguide à
cassette, et y ajoute la voix d’un acteur connu afin d'améliorer l'attractivité du musée. Ce type
d’approche est très caractéristique des institutions américaines de l’époque, qui cherchent à
augmenter leur fréquentation par tous les moyens, en empruntant les codes du système de
consommation traditionnel.


Figure 3 : Visiteurs utilisants le tout premier dispositif audioguide au Stedelijk Museum, 1952 ©  Nederlands
Instituut voor Beeld en Geluid

En France, le moment clé est assurément l’exposition Toutankhamon de 1967 à Paris. Cette
exposition bat des records d’affluence (encore une "exposition marketing" d'ailleurs), et
## 14
Jannen Contreras Vargas, et al. (2016). Estudios sobre públicos y museos. Volumen I. Públicos y museos:
¿Qué hemos aprendido ? Escuela Nacional de Conservación, Restauración y Museografía (ENCRyM-INAH).
(Source trouvée et traitement assisté par Perplexity AI.)
Article de mémoire - DIMI - 2024/2025                                                                                  23


l’audioguide y est présenté comme une véritable innovation, saluée par le public. On
commence à percevoir l’audioguide non seulement comme un outil utile, mais aussi comme
un véritable dispositif à part entière dans la médiation culturelle, pas juste un gadget. Les
années 1980 marquent une première grande évolution technique avec l’arrivée du CD, puis le
développement d’un audioguide façon Walkman, comme ce fut le cas au Louvre. Peu à peu,
les formats deviennent plus compacts, plus faciles à utiliser, notamment grâce à la
démocratisation des cartes mémoire. À la fin du siècle, les premiers modèles avec écrans
apparaissent : on ne se contente plus de l’audio, on ajoute l’image.

Dans les années 2000, le numérique explose. Avec la bulle Internet, puis l’arrivée du MP3, et
surtout du smartphone tactile (l’iPhone étant lancé en 2007), les outils évoluent très vite. Les
audioguides deviennent plus interactifs, avec des écrans, des menus, des animations, etc. En
parallèle, de nombreuses institutions commencent à proposer des parcours via les téléphones
personnels des visiteurs, une pratique qui se développe encore aujourd’hui. D’ailleurs, en
2012, une étude menée par l’American Alliance of Museums montre que les audioguides, les
QR codes ou les visites audio sur smartphone sont largement appréciés par le public,  bien
que seulement 4 musées sur 10 ne proposent ce type de services.

En somme, ce qui fait la force de l’audioguide, c’est sa manière d’accompagner sans
s’imposer. Il respecte le rythme de chaque visiteur, propose un discours, mais laisse toujours
la liberté de passer une œuvre, de revenir plus tard, de choisir ce que l’on souhaite entendre.
En effet, le format de l’audioguide est idéal pour le musée : il est mobile, donc suit le visiteur
dans l’espace ; il est audio, donc ne détourne pas l’attention visuelle de l’œuvre. Ce point est
important : dans un lieu où tout repose sur le regard porté sur les objets, l’audio apparaît
comme le support le moins intrusif.

Cela nous rappel forcément les propos de Denis Guedj sur les enjeux de la médiation : "le
problème du médiateur, c'est le médiateur", et bien ici, l'audioguide est surement la solution
qui se rapproche le plus de la discrétion et de la disparition du dispositif, à condition de ne
pas utiliser l'aspect visuel de l'objet. Cette condition fait partie des points de vigilance à
surveiller. Il ne faut pas que le discours ou le format d'utilisation de l’audioguide prenne le
dessus sur l’œuvre elle-même. Le risque serait alors de déplacer l’attention vers l’appareil
Article de mémoire - DIMI - 2024/2025                                                                                  24


plutôt que vers l’objet exposé. Dans ce cas, le rôle de médiation perd son sens. Ce problème
se retrouve par exemple avec les dispositifs immersifs qui absorbent complètement l'attention
des visiteurs au détriment des œuvres. L’innovation n’a d’intérêt que si elle sert l’objet, si elle
renforce le lien entre le visiteur et l’œuvre, et non si elle le remplace.

Enfin, il faut aussi penser à l’accessibilité numérique. Toutes les générations ne sont pas à
l’aise avec les nouvelles technologies. Les écrans tactiles, les QR codes ou les interfaces
complexes peuvent freiner certains visiteurs, notamment les plus âgés. L’enjeu est donc de
proposer des outils simples, intuitifs, et toujours facultatifs, pour rester dans une logique de
choix et de confort pour tous.

Aujourd’hui, l’audioguide continue d’évoluer, en s’adaptant aux usages numériques et aux
attentes des publics. On assiste même à une forme de transition : l’arrivée des applications
mobiles permet de remplacer les appareils prêtés par les musées, ce qui réduit la gestion
logistique. Le public peut désormais utiliser son propre téléphone. Depuis une dizaine
d’années, les musées se sont progressivement emparés de ce format. Déjà en 2012, une étude
de la Knight Foundation
## 15
montrait que 49 % des musées américains et 37 % des musées
britanniques proposaient une application mobile. En France, on en comptait près de 400 en
2015, un chiffre qui montre bien la place croissante et inévitable de l'application mobile
comme dispositif de médiation.

L’application mobile offre, en théorie, des possibilités très intéressantes. Elle est accessible,
personnalisable, et surtout très flexible : on peut l’utiliser pendant la visite, mais aussi avant
ou après, en fonction de ses besoins. Pourtant, dans la pratique, cette personnalisation reste
très peu mise en œuvre. On retrouve souvent les mêmes parcours, les mêmes fiches infos, les
mêmes schémas pour tout le monde. L’accessibilité est parfois mieux pensée, mais pas
toujours, et le potentiel réel de l’outil reste largement sous-exploité.

Pour les visiteurs, l’application mobile a tout pour plaire. Elle entraîne la curiosité, promet
une visite plus libre et personnalisée. Elle attire par son côté ludique, donne l’impression
## 15
Knight Foundation. (2020). Digital Readiness and Innovation in Museums Report. (traitement assisté par
Perplexity AI)
Article de mémoire - DIMI - 2024/2025                                                                                  25


qu’on pourra mieux comprendre, sans surcharge d’informations. Même ceux peu à l’aise avec
le numérique y voient souvent une opportunité de vivre une expérience différente, plus
légère, plus "moderne
## 16
". Dans les faits, cette promesse séduit rarement sur la durée. L'outil
attire... mais déçoit. Très vite, les limites techniques prennent le dessus : problèmes de
compatibilité avec certains téléphones, interfaces mal pensées, bugs, lenteurs. Ce qui devait
être fluide devient un frein. L’enthousiasme du départ laisse place à la frustration. Beaucoup
de visiteurs téléchargent l’application "pour voir", par simple curiosité... puis l’abandonnent
au bout de quelques minutes
## 17
. Le paradoxe est là : on a entre les mains un outil plein de
potentiel, mais trop rarement bien conçu pour tenir ses promesses.

C) Questionnement et perspectives d'amélioration pour la médiation
mobile

L'application mobile a su trouver sa place dans le paysage muséal, mais elle reste encore
aujourd’hui en retrait par rapport à d’autres dispositifs numériques. Selon certaines études, les
outils présents directement dans les salles d’exposition (bornes, écrans interactifs, panneaux
numériques) sont en réalité plus utilisés que les audioguides... et encore plus que les
applications mobiles
## 18
. Ce constat montre bien que, malgré l’évolution des technologies, les
publics cherchent avant tout à être accompagnés par le musée lui-même. On peut y voir un
besoin de légitimité dans le discours, mais aussi, comme le souligne Anne Joncherie, un
sentiment fréquent de ne pas "avoir les codes", ou de ne pas être assez compétent face à des
œuvres patrimoniales.

Pourtant, lorsqu’elle est bien conçue, l’application mobile peut renforcer l’attention du
visiteur, encourager son engagement cognitif, et même favoriser une forme d’évasion
mentale
## 19
. Son attractivité visuelle et la qualité de son contenu sont deux leviers essentiels à
activer lors de sa conception. L’application ne doit pas être pensée comme un simple outil de
## 19
Ben Nasr, I., Hallem, Y., & De Carli, A. (2018). Apports de l’application mobile aux connaissances et à
l’évasion mentale induites par l’expérience muséale : Rôle de l’attention focalisée et de la distorsion du temps.
## Management & Avenir, 99(1), 191–213.
## 18
GECE. (2024). Baromètre 2024 des publics des musées et des lieux patrimoniaux. Agence GECE.
## 17
De nouveau “Quel est le rôle de l’application mobile dans la valorisation de l’expérience muséale”
## 16
Ben Nasr, I., Hallem, Y., & Lagier, J. (2017). Quel est le rôle de l’application mobile dans la valorisation de
l’expérience muséale ? Management & Avenir, 92(2), 87–108.
Article de mémoire - DIMI - 2024/2025                                                                                  26


communication ou une vitrine numérique, mais bien comme un prolongement de l’expérience
sur place, un support vivant, interactif, capable de guider sans enfermer.

Mais là encore, les retours sont partagés. Si certains apprécient la praticité du smartphone, sa
familiarité, et la possibilité d’une visite plus autonome, d’autres regrettent qu’il vienne
perturber l’attention ou nuire à l’immersion
## 20
. Il y a aussi des contraintes très concrètes :
batterie qui se vide trop vite, stockage saturé, qualité sonore moyenne... autant de détails
techniques qui peuvent nuire à l’expérience.

Globalement, deux tiers des visiteurs se disent satisfaits par l’offre d’application mobile. Un
quart aimerait même en voir davantage, en particulier chez les jeunes et les familles.
## 21
Il y a
donc une attente, mais aussi une exigence. Le numérique n’est pas un "plus" gadget : il doit
avoir du sens. Il faut éviter qu’il vienne parasiter et remplacer la relation oeuvres/visiteurs.
L’équilibre est délicat, mais essentiel : l’application doit enrichir l’expérience, pas la
détourner.

## 21
De nouveau “Baromètre 2024 des publics des musées et des lieux patrimoniaux”
## 20
De nouveau “Apports de l’application mobile...”
Article de mémoire - DIMI - 2024/2025                                                                                  27


## Conclusion

Ce travail d’état de l’art n’a pas, je le rappelle, vocation à apporter de réponses définitives
aux sujets évoqués. Il permet néanmoins de poser plusieurs constats sur l’évolution de la
médiation muséale en France. Loin d’être un sujet clos ou stable, la médiation culturelle
apparaît comme un domaine vivant, perpétuellement redéfini par les transformations des
publics, des technologies, et des attentes vis-à-vis des institutions. Ce que l’on appelait hier
"visite guidée" est aujourd’hui dilué dans une multitude de formats, de temporalités et de
supports. De la médiation humaine aux dispositifs immersifs, des cartels papier aux interfaces
interactives, l’offre est devenue plurielle, parfois trop.

Le numérique tient alors une place centrale dans la révolution en cours. Il est à la fois
catalyseur de nouvelles formes d’engagement et source de déséquilibres. Les dispositifs
numériques promettent une médiation plus souple, personnalisée, inclusive — mais ils
peinent encore à trouver un équilibre clair entre assistance et invisibilité. Et cette tension est
particulièrement visible dans le cas de l’application mobile, devenue ces dernières années le
support privilégié des musées pour dématérialiser la visite et rendre le contenu plus
accessible.

Et pourtant, en dépit des qualités qu’on lui prête sur le papier (accessibilité, souplesse
d’utilisation, richesse de contenu, et capacité à accompagner la visite avant et après)
l’application mobile ne parvient que rarement à convaincre pleinement dans la réalité du
terrain. Jugée trop accessoire par certains, trop intrusive par d’autres, elle souffre aussi d’un
manque d’implication émotionnelle. Les recherches mobilisées au fil de ce travail vont dans
le même sens : face aux outils plus traditionnels ou intégrés directement dans le parcours
d’exposition, l’application peine encore à trouver sa place dans les usages réels des visiteurs.

On pourrait penser que le problème vient de la technologie. Mais il semble plus juste de dire
qu’il s’agit d’un problème d’usage, d’expérience, et plus encore de posture : si la médiation
veut se faire discrète, l’interface ne peut pas accaparer l’attention. Si elle veut transmettre,
elle ne peut pas être fade. Si elle veut engager, elle ne peut pas rester passive.
Article de mémoire - DIMI - 2024/2025                                                                                  28



Il est donc nécessaire de prolonger ce travail en se concentrant plus spécifiquement sur ce
paradoxe : comment un outil aussi riche que l'application mobile peut-il échouer à
pleinement s'imposer comme une référence dans l'expérience muséale ? C'est cette question qui guide la suite de ce mémoire, à travers la problématique suivante :

*Entre la promesse d'une médiation accessible et la réalité d'un outil marginalement adopté, qu'est-ce qui, dans la conception ou dans le contexte, empêche l'application mobile audioguide de tenir son rôle ?*

Plusieurs pistes d'analyse structurent l'investigation qui suit :
- **Le poids du dispositif** : certaines interfaces sont trop visibles, trop complexes, et
parasitent la visite au lieu de l'accompagner. Cela pose la question d'un retour à une
médiation plus sonore, plus discrète, inspirée de l'audioguide traditionnel.
- **La qualité du contenu et la vulgarisation** : le contenu est souvent linéaire et peu incarné. La tension entre vulgarisation et rigueur scientifique, explorée plus haut, se traduit par des audioguides au ton neutre, validés par des conservateurs rarement au contact du public. Le contenu gagnerait à injecter plus d'émotion, de rythme, voire de narration vivante.
- **Le contexte d'usage** : le smartphone, objet du quotidien, entre en concurrence avec lui-même au musée. Notifications, photos, messages : l'attention est fragmentée avant même que l'audioguide ne démarre.
- **Les contraintes institutionnelles** : les musées n'ont pas toujours les moyens de développer et maintenir une application de qualité. Les cycles technologiques rapides rendent les investissements vite obsolètes.

Ces hypothèses ne prennent sens que confrontées au terrain. Les parties suivantes de ce mémoire les mettent à l'épreuve du réel, à travers l'analyse d'entretiens, d'un questionnaire, et d'un corpus d'applications existantes.










Article de mémoire - DIMI - 2024/2025                                                                                  31


## Bibliographie / Webographie
- Ben Nasr, I., Hallem, Y., & De Carli, A. (2018). Apports de l’application mobile aux
connaissances et à l’évasion mentale induites par l’expérience muséale : Rôle de
l’attention focalisée et de la distorsion du temps. Management & Avenir, 99(1),
191–213. https://doi-org.ezproxy.univ-paris13.fr/10.3917/mav.099.0191
- Ben Nasr, I., Hallem, Y., & Lagier, J. (2017). Quel est le rôle de l’application mobile
dans la valorisation de l’expérience muséale ? Management & Avenir, 92(2), 87–108.
https://doi.org/10.3917/mav.092.0087
- Blondeau, V., Meyer-Chemenska, M., & Schmitt, D. (2020). Le design de
l’expérience au musée : nouvelles perspectives de recherche. Culture & Musées, 35.
https://doi.org/10.4000/culturemusees.4637
- Caillet, É. (1995). À l’approche du musée : la médiation culturelle. Presses
Universitaires de Lyon.
https://books.google.fr/books?hl=fr&lr=&id=nJhYDwAAQBAJ
- Deshayes, S. (2004). L’usage des supports mobiles au musée, des audioguides
classiques au multimédia nomade. Communication présentée à ICHIM 04 - Digital
## Culture & Heritage / Patrimoine & Culture Numérique. Archives & Museum
## Informatics Europe.
https://www.archimuse.com/publishing/ichim04/1799_Deshayes.pdf
- Ducongé, G. (2024). L’audioguide de musées à l’ère post-COVID : un dispositif
d'aide à la visite (toujours) incontournable ? [Mémoire].
https://www.academia.edu/download/118073409/DUCONGE_L_audioguide_de_mus
ees_a_l_ere_post_Covid_Memoire_VLite.pdf
- France Culture. (2021). Podcast « Histoire de musées ».
https://www.radiofrance.fr/franceculture/podcasts/serie-histoire-de-musees
- GECE. (2024). Baromètre 2024 des publics des musées et des lieux patrimoniaux.
Agence GECE.
- Gentès, A., & Jutant, C. (2012). Nouveaux médias au musée : Le visiteur équipé.
Culture & Musées, 19, 67–91. https://doi.org/10.3406/pumus.2012.1648
- Jarrier, E., & Bourgeon-Renault, D. (2020). L’enrichissement de l’expérience de visite
muséale par l’utilisation d’outils interactifs de médiation. Décisions Marketing, 97(1),
87–101. https://doi.org/10.7193/DM.097.87.101
Article de mémoire - DIMI - 2024/2025                                                                                  32


- Jarrier, E., Bourgeon-Renault, D., & Belvaux, B. (2019). Une mesure des effets de
l’utilisation d’un outil numérique sur l’expérience de visite muséale. Management &
## Avenir, 108(2), 107–126.
https://doi-org.ezproxy.univ-paris13.fr/10.3917/mav.108.0107
- Jannen Contreras Vargas, et al. (2016). Estudios sobre públicos y museos. Volumen I.
Públicos y museos: ¿Qué hemos aprendido ? Escuela Nacional de Conservación,
Restauración y Museografía (ENCRyM-INAH).
https://ilamdocs.org/blob/Publicosymuseos-vol-I.pdf?fieldname=attachment&classna
me=Document&record=2526
 Source trouvée et traitement assisté par Perplexity AI.
- Jonchery, A. (2024). Introduction à la médiation et aux publics. Cours à l’École du
Louvre, communication orale.
- Knight Foundation. (2020). Digital Readiness and Innovation in Museums Report.
https://knightfoundation.org/wp-content/uploads/2020/10/Digital-Readiness-and-Inno
vation-in-Museums-Report.pdf
 Traitement assisté par Perplexity AI.
- Schmitt, D. (2014). Vers une remédiation muséale à partir de l'expérience située des
visiteurs. Les Enjeux de l'information et de la communication.
https://hal.science/hal-01550561v1/document

Article de mémoire - DIMI - 2024/2025                                                                                  33


Liste des figures


Figure 1 : Le Diorama du village Pequot, Mashantucket Pequot Museum and Research
## Center. © Noémie Étienne


Figure 2 : Bateau viking et scène de La Légende de Saint Philibert (1997-2004). © Wikipédia


Article de mémoire - DIMI - 2024/2025                                                                                  34




Figure 3 : Visiteurs utilisants le tout premier dispositif audioguide au Stedelijk Museum, 1952
©  Nederlands Instituut voor Beeld en Geluid

Article de mémoire - DIMI - 2024/2025                                                                                  35