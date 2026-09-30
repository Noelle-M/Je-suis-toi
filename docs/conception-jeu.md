# Je suis toi

## Document de conception du jeu

**Je suis toi** est un jeu d’enquête interactif en temps réel dans lequel le joueur incarne un enquêteur dont il choisit lui-même le nom. Le jeu repose sur une enquête vivante, des personnages persistants, des informations partielles, des contradictions et un tableau d’enquête que le joueur construit lui-même.

Le joueur ne reçoit jamais la vérité sous forme de missions successives. Il doit observer, questionner, comparer, revenir sur ses découvertes et décider lui-même quelles pistes méritent d’être poursuivies.

---

## Sommaire

1. [Principe général](#1-principe-général)
2. [Le personnage principal](#2-le-personnage-principal)
3. [Le temps réel](#3-le-temps-réel)
4. [La liberté d’enquête](#4-la-liberté-denquête)
5. [Les personnages](#5-les-personnages)
6. [Les interrogatoires](#6-les-interrogatoires)
7. [Les lieux](#7-les-lieux)
8. [Le tableau d’enquête](#8-le-tableau-denquête)
9. [Les preuves et les informations](#9-les-preuves-et-les-informations)
10. [La cohérence des personnages](#10-la-cohérence-des-personnages)
11. [La progression d’une enquête](#11-la-progression-dune-enquête)
12. [Les déplacements internationaux](#12-les-déplacements-internationaux)
13. [La résolution](#13-la-résolution)
14. [Les règles de crédibilité](#14-les-règles-de-crédibilité)
15. [Architecture narrative de l’affaire 01](#15-architecture-narrative-de-laffaire-01)
16. [Arborescence du projet](#16-arborescence-du-projet)

---

## 1. Principe général

Chaque affaire commence par un événement qui paraît suffisamment ordinaire pour que l’institution ne considère pas immédiatement nécessaire de mobiliser d’importants moyens. Un détail attire pourtant l’attention du personnage principal. Il ne s’agit pas nécessairement d’un indice spectaculaire, mais d’une incohérence concrète qui ne correspond pas à l’explication la plus évidente.

Le joueur décide de poursuivre cette piste malgré les réticences de sa hiérarchie. Son personnage n’est ni violent ni hors-la-loi. Son caractère rebelle repose sur son obstination, sa curiosité et sa tendance à revenir sur les détails que les autres considèrent comme secondaires.

La règle narrative centrale est que le joueur enquête parce qu’il refuse de considérer une explication comme suffisante lorsqu’elle laisse des éléments inexpliqués.

L’affaire doit donner l’impression d’exister indépendamment du joueur. Les autres personnages travaillent, se déplacent, prennent des décisions, attendent des résultats, commettent des erreurs et poursuivent leurs propres objectifs.

Le joueur ne sait jamais au départ qui est réellement son allié, qui lui fait perdre du temps et qui lui cache volontairement quelque chose.

---

## 2. Le personnage principal

Le joueur choisit le nom de son enquêteur.

Le personnage est un officier de police judiciaire intégré à un groupe d’enquête criminelle. Il travaille avec d’autres policiers, des techniciens de police scientifique, des médecins légistes, des analystes et des magistrats selon les besoins de l’enquête.

Son caractère est volontairement indépendant. Il peut contester une conclusion, demander une nouvelle vérification, revenir vers un témoin ou défendre une piste que ses collègues considèrent comme improbable.

Cette indépendance ne lui donne cependant pas tous les pouvoirs. Il doit respecter le cadre judiciaire, demander les autorisations nécessaires et travailler avec les professionnels compétents. Il ne manipule pas lui-même les éléments réservés à la police scientifique et ne réalise pas les actes qui relèvent du médecin légiste.

Le joueur doit donc avoir la sensation d’un enquêteur libre dans son raisonnement, mais inscrit dans une institution réelle.

---

## 3. Le temps réel

Le temps du jeu suit le temps réel.

Vingt-quatre heures réelles correspondent à vingt-quatre heures dans l’univers de l’enquête. Lorsque le joueur quitte le jeu pendant plusieurs heures, plusieurs heures s’écoulent également dans l’affaire.

Les personnages possèdent leurs propres horaires et leurs disponibilités. Les résultats d’analyses arrivent après un délai cohérent avec leur nature. Un témoin peut rappeler plus tard, un rendez-vous peut être fixé au lendemain et un lieu peut n’être accessible qu’à certaines heures.

Le téléphone de l’enquêteur peut recevoir des SMS, des appels, des messages vocaux, des photographies, des rapports et des résultats pendant son absence.

Le temps réel ne doit cependant jamais bloquer définitivement l’enquête. Lorsqu’un événement important se produit pendant l’absence du joueur, l’information doit rester récupérable à son retour.

L’objectif est de créer une enquête qui accompagne réellement le joueur pendant plusieurs jours. Il doit pouvoir quitter le jeu avec une question en tête et avoir envie d’y revenir parce qu’une hypothèse lui est venue entre-temps.

---

## 4. La liberté d’enquête

Le jeu ne doit pas être construit comme une succession de missions imposant une seule action correcte.

Le joueur peut choisir l’ordre dans lequel il explore les pistes disponibles. Il peut retourner sur un lieu, convoquer un témoin, reprendre une audition, présenter une nouvelle preuve à une personne déjà interrogée, demander une analyse, rechercher une information administrative ou attendre un résultat.

Certaines actions peuvent ouvrir de nouvelles possibilités tandis que d’autres peuvent simplement confirmer qu’une piste ne mène nulle part.

Le jeu doit accepter qu’un joueur comprenne une partie de la vérité plus tôt que prévu. Il ne doit pas lui imposer artificiellement d’attendre une mission avant de pouvoir formuler une hypothèse.

En revanche, comprendre une hypothèse ne signifie pas automatiquement pouvoir la prouver. Le joueur doit disposer des éléments nécessaires pour transformer son intuition en conclusion défendable.

---

## 5. Les personnages

Les personnages constituent une partie essentielle du gameplay.

Ils ne sont pas des distributeurs d’indices. Chacun possède une fonction, une personnalité, une histoire, des connaissances, des limites et des objectifs qui lui sont propres.

Un personnage peut être réellement sympathique tout en cachant quelque chose. Un personnage peut être désagréable sans avoir le moindre rapport avec le crime. Un collègue peut contester le joueur simplement parce qu’il pense que sa piste est mauvaise. Un témoin peut se tromper sans mentir.

Les personnages importants doivent revenir au cours de l’enquête. Ils peuvent fournir une information, être recontactés plusieurs jours plus tard, corriger un souvenir, apporter un résultat, contredire une hypothèse ou demander quelque chose au joueur.

La continuité est essentielle. Une personne qui a déjà parlé avec l’enquêteur doit se souvenir de ce qui a été dit. Une nouvelle preuve peut modifier sa réponse, mais elle ne doit pas lui faire oublier une conversation précédente.

---

## 6. Les interrogatoires

Lorsqu’un personnage est interrogé, le joueur entre dans une véritable scène d’audition.

Il peut poser ses questions au clavier ou au microphone, présenter une preuve, revenir sur une réponse, confronter deux déclarations, interrompre l’entretien ou convoquer à nouveau la personne plus tard.

L’interrogatoire doit être libre dans sa formulation. Le joueur ne choisit pas uniquement parmi trois questions préécrites.

L’intelligence artificielle peut être utilisée pour permettre des conversations naturelles, mais elle doit rester enfermée dans une bible stricte. Chaque personnage possède des informations qu’il connaît, des informations qu’il ignore, des choses qu’il croit vraies, des choses qu’il veut cacher et des choses qu’il refuse de révéler.

L’IA ne doit jamais inventer un fait susceptible de modifier la vérité de l’affaire.

---

## 7. Les lieux

Les lieux sont représentés par de belles scènes 2D fixes en haute définition.

Le joueur peut changer de vue, zoomer, examiner certains détails, rechercher des objets et interroger les personnes présentes.

Le choix de scènes fixes permet de concentrer les ressources sur la qualité visuelle, l’ambiance, la lumière, les détails et la composition plutôt que sur une production 3D lourde.

Chaque lieu doit avoir une fonction narrative réelle. Un endroit peut contenir une preuve, permettre une rencontre, révéler une habitude ou simplement fournir un élément de contexte qui prendra son sens plus tard.

---

## 8. Le tableau d’enquête

Le tableau d’enquête est l’un des éléments signature de **Je suis toi**.

Le joueur y rassemble les portraits, photographies, lieux, documents, objets, témoignages, rapports et événements qu’il découvre.

Il organise librement les éléments et crée lui-même les liens entre eux. Les liens peuvent être nommés et différenciés visuellement.

Le jeu ne doit pas relier automatiquement les preuves importantes. Le joueur doit pouvoir faire une association qui n’a pas encore été explicitement confirmée par l’enquête.

Le tableau sert également de mémoire externe. Le joueur peut y inscrire ses propres hypothèses et conserver des pistes qui se sont révélées fausses.

À la fin d’une affaire, le tableau doit permettre de comprendre le raisonnement du joueur et la manière dont il a progressivement reconstruit l’histoire.

---

## 9. Les preuves et les informations

Une preuve n’a pas nécessairement une signification unique au moment où elle est découverte.

Un objet peut sembler banal avant qu’un témoignage lui donne une autre importance. Une photographie peut confirmer une hypothèse plusieurs jours après sa découverte. Une contradiction dans une audition peut rester inexpliquée jusqu’à l’arrivée d’un document.

Les preuves doivent donc pouvoir changer de sens sans changer de nature.

Le jeu doit distinguer les preuves matérielles, les documents, les données numériques, les résultats scientifiques, les témoignages et les hypothèses du joueur.

Une hypothèse du joueur n’est jamais automatiquement transformée en fait.

---

## 10. La cohérence des personnages

Chaque personnage possède une fiche de vérité qui définit son identité, son rôle, ce qu’il sait, ce qu’il ignore, ce qu’il croit, ce qu’il cache et ce qu’il peut révéler.

Les personnages ne doivent jamais connaître des informations uniquement parce qu’elles seraient utiles au joueur.

Les mensonges doivent avoir une raison. Un personnage peut mentir pour protéger quelqu’un, pour préserver sa réputation, parce qu’il a commis une faute sans rapport avec le meurtre ou parce qu’il est directement impliqué.

Les comportements hostiles ne constituent jamais à eux seuls une preuve de culpabilité. À l’inverse, une personne très serviable peut être dangereuse.

Cette règle permet notamment de créer des personnages comme des collègues irritants mais innocents, des supérieurs prudents, des témoins difficiles à convaincre ou des personnes très sympathiques qui cachent une information importante.

---

## 11. La progression d’une enquête

Une affaire doit comporter plusieurs niveaux de compréhension.

Le joueur commence par une situation concrète et limitée. Il découvre ensuite des anomalies, formule des hypothèses, rencontre des contradictions et élargit progressivement le périmètre de ses recherches.

Une révélation importante doit modifier la lecture d’éléments déjà rencontrés.

Le joueur ne doit pas recevoir toutes les réponses dans l’ordre prévu par les scénaristes. Il peut découvrir une information familiale avant une information criminelle, comprendre une partie du mobile avant de connaître l’identité d’un suspect ou remarquer une contradiction plusieurs jours avant d’en comprendre la cause.

L’enquête doit donc être conçue selon deux niveaux distincts. La vérité complète est fixée à l’avance et la découverte par le joueur peut suivre plusieurs chemins.

Chaque affaire possède néanmoins des points de passage indispensables pour que la résolution soit possible.

---

## 12. Les déplacements internationaux

Lorsqu’une affaire implique plusieurs pays, le personnage principal ne peut pas simplement agir dans un autre territoire comme s’il y exerçait sa propre compétence.

Les déplacements sont intégrés à l’enquête dans un cadre de coopération avec les autorités locales.

Dans l’affaire 01, le personnage principal commence son enquête à Poitiers. Lorsque les éléments conduisent vers les États-Unis, il se rend sur place pour poursuivre les auditions et les vérifications nécessaires.

Il travaille avec une policière américaine, **Detective Laura Bennett**, du Greenwich Police Department. Elle constitue son interlocutrice locale et facilite les démarches relevant des autorités américaines.

Le personnage principal interroge notamment Elena, les collaborateurs d’Alexander et les personnes qui peuvent apporter des informations sur sa vie aux États-Unis.

Il revient ensuite en France pour poursuivre l’enquête depuis Poitiers. Laura reste en contact avec lui et devient essentielle à la résolution finale lorsque l’événement concernant Mikhail se produit aux États-Unis.

Le déplacement international doit donc modifier réellement la manière de travailler du joueur et enrichir l’enquête, sans devenir un simple changement de décor.

---

## 13. La résolution

La résolution ne consiste pas simplement à demander au joueur de sélectionner un coupable dans une liste.

Lorsqu’il estime avoir compris l’affaire, le joueur doit pouvoir présenter sa théorie. Il doit identifier la victime, expliquer les événements principaux, établir les liens entre les personnages et présenter les preuves qui soutiennent ses conclusions.

Le joueur peut parvenir à une hypothèse avant de posséder toutes les preuves nécessaires. Le jeu doit lui permettre de continuer à enquêter plutôt que de lui donner automatiquement raison.

La résolution finale confronte son raisonnement à la vérité de l’affaire.

Le dernier élément déterminant doit confirmer une hypothèse déjà construite par le joueur plutôt que lui fournir toute la solution au dernier moment.

Dans l’affaire 01, cette logique conduit au grand retournement biométrique. Le personnage principal est rentré en France après son déplacement aux États-Unis et reste en contact avec Laura Bennett. Mikhail est alors arrêté aux États-Unis après avoir conduit en état d’ivresse. Lors de la procédure, ses empreintes sont relevées et la contradiction avec l’identité d’Alexander Beaumont apparaît.

Le joueur français n’arrête donc pas Mikhail. Il reçoit depuis les États-Unis la preuve qui permet de confirmer l’hypothèse qu’il a construite.

---

## 14. Les règles de crédibilité

La crédibilité prime toujours sur l’effet spectaculaire.

Les policiers doivent agir dans le cadre de leurs fonctions. Le personnage principal ne retire pas lui-même les chaussures d’un cadavre pour découvrir un indice. Les éléments de la scène sont pris en charge par les professionnels compétents.

Le médecin légiste peut reconnaître un visage, signaler une anomalie médicale ou demander qu’un élément soit approfondi, mais une reconnaissance visuelle ne remplace pas une identification formelle.

Les techniciens de police scientifique réalisent les constatations, prélèvements et analyses relevant de leur domaine.

Les magistrats interviennent lorsque leur décision ou leur autorisation est nécessaire.

Les policiers étrangers restent compétents sur leur propre territoire.

Les délais doivent être crédibles. Une analyse ne doit pas apparaître instantanément uniquement parce que le joueur en a besoin. Une audition importante peut nécessiter une prise de rendez-vous. Un document peut demander une recherche administrative.

La fiction peut simplifier certaines procédures pour préserver le plaisir de jeu, mais elle ne doit jamais reposer sur un comportement professionnel manifestement invraisemblable.

---

## 15. Architecture narrative de l’affaire 01

La première enquête porte sur **Alexander Beaumont**, homme d’affaires américain extrêmement riche retrouvé mort dans une ruelle de Poitiers sous l’apparence d’un homme précaire.

La première identité fournie aux enquêteurs est volontairement trompeuse. Dans le studio, ils trouvent le véritable passeport de **Mikhail Sokolov**, placé là par Elena et Mikhail. Ils pensent ainsi que le corps est celui de Mikhail et que l’affaire peut s’arrêter à cette identification.

Le joueur refuse cette conclusion parce que plusieurs détails ne correspondent pas. Les chaussures sont coûteuses et anciennes. Bébel confirme qu’il les a toujours vues sur Daniel. Le bouton de manchette renvoie vers la famille Beaumont. Élise reconnaît le visage d’Alexander dans le cadre de son travail médico-légal, tout en sachant qu’une ressemblance ne constitue pas une identification.

Pendant que l’enquête progresse, le joueur découvre qu’Alexander Beaumont continue officiellement à vivre aux États-Unis. Il apparaît dans des interviews, voyage, participe à des séminaires et travaille pour le Beaumont Group.

Les recherches familiales révèlent ensuite l’existence de **Peter Beaumont**, frère jumeau d’Alexander, devenu **Mikhail Sokolov** après le départ de leur mère en Russie. Alexander ignore totalement l’existence de son frère et croit que sa mère est morte en couches.

Mikhail a découvert Alexander par hasard à la télévision dans un hôtel en Russie. Après la mort de sa mère, sa grand-mère Galina lui a révélé la vérité familiale. Sa jalousie envers la fortune et la vie de son frère l’a progressivement conduit à vouloir prendre sa place.

Elena, future épouse d’Alexander, est en réalité la compagne de Mikhail. Elle entre dans la vie d’Alexander, gagne sa confiance et transmet pendant des années à Mikhail les informations nécessaires pour reproduire son frère.

**Ethan Parker**, directeur de la sûreté du Beaumont Group et proche d’Alexander depuis plus de quinze ans, devient leur complice interne. Il utilise sa position pour donner une apparence professionnelle aux menaces qui constituent la campagne de peur.

Cette campagne pousse Alexander à disparaître volontairement. Il vient en France, s’installe à Poitiers sous l’identité de Daniel Morel et reçoit régulièrement de l’argent liquide.

Avant de s’installer définitivement dans cette nouvelle vie, Alexander entre normalement en France avec son véritable passeport américain. Après son arrivée, Elena lui remet le véritable passeport de Mikhail en lui faisant croire qu’il s’agit d’un document de couverture. Alexander ne sait pas qu’il possède le véritable passeport de son frère.

Mikhail possède de son côté le véritable passeport d’Alexander et commence à occuper progressivement sa place aux États-Unis.

Alexander est privé de télévision, d’Internet et de ses moyens de communication habituels. Il est également surveillé en France afin de maintenir chez lui la conviction qu’il est toujours recherché.

Après plusieurs mois d’isolement, sa situation devient insupportable. Il veut rentrer aux États-Unis et contacte Elena pour lui annoncer sa décision.

Le point de rupture intervient lorsqu’il réussit à semer temporairement les hommes qui le surveillent et se rend dans un kiosque de la gare de Poitiers. Il y découvre un exemplaire récent du **TIME** présentant son propre visage alors qu’il vit caché en France.

Il comprend qu’un autre homme utilise son identité.

Les hommes qui le surveillent le retrouvent dans le kiosque. Elena et Mikhail comprennent qu’Alexander est désormais capable de révéler la substitution et décident de le faire éliminer.

Le corps est ensuite mis en scène comme celui de Daniel Morel, avec une forte présence d’alcool destinée à orienter les premières interprétations.

L’enquête française progresse ensuite jusqu’aux États-Unis. Le personnage principal s’y rend avec l’appui de Detective Laura Bennett, interroge Elena, les collaborateurs d’Alexander et les personnes susceptibles de connaître les habitudes du dirigeant. Il revient ensuite à Poitiers et poursuit l’enquête avec ses collègues français.

La preuve finale arrive par l’intermédiaire de Laura Bennett. Mikhail est arrêté aux États-Unis après avoir conduit en état d’ivresse. Lors de la procédure, ses empreintes sont relevées et révèlent qu’il est bien Mikhail Sokolov alors qu’il vit publiquement sous l’identité d’Alexander Beaumont.

Cette découverte permet de démontrer qu’il existe deux hommes et que le corps français n’est pas celui de Mikhail. Les éléments génétiques et les archives familiales permettent alors d’établir le lien entre les deux hommes et de confirmer leur gémellité.

La vérité complète de la machination est ensuite reconstruite par le joueur à partir de l’ensemble des éléments recueillis.

L’affaire doit conserver une distinction stricte entre ce que nous savons en tant que concepteurs et ce que le joueur sait à chaque étape. Le joueur ne doit jamais recevoir une information uniquement parce qu’elle est nécessaire au scénario.

---

## 16. Arborescence du projet

Le dépôt GitHub doit séparer le fonctionnement général du jeu et les différentes enquêtes.

```
Je-suis-toi/
│
├── README.md
│
├── docs/
│   ├── conception-jeu.md
│   │
│   └── enquetes/
│       └── 01-alexander/
│           ├── README.md
│           ├── point-01.md
│           ├── point-02.md
│           ├── point-03.md
│           ├── point-04.md
│           ├── point-05.md
│           ├── point-06.md
│           ├── point-07.md
│           ├── point-08.md
│           ├── point-09.md
│           ├── point-10.md
│           ├── point-11.md
│           ├── point-12.md
│           ├── point-13.md
│           ├── point-14.md
│           ├── point-15.md
│           ├── point-16.md
│           ├── point-17.md
│           ├── point-18.md
│           ├── point-19.md
│           ├── point-20.md
│           ├── point-21.md
│           ├── point-22.md
│           ├── point-23.md
│           ├── point-24.md
│           ├── point-25.md
│           ├── point-26.md
│           ├── point-27.md
│           ├── point-28.md
│           └── point-29.md
│
└── src/
    └── ...
```

### Rôle des dossiers

**`docs/conception-jeu.md`** contient les règles générales de **Je suis toi**. Il décrit le fonctionnement du temps réel, les interrogatoires, le tableau d’enquête, les personnages, les lieux, la logique de résolution et les règles de crédibilité.

**`docs/enquetes/01-alexander/`** contient uniquement la bible narrative de la première affaire. Les vingt-neuf points détaillent la vérité de l’affaire, les personnages, les preuves, la progression et la résolution.

**`src/`** contiendra ensuite le code du jeu. Le code ne doit pas devenir la source de vérité narrative. Les faits de l’enquête doivent rester documentés dans la bible afin que le moteur de jeu et les systèmes d’IA puissent s’y référer sans réinventer l’histoire.

La conception du jeu doit rester indépendante de l’affaire Alexander afin que les futures enquêtes puissent utiliser le même moteur avec leurs propres personnages, lieux, preuves, chronologies et vérités cachées.
