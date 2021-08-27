# Apprenez par vous-même la science informatique

> Ce document est une traduction de [TeachYourselfCS](https://teachyourselfcs.com/), écrit par [Ozan Onay](https://twitter.com/oznova_) et [Myles Byrne](https://twitter.com/quackingduck).

> Ceci est une traduction de la version originale mise à jour en mai 2020.

Si vous êtes un ingénieur autodidacte ou que vous avez suivi une formation accélérée, vous vous devez d'apprendre la science informatique.
Heureusement, vous pouvez vous instruire dans ce domaine sans y passer des années ni dépenser une petite fortune dans un diplôme 💸.

Si les ressources disponibles sont nombreuses, toutes ne se valent pas.
Et vous n'avez pas besoin d'encore une autre liste de "200+ cours en ligne gratuits".
Vous avez besoin de réponses aux questions suivantes:

- **Quelles disciplines** apprendre, et pourquoi ?
- Quel est **le meilleur livre ou la meilleure série de vidéos de cours** pour chacune de ces disciplines ?

Ce guide est notre tentative de répondre définitivement à toutes ces questions.

## En bref

Étudiez l'ensemble des neufs disciplines suivantes approximativement dans le même ordre à l'aide du manuel ou des vidéos conseillées (idéalement les deux).
Comptez 100 à 200 heures pour chaque sujet, puis revoyez vos préférés tout au long de votre carrière 🚀.

| Domaine | Pourquoi l'étudier ? | Livre | Vidéos |
| --------| -------------------- | ----- | ------ |
| **[Programmation](#Programmation)** | Ne soyez pas la personne qui n'a "jamais vraiment bien compris" quelque chose comme la récursion. | _Structure and Interpretation of Computer Programs_ | Berkeley CS 61A par Brian Harvey|
| **[Architecture des ordinateurs](#Architecture-des-ordinateurs)** | Si vous n'avez pas une représentation mentale solide de la manière dont fonctionne un ordinateur, toutes vos abstractions de haut niveau en seront fragilisées. | _Computer Systems: A Programmer's Perspective_ | Berkeley CS 61C|
| **[Algorithmes et structures de données](#Algorithmes-et-structures-de-données)** | Si vous ne savez pas comment utiliser des structures de données omniprésentes, comme des piles, des queues, des arbres ou des graphes, alors vous ne serez pas en mesure de résoudre des problèmes difficiles. | _The Algorithm Design Manual_ | Les cours de Steven Skiena |
| **[Mathématiques pour l'informatique](#Mathématiques-pour-l'informatique)** | La science informatique est fondamentalement une branche dérivée des mathématiques appliquées, par conséquent apprendre les mathématiques vous donnera un avantage compétitif. | _Mathematics for Computer Science_ | MIT 6.042J par Tom Leighton |
| **[Système d'exploitation](#Système-d'exploitation)** | La plupart du code que vous écrivez est exécutée par un système d'exploitation donc vous devriez savoir comment celui-ci interagit. | _Operating Systems: Three Easy Pieces_ | Berkeley CS 162 |
| **[Réseaux informatiques](#Réseaux-informatiques)** | Internet s'est avéré être une grosse problématique: comprenez comment il fonctionne pour déployer son plein potentiel. | _Computer Networking: A Top-Down Approach_ | Stanford CS 144 |
| **[Bases de données](#Bases-de-données)** | Les données sont au coeurs des programmes les plus importants, or peu de personnes comprennent comment les systèmes de bases de données fonctionnent réellement. | _Readings in Database Systems_ | Berkeley CS 186 par Joe Hellerstein |
| **Langages et compilateurs** | Si vous comprenez comment les langages et les compilateurs fonctionnent, votre code en sera meilleur et il vous sera plus aisé d'apprendre de nouveaux langages. | _Crafting Interpreters_ | Le cours d'Alex Aiken sur edX |
| **Systèmes distribués** | De nos jours, la plupart des systèmes sont distribués. | _Designing Data-Intensive Applications_ de Martin Kleppmann | MIT 6.824|

## C'est toujours trop ?

Si vous vous sentez débordés à la perspective d'étudier seul neuf disciplines pendant plusieurs années, nous vous conseillons de vous concentrer uniquement sur deux livres : _Computer Systems: A Programmer's Perspective_ et _Designing Data-Intensive Applications_.
D'expérience, ces deux livres fournissent un retour sur le temps investi incroyablement payant, en particulier pour les ingénieurs autodidactes et les personnes qui ont suivi une formation accélérée travaillant sur des applications en réseau.
Ils peuvent également servir de "drogue d'initiation", vous ouvrant ainsi la porte aux autres sujets et ressources listées ci-dessus.

## Pourquoi apprendre la science informatique ?

Il y a deux types d'ingénieurs: ceux qui comprennent la science informatique suffisamment bien pour effectuer un travail audacieux et innovant, et ceux qui s'en sortent parce qu'ils sont familiers avec quelques outils de haut niveau.
Les deux se font appeler ingénieurs informatique, et les deux tendent à gagner des salaires similaires au début de leur carrière.
Mais les ingénieurs de type 1 évoluent vers un travail plus épanouissant et bien rémunéré au cours du temps, qu'il s'agisse de travaux à valeur commerciale ou de projets _open-source_ avant-gardistes, de direction technique ou de contributions individuelles d'une grande qualité.

> Le système de SMS global traite 20 milliards de messages par jour.
> WhatsApp en traite maintenant 42 milliards.
> Avec 57 ingénieurs.
> [pic.twitter.com/zZrtSIzhlR](https://t.co/zZrtSIzhlR)

> — Benedict Evans (@BenedictEvans) [2 février 2016](https://twitter.com/BenedictEvans/status/694342874729545729)

Les ingénieurs de type 1 trouvent des moyens pour apprendre la science informatique en profondeur, que ce soit de manière conventionnelle ou en se formant continuellement pendant leur carrière.
Ceux de type 2, typiquement, restent à la surface, apprenant des outil et des technologies spécifiques au lieu de leurs fondements sous-jacents, en se contentant d'acquérir de nouvelles compétences quand la mode technologique change de direction.
Actuellement, le nombre de personnes entrant dans l'industrie augmente rapidement, tandis que le nombre de diplômés en science informatique est relativement constant.
Cet excédent d'ingénieurs de type 2 commence à restreindre leurs opportunités de travail et les maintient à l'écart des tâches les plus épanouissantes.
Que vous vous efforciez de devenir un ingénieur de type 1 ou que vous soyez simplement à la recherche d'une sécurité d'emploi accrue, apprendre la science informatique est le seul moyen fiable d'y parvenir.

> Lol oh pourtant ils l'étaient.... [pic.twitter.com/XVNYlXAHar](https://t.co/XVNYlXAHar)

> — Jenna Bilotta (@jenna) [4 mars 2017](https://twitter.com/jenna/status/838161631662092289)

## Guide par disciplines

### Programmation

La plupart des licences en informatique commencent par une "introduction" à la programmation.
_(Note de la traductrice: Ce texte a été écrit dans un contexte nord-américain.)_
Les meilleures versions de ces cours profitent non seulement aux débutants, mais aussi à ceux qui ont manqué des concepts et modèles bénéfiques lors de leur premier apprentissage à programmer.
Notre recommendation standard pour ce type de contenu est le classique _Structure and Interpretation of Computer Programs (SICP)_ qui est disponible gratuitement en ligne aussi bien sous forme de [livre](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html) que sous forme de [vidéos de cours du MIT](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/)
Bien que ces vidéos soient formidables, nous suggérons plutôt les [cours de Brian Harvey basés sur SICP](https://archive.org/details/ucberkeley-webcast-PL3E89002AA9B9879E?sort=titleSorter) (pour le cours 61A à Berkeley).
Ceux-ci sont plus raffinés et conviennent mieux aux nouveaux étudiants que les cours du MIT.

Nous recommandons de travailler au moins les trois premiers chapitres de SICP et de faire les exercices.
Pour un entraînement supplémentaire, travaillez un ensemble de petit problèmes de programmation comme ceux sur [exercism](https://exercism.io/).

Compte-tenu du fait que ce guide a été publié pour la première fois en 2016, l'une des questions les plus fréquemment posées a été si nous recommandions maintenant des enregistrements d'itérations plus récentes du cours 61A enseigné par John DeNero et/ou le livre correspondant _[Composing Programs](https://composingprograms.com/)_, qui est "dans la tradition du SICP" mais utilise le Python.
Nous pensons que les ressources de DeNero sont également formidables et que certains étudiants pourraient en fin de compte les préférer, mais nous continuons de suggérer SICP, Scheme et les cours de Brian Harvey comme le premier jeu de ressources à essayer.

Pourquoi ?
Parce que SICP est unique dans ses capacités - au moins potentiellement - à altérer vos croyances fondamentales à propos des ordinateurs et de la programmation.
Tout le monde n'expérimentera pas cela.
Certains détesteront cet ouvrage, d'autres n'iront pas au-delà des premières pages, mais la récompense éventuelle vaut la peine d'essayer.

Si vous n'aimez pas SICP, essayer _Composing Programs_.
Si cela ne vous convient toujours pas, essayer _[How to Design Programs](https://htdp.org/)_.
Si aucun de ces ouvrages ne semble récompenser vos efforts, peut-être est-ce signe que vous feriez mieux de vous concentrer sur d'autres sujet pour un moment et de repasser à cette discipline dans un an ou deux.

Pour finir, un point de clarification: ce guide n'est PAS conçu pour ceux qui sont entièrement novices en programmation.
Nous partons du principe que vous être un développeur compétent sans bagage en science informatique et qui cherche à combler des lacunes.
Le fait que nous ayons inclu une section sur la "programmation" est simplement un rappel qu'il peut y avoir davantage à apprendre.
Pour ceux qui n'ont jamais codé auparavant, mais qui aimeraient le faire, vous devriez préférer un guide tel que [celui-ci](https://www.reddit.com/r/learnprogramming/wiki/faq#wiki_getting_started).

### Architecture des ordinateurs

L'architecture des ordinateurs - parfois appelée "systèmes informatiques" ou "organisation des ordinateurs" - est un premier aperçu important de l'informatique en-dessous de la surface des logiciels.
Selon notre expérience, c'est le domaine le plus négligé parmi les ingénieurs autodidactes.

Notre livre introductif préféré est _[Computer Systems: A Programmer's Perspective](https://csapp.cs.cmu.edu/3e/home.html) (CS:APP)_ et un cours d'introduction typique à l'architecture des ordinateur basé sur cet ouvrage [couvre](https://csapp.cs.cmu.edu/3e/courses.html) la plupart des chapitres 1 à 6.

Nous aimons CS:APP pour son approche pratique, orientée développeur.
Bien que l'architecture des ordinateurs soit bien plus vaste que ce qui est couvert dans le livre, il sert d'excellent point de départ pour ceux qui aimeraient comprendre les systèmes informatiques principalement pour écrire des logiciels plus rapides, plus efficaces et plus fiables.

> Le matériel est la plate-forme.

> — _Mike Acton, Directeur moteur à Insomniac Games
> ([regardez sa conférence CppCon](https://www.youtube.com/watch?v=rX0ItVEVjHc))_

Pour ceux qui préfèreraient une introduction plus douce et un équilibre entre les enjeux matériels et logiciels, nous suggérons _The Elements of Computing Systems_, aussi connu sous le nom "Nand2Tetris".
C'est un ouvrage ambitieux qui tente de vous livrer une compréhension cohésive de comment tout fonctionne dans un ordinateur.
Chaque chapitre implique de construire une petite partie du système entier, de l'écriture de portes logiques élémentaires en utilisant HDL, un CPU et un assembleur, jusqu'à une application de la taille d'un jeu de Tetris.

Nous recommandons de lire les six premiers chapitres du livre et de réaliser les projets associés.
Cela développera votre compréhension des liens entre l'architecture de la machine et le logiciel qui tourne dessus.

La première moitié du livre (et l'ensemble de ses projets) sont disponibles gratuitement sur [le site web de Nand2Tetris](https://www.nand2tetris.org/).
Il est aussi disponible sous forme d'un [cours Coursera accompagné de vidéos](https://www.coursera.org/learn/build-a-computer).

En cherchant la simplicité et la cohésion, Nand2Tetris met de côté la profondeur.
En particulier, deux concepts très importants dans l'architecture moderne des ordinateurs que sont le pipelining et la hiérarchie de la mémoire sont essentiellement absents du texte.

Une fois que vous vous sentirez à l'aise avec le contenu de Nand2Tetris, nous vous proposons soit de revenir à CS:APP, soit d'envisager de lire _Computer Organization and Design_ de Patterson et Hennessy, un excellent ouvrage désormais classique.
Toutes les sections du livre ne sont pas essentielles ; nous suggérons de suivre le cours [CS61C](https://inst.eecs.berkeley.edu/~cs61c/sp15/) de Berkeley, "Great Ideas in Computer Architecture" pour une lecture plus spécifique.
Les notes de cours et travaux pratiques sont disponibles en ligne, et les cours passés sont disponible sur [Internet Archive](https://archive.org/details/ucberkeley-webcast-PL-XXv-cvA_iCl2-D-FS5mk0jFF6cYSJs_).

### Algorithmes et structures de données

Nous sommes en accord avec des décennies de sens commun selon lequel la familiarité avec les algorithmes et structures de données courantes est l'un des aspects les plus valorisants d'une instruction à la science informatique.
C'est également un excellent endroit pour entraîner ses capacités de résolution de problème en général, ce qui sera payant dans tous les autres domaines d'étude.

Il existe des centaines de livres disponibles, mais notre préféré est _The Algorithm Design Manual_ de Steven Skiena.
Il est évident qu'il aime la résolution de problèmes algorithmiques et réussi généralement à susciter un enthousiasme similaire auprès de ses étudiants et lecteurs.
Selon nous, les deux ouvrages les plus souvent proposés (CLRS _(Note de la traductrice: Cormen, Leiserson, Rivest et Stein)_ et Sedgewick) tendent à être un petit peu trop alourdis de preuves pour ceux qui apprennent ce contenu principalement en vue de résoudre des problème en pratique.

Pour ceux qui préfèrent les cours filmés, [Skiena fourni généreusement les siens en ligne](https://www3.cs.stonybrook.edu/~skiena/373/videos/).
Nous aimons aussi beaucoup le cours de Tim Roughgarden, disponible sur [Coursera](https://www.coursera.org/specializations/algorithms) et [ailleurs](https://timroughgarden.org/videos.html).
Préférer le style de Skiena ou de Roughgarden est une question de préférence personnelle.
En fait, il existe des douzaines d'alternatives viables, aussi s'il vous arrive d'en trouver une autre que vous appréciez, nous vous encourageons à continuer avec !

> Je n'ai qu'une seule méthode que je recommande largement - cela s'appelle réfléchir avant d'écrire.

> — _Richard Hamming_

Pour la pratique, notre approche préférée est pour les étudiants de résoudre des problèmes sur [Leetcode](https://leetcode.com/).
Ces problèmes tendent à être intéressants pourvu de solutions et discussions décentes.
Il aident également à mesurer les progrès face aux questions couramment utilisées pendant les entretiens techniques dans les companies les plus compétitives.
Nous vous suggérons de résoudre environ 100 problèmes aléatoires sur leetcode comme une partie de vos études.

Enfin nous recommandons vivement _How to Solve It_ comme un guide excellent et unique pour la résolution de problèmes en général ; c'est autant applicable à la science informatique qu'aux mathématiques.

### Mathématiques pour l'informatique

> Si les gens ne croient pas que les mathématiques soient simples, c'est uniquement parce qu'ils ne réalisent pas à quel point la vie est compliquée.

> — _John von Neumann_

D'une certaine manière, la science informatique est une branche dérivée des mathématiques appliquée.
Tandis que plusieurs ingénieurs logiciel essaient - et parviennent à des degrés variables - d'ignorer cela, nous vous encourageons d'en aborder l'étude de manière directe.
Procéder ainsi avec succès vous donnera un énorme avantage compétitif sur ceux qui ne le font pas.

Le domaine des mathématiques le plus pertinent pour la science informatique est généralement appelé "mathématiques discètes", où "discret" est opposé à "continu" et est vaguement une collection de sujets de mathématiques appliquées intéressants en-dehors de l'arithmétique.
Compte-tenu de la définition souple, il n'aurait pas de sens d'essayer de couvrir l'entièreté des "mathématiques discrètes".
Un objectif plus réaliste est de se forger une compréhension de la logique, de la combinatoire et probabilités, de la théorie des ensemble, de la théorie des graphe et un petit peu de la théorie des nombres formant la cryptographie.
L'algèbre linéaire est un domaine d'étude additionnel qui vaut le coup, compte-tenu de son importance dans les graphismes et l'apprentissage automatique.

Notre suggestion de point de départ pour les mathématiques discrètes est l'ensemble des [notes de cours de László Lovász](http://www.cs.elte.hu/~lovasz/dmbook.ps).
Le professeur Lovász a fait un très bon travail pour rendre le contenu abordable et intuitif, ce qui en fait un meilleur point de départ que bien des textes plus formels.

Pour un approche plus avancée, nous conseillons _[Mathematics for Computer Science](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/readings/MIT6_042JF10_notes.pdf) (Note de la traductrice: lien mort au moment de la traduction, remplacé par un équivalent)_, notes de cours de la longueur d'un livre d'un cours éponyme du MIT.
Les vidéos de ce cours sont également [disponibles gratuitement](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/video-lectures/), et constituent notre recommandation de vidéos de cours pour les mathématiques discrètes.

Pour l'algèbre linéaire, nous suggérons de commencer avec la série de vidéos _[Essence of linear algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)_, suivie du livre et des [vidéos de cours](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/) de Gilbert Strang.

### Système d'exploitation

_Operating System Concept_ (le "livre du dinosaure") et _Modern Operating Systems_ sont des "classiques" sur les systèmes d'exploitation.
Les deux ont fait l'objet de critiques quant à leur manque de clarté et, de manière générale, leur peu de souci vis-à-vis des étudiants.

_Operating Systems: Three Easy Pieces (OSTEP)_ est une bonne alternative [disponible gratuitement en ligne](https://pages.cs.wisc.edu/~remzi/OSTEP/).
Nous aimons en particulier la structure et la lisibilité de l'ouvrage, et nous avons l'impression que les exercices en valent le coup.

Après OSTEP, nous vous encourageons à explorer les décisions de conception pour des systèmes d'exploitation spécifiques, à travers des livres du style "{Système d'exploitation} Intenals" comme _Lion's commentary on Unix_, _The Design and Implementation of the FreeBSD Operating System_ et _Mac OS X Internals_.
Pour Linux, nous conseillons le fantastique _Linux Kernel Development_ de Robert Love.

Une excellente manière de consolider votre compréhension des systèmes d'exploitation est de lire le code source d'un petit noyau et d'y ajouter des fonctionnalités.
Un choix peut être [xv6](https://pdos.csail.mit.edu/6.828/2016/xv6.html), un portage d'Unix V6 en C ANSI et x86 maintenu dans le cadre d'un cours au MIT.
OSTEP a un appendice de [travaux pratiques possibles avec xv6](https://pages.cs.wisc.edu/~remzi/OSTEP/lab-projects-xv6.pdf) avec plein d'idées formidables pour des projets éventuels.

### Réseaux informatiques

Sachant qu'une si grande partie de l'ingénierie logicielle réside sur des serveurs et des clients webk, un des domaine les plus rapidement valorisant en science informatique est les réseaux informatiques.
Il se trouve que nos étudiants autodidactes qui étudient méthodiquement les réseaux comprennent enfin les termes, concepts et protocoles dont ils ont été entourés des années durant.

> On ne peut pas regarder dans une boule de cristal et voir le futur.
> Ce qu'Internet deviendra à l'avenir sera ce que la société en fera.

> — _Bob Kahn_

Notre livre préféré sur le sujet est _Computer Networking: A Top-Down Approach_.
Les petits projets et exercices dans ce livre valent largement le coup d'être faits, et nous apprécions particulièrement les "travaux pratiques Wireshark" qu'ils ont [généreusement publié en ligne](Ohttps://gaia.cs.umass.edu/kurose_ross/wireshark.htm).

Pour ceux qui préfèrent des vidéos de cours, nous vous suggérons le cours de Stanford _[Introduction to Computer Networking](https://www.youtube.com/playlist?list=PLoCMsyE1cvdWKsLVyf6cPwCLDIZnOj0NS)_ disponible auparavant sur la plateforme de MOOC de Stanford Lagunita, mais désormais malheureusement uniquement disponible comme des listes d'écoute non officielles sur Youtube.

### Bases de données
