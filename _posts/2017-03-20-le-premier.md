---
title: Recyclage d'Artefacts Non Livrables
description: Capitaliser sur toutes les productions d'un projet informatique, y compris ce qu'on ne livre pas !
header: Recyclage d'Artefacts Non Livrables
type: Article
---

<h1>Qu'est-ce qu'un artefact non livrables dans un projet informatique ?</h1>
Qu'il soit agile ou non, des livraisons régulières jalonnent le déroulement d'un projet. En plus du code source de l'application, il convient de mettre en forme la documentation fonctionnelle, technique, de tests, des fonctionnalités, etc… Certes, le livrable le plus important d'un projet est l’application elle-même, mais d’autres livraisons jalonnent le projet : scénarii d’usage, modèles d’architecture, code source, documentation utilisateur ou technique, rapports d’avancement… Dès lors, un certain nombre de productions ne sont que temporairement conservées dans le but de réfléchir à une idée ou d'échanger, comme par exemple, des croquis sur paper-board, des discussions orales, des emails, des photos ou notes papier... Ce sont des artefacts non livrables car ils ne sont pas mis en forme pour être livrés au client. <a href="#refSB">[4]</a>

<a href="https://manurnx.wp.imt.fr/files/2017/03/livrablesjetables.jpg"><img class="alignnone size-full wp-image-137" src="https://manurnx.wp.imt.fr/files/2017/03/livrablesjetables.jpg" alt="" width="2048" height="414" /></a>

La durée de vie d'un artefact jetable ne dépasse pas celle d'un projet. Il n'est utile que pendant l'élaboration des artefacts livrables. Cependant, peut-il être utile dans un autre projet ? Il serait dommage de réinventer la roue à chaque nouveau projet. Peut-on capitaliser sur ces artefacts jetables, dessins, notes ou autres <a href="#refKH">[1]</a> ? Et comment ?

<!--more-->
<h2>Pourquoi les concepteurs ne privilégient pas davantage d'artefacts livrables ?</h2>
Les projets de développement logiciel qui suivent un processus agile donne la priorité au code source et non à la documentation ou aux modèles ayant permis sa production ou décrivant son architecture. Ces derniers sont à maintenir au fur et à mesure que les besoins évoluent et donc que le code est modifié, ce qui alourdit la charge de travail et rend moins agile la démarche. Cela ne veut pourtant pas dire qu'il ne faut pas modéliser ou documenter le code afin de conceptualiser une partie de l'architecture ou d'expliquer des choix d'implémentation. D'autant que ces modèles permettrait d'industrialiser la production grâce à la démarche d'ingénierie dirigée par les modèles. En effet, une modélisation respectant un langage standard et donc réalisée dans un outil de modélisation peut permettre à partir d'un modèle du système de générer du code, ou de transformer le modèle dans un autre formalisme, enfin d'automatiser des opérations sur les modèles et rendre moins fastidieuses le développement logiciel.

De nombreuses enquêtes montrent que les outils de modélisation ne sont pas bien adaptés aux usages des concepteurs. D'une part, ils sont reconnus lourds d'utilisation, et d'autre part implique de connaître les standards de modélisation, complexes et compliqués, comme par exemple le langage UML pour modéliser une application. Il est souvent préféré un simple croquis sur un bout de papier. <a href="#refBD">[2]</a> D'après Craig Larman <a href="#refLV">[5]</a>, créateur et animateur d'une communauté Agile Modeling, le meilleur outil de modélisation est un marker et un grand tableau blanc : <i>"The best modeling tool that I know of is a fresh black marker pen, a group of people, and a giant whiteboard area. Sketching UML on the wall is great."</i>

