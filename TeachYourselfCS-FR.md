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

## TL;DR (en bref)

Étudiez l'ensemble des neufs disciplines suivantes approximativement dans le même ordre à l'aide du manuel ou des vidéos conseillés (idéalement les deux).
Comptez 100 à 200 heures pour chaque sujet, puis revoyez vos préférés tout au long de votre carrière 🚀.

| Domaine | Pourquoi l'étudier ? | Livre | Vidéos |
| --------| -------------------- | ----- | ------ |
| **[Programmation](#Programmation)** | Ne soyez pas la personne qui n'a "jamais vraiment bien compris" quelque chose comme la récursion. | _Structure and Interpretation of Computer Programs_ | Berkeley CS 61A par Brian Harvey|
| **Architecture des ordinateurs** | Si vous n'avez pas une représentation mentale solide de la manière dont fonctionne un ordinateur, toutes vos abstractions de haut niveau en seront fragilisées. | _Computer Systems: A Programmer's Perspective_ | Berkeley CS 61C|
| **Algorithmes et structures de données** | Si vous ne savez pas comment utiliser des structures de données omniprésentes, comme des piles, des queues, des arbres ou des graphes, alors vous ne serez pas en mesure de résoudre des problèmes difficiles. | _The Algorithm Design Manual_ | Les cours de Steven Skiena |
| **Mathématiques pour l'informatique** | La science informatique est fondamentalement une branche dérivée des mathématiques appliquées, par conséquent apprendre les mathématiques vous donnera un avantage compétitif. | _Mathematics for Computer Science_ | MIT 6.042J par Tom Leighton |
| **Système d'exploitation** | La plupart du code que vous écrivez est exécuté par un système d'exploitation donc vous devriez savoir comment celui-ci interagit. | _Operating Systems: Three Easy Pieces_ | Berkeley CS 162 |
| **Réseaux informatiques** | Internet s'est avéré être une grosse problématique: comprenez comment il fonctionne pour déployer son plein potentiel. | _Computer Networking: A Top-Down Approach_ | Stanford CS 144 |
| **Bases de données** | Les données sont au coeurs des programmes les plus importants, or peu de personnes comprennent comment les systèmes de bases de données fonctionnent réellement. | _Readings in Database Systems_ | Berkeley CS 186 par Joe Hellerstein |
| **Langages et compilateurs** | Si vous comprenez comment les langages et les compilateurs fonctionnent, votre code sera meilleur et il vous sera plus aisé d'apprendre de nouveaux langages. | _Crafting Interpreters_ | Le cours d'Alex Aiken sur edX |
| **Systèmes distribués** | De nos jours, la plupart des systèmes sont distribués. | _Designing Data-Intensive Applications_ de Martin Kleppmann | MIT 6.824|

## C'est toujours trop ?

Si vous vous sentez débordés à la perspective d'étudier seul neuf disciplines pendant plusieurs années, nous vous conseillons de vous concentrer uniquement sur deux livres : _Computer Systems: A Programmer's Perspective_ et _Designing Data-Intensive Applications_.
D'expérience, ces deux livres fournissent un retour sur le temps investi incroyablement payant, en particulier pour les ingénieurs autodidactes et les personnes qui ont suivi une formation accélérée travaillant sur des applications en réseau.
Ils peuvent également servir de "drogue d'initiation", vous ouvrant ainsi la porte aux autres sujets et ressources listées ci-dessus.

## Pourquoi apprendre la science informatique ?

Il y a deux types d'ingénieurs: ceux qui comprennent la science informatique suffisamment bien pour effectuer un travail audacieux et innovant, et ceux qui s'en sortent parce qu'ils sont familiers avec quelques outils de haut niveau.
Les deux se font appeler ingénieurs informatiques, et les deux tendent à gagner des salaires similaires au début de leur carrière.
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
