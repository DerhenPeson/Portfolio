---
title: Automatisation baie radio
publishDate: 2020-03-02 00:00:00
img: /assets/stock-1.jpg
img_alt: Iridescent ripples of a bright blue and pink liquid
description: |
  Mon travail au sein d'une équipe IVVQ sur l'automatisation de tests d'une baie radio
tags:
  - Dev (Python)
  - Electronique (équipements radio)
---

<!-- ## Level-two heading -->

> Introduction au projet:

J'ai été intégré dans l'équipe IVVQ (Intégration Vérification Validation Qualification) du secteur « Réseau de communication d'infrastructure stratégique" au sein de l'entreprise Thales. Son rôle est l'intégration d'une station d'émission réception FH et en particulier l'intégration d'un nouveau modem développé par Thales sur cette station. Pour ce faire, des baies de test sont montées afin, comme leur nom l’indique, d’effectuer toutes sortes de tests afin d’étudier par exemple les puissances d’émission optimales ainsi que les réactions des différents équipements. Le but est ici de fournir un moyen de communication toujours plus performant. Pour le moment, nous n’avons pas encore tout le matèriel nécessaire pour faire une simulation complète et les tests évoluent donc au fur et à mesure que les différentes pièces arrivent sur site. Les différents acteurs de cette équipe ont donc envisagé la mise en place de moyens d’automatisation à la fois afin d’éviter la perte de temps due au calibrage de tous les appareils mais aussi pour permettre d’effectuer des actions de nuit ou le week-end.

<!-- ### Level-three heading -->
> Ma tâche:

Dans ce projet ma tâche est de développer 3 tests d'automatisation qui seront lancés à chaque modification de matèriel sur la baie afin 
de tester le fonctionnement global. L'e premier script est un banal test de fréquence qui permet de tester le bon fonctionnement de la baie. Le deuxième script est un script de performance qui a pour but de balayer toute la plage de fréquence d'émission afin de constituer un fichier de calibration qui servira pour tout les tests. Enfin, le dernier test est un test d'endurance qui permet de simuler l'émission sur plusieurs jours en faisant varier les fréquences et la puissance d'émission pour au final renvoyer les données des sondes de puissance et de température dans un fichier csv.

<!-- ### Level-three heading -->
> Mon travail:

J'ai donc pour ce projet développer 3 scripts en python servant chacun à effectuer un test. J'ai aussi mis en place des librairies python afin de piloter les équipements de la baie radio. Et pour finir j'ai testé la totalité de mon travail directement sur la baie en manipulant le matèriel disponible(générateur, sondes, analyseur de spectre)

<!-- #### Level-four heading -->
> Compétences:

- Développement: nouvelles librairies à maîtriser
- Electronique: apprentissage de l'utilisation du matèriel radio
- Team work: Première intégration dans une équipe d'ingénieur et donc apprentissage de la commmunication inter équipe.