Et que se passe-t'il si on veut sortir du standard et annoter un modèle UML par exemple ou mixer plusieurs diagrammes ? Peu d'outils respectant le standard permettent cela. Il est possible de rendre un croquis persistent soit en le conservant tel quel, soit en le rendant conforme à un standard en le saisissant dans un outil. C’est le cas par exemple d’un schéma griffonné sur un paper-board lors d’un brainstorming et saisi dans un modeleur UML une fois sa conception stabilisée. À l’opposer, il est possible d’annoter un diagramme UML. Dès lors, les informations notées sur le diagramme sont hors standard. <a href="#refWHD">[3]</a>
Les moyens de conserver les artefacts jetables du projet sont la numérisation (photos des schémas sur paper-board ou tableau-blanc, enregistrement des discussions, notes de réunions, de discussions orales, extraits de discussions écrites, emails ou forums, schémas réalisés sur une tablette...)
Les schémas sont rarement retranscrits sur un modeleur UML standard, mais des diagrammes UML ébauchés sur un tableau blanc peuvent être saisis dans un outil de modélisation, souvent dans un souci de documentation.
<h1>Tri sélectif et valorisation d'artefacts jetables</h1>
Dans les trois scénarii suivant, j'exprime trois cas de figure qui motivent la conservation des artefacts non livrables et une idée de moyen pour le permettre.
<h2>Scénario 1. Capitalisation sur les anciens projets</h2>
Éviter les tâches récurrentes d'un projet. Les schémas, notes ou autres peuvent être intéressants d'un projet à l'autre. Il pourrait être intéressant de récupérer des schémas, des notes, voire de concevoir et maintenir un référentiel de bonne pratiques. Les artefacts jetables seraient conservés dans une base de connaissances et ré-utilisés dans d'autres projets : aide au product-owner dans le choix et la priorisation des backlogs, aide à l'ébauche de croquis par complémentation, aide aux décisions sur le projet...
<h2>Scénario 2. Retracer le film</h2>
Lorsqu'un nouveau membre intègre l'équipe en cours de projet, il doit assimiler beaucoup d'informations et intégrer les différentes productions du projet. Il pourrait être ainsi efficace plus rapidement sur les tâches courantes du projet. Les tâches et décision du projet sont enregistrés, ce qui permet de refaire le film du projet dans son état à l'instant t. Cela lui permet de vite rattraper son retard sur le projet. Cette idée peut permettre aussi de remonter le fil d'un projet en échec pour retrouver le moment où la mauvaise décision a été prise.
<h2>Scénario 3. Historique du livrable</h2>
Il peut être intéressant de savoir comment un diagramme UML a été réalisé, par quelle étapes, quelles ébauches ont permis de faire les bons choix de conception. On lie un livrable avec tous les jetables et les choix ayant permis sa réalisation (ex. : schémas d’architecture griffonnés attachés au code source livré...)
<h2 id="3a2c" class="graf graf--p graf-after--figure">Sources et liens utiles</h2>
[1] <a name="refKH"></a><a href="http://www.infoq.com/articles/kenji-modeling-agile" target="_blank">Modeling in the Agile Age: What to Keep Next to Code to Scale Agile Teams</a>, article de Kenji Hiranabe, Agile software development practitioner, sur le site InfoQ.com.

[2] <a name="refBD"></a><span style="font-size: 1rem;">S. Baltes and S. Diehl. 2014. <em>"Sketches and diagrams in practice"</em>. In Proceedings of the 22nd ACM SIGSOFT International Symposium on Foundations of Software Engineering (FSE 2014). ACM, New York, NY, USA, 530-541.</span>

[3] <a name="refWHD"></a><span style="font-size: 1rem;">J. Walny, J. Haber, M. Dörk, J. Sillito and S. Carpendale,</span><em style="font-size: 1rem;"> "Follow that sketch: Lifecycles of diagrams and sketches in software development,"</em><span style="font-size: 1rem;"> 2011 6th International Workshop on Visualizing Software for Understanding and Analysis (VISSOFT), Williamsburg, VA, 2011, pp. 1-8.</span>

[4] <a name="refSB"></a><a href="https://www.infoq.com/articles/agile-software-architecture-sketches-NoUML">Agile Software Architecture Sketches and NoUML</a>, article de Simon Brown, Consultant indépendant, sur le site InfoQ.com.

[5] <a name="refLV"></a><i>Practices for Scaling Lean &amp; Agile Development: Large, Multisite, and Offshore Product Development with Large-Scale Scrum</i>, Larman &amp; Vodde, Addison-Wesley. Copyright (c) 2010.
