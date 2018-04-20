
# Directive sur la publication et le maintient d’un projet Ville en un projet libre

## Introduction
Suivant sa politique sur l’utilisation et le développement des logiciels
et du matériel libres, la Ville de Montréal sera amenée à publier des
projets développés par et pour la Ville, en tant que projets libres.

Le présent document décrit les grandes lignes du processus à suivre afin
de publier un tel projet et de le maintenir en tant que projet libre.

## Portée

Cette directive s’adresse à l’ensemble des unités administratives de la
Ville de Montréal susceptibles d’avoir à publier des projets logiciels
ou matériels en tant que projet libres.

Cette directive s’applique autant aux employés de la Ville qu’à ses
contractants ou aux tierces parties appelées à publier des projets
logiciels ou matériels au nom de la Ville, en tant que projets libres.

## Définitions
**Contrat de licence du contributeur *(Contributor License Agreement)*
(CLA)**: Accord entre un contributeur et l’entité juridique gérant un
projet libre, permettant de contribuer de la propriété intellectuelle
à cedit projet.

**Contributeur**: Personne faisant une contribution à un projet libre.

**Contribution**: Tout changement au code, à la documentation, aux
fichiers de configuration, aux plans, ou à tout autre fichier d’un
projet libre, qui est donné au projet en question pour y être inclus.

**Licence**: Contrat par lequel le titulaire des droits du logiciel
ou matériel autorise un tiers à poser certains gestes vis-à-vis ce
logiciel ou matériel.

**Maintien d’un projet libre**: Efforts nécessaires à garder un
projet libre actif.  Ses efforts incluent: faire évoluer le code ou
les plans du projet, documenter publiquement le projet, fournir un
niveau de support utile mais raisonnable aux utilisateurs, réviser
et accepter des contributions, etc.

**Projet logiciel libre**: Un programme ou une bibliothèque logicielle
pour lequel le code et autre ressource sont mis à la disposition du
grand public pour utilisation et/ou modification, et ce sans compensation.

**Projet matériel libre**: Plans d’artéfacts tangibles (machines,
dispositifs ou toutes choses physiques) ayant été rendus publics de façon
à ce que quiconque puisse fabriquer, modifier, distribuer et utiliser ces
artéfacts.

**Propriété intellectuelle**: Droits légaux quant à des créations
intellectuelles par exemple un logiciel ou des plans de matériels.

**Publication libre**: Les efforts et étapes initiaux nécessaires
à rendre un projet logiciel ou matériel disponible au grand public.

**Responsable du projet (*Maintainer*)**: Personne responsable de
l'exécution de l'ensemble des opérations qui sont jugées nécessaires
pour garantir le bon fonctionnement d'un projet de logiciel ou matériel
libres, conformément à des spécifications définies.

## Permissions de publication
Afin de protéger les intérêts et les ressources de la Ville, il faut
que les bénéfices, les risques et les coûts soient évalués avant la
publication libre d’un projet logiciel ou matériel.  Lorsque l’unité
d’affaires juge appropriée la publication libre d’un projet, une
permission devra être obtenue du directeur du service des TI, ou de
son délégué.  Cette permission vise à assurer que les bénéfices de
la publication libre sont compatibles avec les valeurs de la Ville.

La permission sera obtenue suite à la présentation et l’acceptation
d’un dossier contenant au minimum les éléments suivants :
1. la raison d’être du produit;
1. la vigie de marché démontrant le manque à combler s’il y a lieu,
ou les avantages de créer un marché ouvert parallèle;
1. les risques potentiels,
1. les coûts à prévoir (nombre d’employés affectés aux projet,
tâches requises pour le maintien du projet après sa publication,
estimation de la durée de l’implication, etc.).

## Publication

### Propriété intellectuelle

Afin de pouvoir publier librement un projet logiciel au nom de la
Ville, un responsable du projet doit s’assurer que la Ville détient
les droits légaux nécessaires à une telle publication.  Pour cela,
le responsable du projet doit:
1. s’assurer que tout fichier faisant partie de la publication est,
de façon exclusive, la propriété intellectuelle de la Ville;<br>
ou,
1. s’assurer que la Ville possède les droits nécessaires à publier
tous les fichiers faisant partie de la publication sous la licence
libre en question (voir la section sur la licence).

La publication libre d’un tel projet est faite au nom de la Ville
dans le dépôt public identifié par le service des TI.

Lorsqu’un projet devient disponible en tant que projet libre, toutes
contributions futures sont régies par la directive de contribution à
un projet logiciel existant.

### Forge de logiciels libres

La publication de projet sera faite dans GitHub sous le compte de la 
Ville: https://github.com/villedemontreal

### Responsables du projet

Avant la publication, un ou plusieurs responsables du projet doivent
être désignés.  Un responsable devrait normalement avoir une connaissance
approfondie des détails du projet et pourra en gérer le code et autres
aspects.  Le mandat d’un responsable du projet est d’assurer l’évolution
du projet afin que la Ville puisse bénéficier des avantages de la
publication en libre.

Il est recommandé de désigner plus d’un responsable afin d’assurer le
maintien du projet.

Durant la vie du projet, de nouveaux responsables peuvent être nommés
après qu’ils aient démontré les compétences nécessaires au rôle.  Une
telle nomination doit être appuyée par au moins un responsable existant,
sans être refusée par aucun autre responsable du projet.  Après une
nomination approuvée, un nouveau responsable se verra accorder les mêmes
droits que les responsables existants. Une personne mise en nomination en
tant que responsable, peut aussi bien être associée à la Ville qu’être un
contributeur externe, sans aucune association à la Ville.  

Un responsable du projet peut en tout temps abandonner officiellement son
rôle.  Dans un tel cas, il convient d’avertir le reste de la communauté du
projet, et d’assurer une transition de responsabilité, si nécessaire.

### Identité à utiliser pour la publication

La publication libre d’un projet sera faite par un des responsables du
projet qui a été assigné.  Cette publication doit être faite en utilisant
le nom dudit responsable ainsi que son adresse courriel fournie par la Ville.
Toutes modifications faites au nom de la Ville, après la publication du projet,
doivent aussi être faites en utilisant l’adresse courriel fournie par la Ville.

L’utilisation de l’adresse courriel de la Ville permet de distinguer les
contributions faites au nom de la Ville et de celles réalisées en dehors des
heures de travail (non rémunérées par la Ville).

Toutes contributions pour lesquelles la Ville possède la propriété intellectuelle
doivent être faites par un employé ou un contractant à l’emploi de la Ville.

Toutes contributions faites de façon personnelle doivent être faites en utilisant
une adresse courriel personnelle.

### Licence
Tout code du projet publié en libre utilisera la licence MIT. Un ficher LICENSE.md
tel que définit dans l’appendice A, doit être mis dans le répertoire de base du
projet, et ce, dès la publication initiale.

Pour les autres composantes du projet, tel les images et la documentation, une des
licences Creative Commons sera utilisée.

Pour les bases de données, la licence Open Data Commons Open Database License (ODbL)
sera utilisée (voir l’appendice A).

### Information sensible

Une publication libre d’un projet doit respecter la Loi sur la protection des
renseignements personnels du Québec; ne pas nuire à la protection de la vie privée
à la sécurité publique ou à la sécurité de l’information de la Ville de Montréal.

Il est de la responsabilité du responsable de projet faisant la publication de
s’assurer que le projet à publier ne contient pas ce type d’information.

Une liste non-exhaustive d’exceptions est fournie:
À REMPLIR

## Contributions

Un projet libre est appelé à évoluer après sa publication. Des contributions,
autant internes (de la Ville) qu’externes (d’un contributeur non associé à la Ville)
seront reçues afin de réparer des bogues ou d’ajouter des fonctionnalités.  Ces
contributions doivent être gérées de façon adéquate.

Il est de la responsabilité d’un responsable du projet de gérer et d’accepter ou
refuser une contribution.

### Bonnes pratiques pour contributions

Les responsables du projet définissent les étapes à suivre pour faire une
contribution au projet.  Un fichier CONTRIBUTING.md, doit être mis dans le
répertoire de base du projet.  Les bonnes pratiques de contribution sont spécifiques
à un projet et à ses responsables.  Des exemples de fichier CONTRIBUTING.md peuvent
servir d’inspiration:
* https://github.com/dotnet/corefx/blob/master/Documentation/project-docs/contributing.md
* https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md
* https://github.com/robbyrussell/oh-my-zsh/blob/master/CONTRIBUTING.md
* https://github.com/facebook/react/blob/master/CONTRIBUTING.md

### Licence

Chaque composante faisant partie d’une contribution devra utiliser la licence approprié
comme définie plus haut. 

### Contrat de licence du contributeur (*Contributor License Agreement - CLA*)
Dans tous les cas de contributions, un responsable du projet doit s’assurer que la personne
effectuant la contribution possède les droits nécessaires vis-à-vis de toutes les
modifications soumises.  Pour cela, le contributeur doit confirmer explicitement que:

  1. **la contribution a été rédigée en tout ou en partie par le contributeur
  et qu’il/elle a les droits de publier la contribution sous la licence libre
  du projet**;<br>
  ***OU***
  1. **la contribution a été fournie au contributeur par une autre personne
  qui certifie la clause #1, et que cette contribution n’a pas été modifiée
  depuis.**

L’utilisation d’un contrat de licence du contributeur (CLA) par le projet est recommandée
afin de gérer les contributions au projet.  Différentes solutions encadrant la gestion de
CLA dans GitHub sont disponibles:
* https://www.clahub.com/
* https://cla-assistant.io/
* https://clabot.github.io/

### Droits d’auteurs

Les droits d’auteurs pour chaque contribution resteront avec l’auteur original de la
contribution. 

### Contributions par un responsable du projet

Une modification faite par un responsable du projet et respectant le CLA peut être acceptée
sans plus de formalité.

### Contributions externes

Une contribution par une personne n’étant pas un responsable du projet est considérée
“externe”, et ce, même si elle est faite par une personne associée à la Ville.  Toute
contribution externe devra être approuvée par un responsable du projet.  Avant d’accepter
une contribution, il est de la responsabilité du responsable du projet de s’assurer que:
1. le CLA est respecté,
1. les licences sont publiées dans les fichiers nécessaires,
1. la contribution est appropriée et de qualité suffisante.

## Code de conduite

Le maintien de projets libres au nom de la Ville de Montréal affecte potentiellement la
réputation de la Ville. Il est important de protéger cette réputation pour préserver
l’image de la Ville. Dans cette optique, toutes interactions avec une communauté libre,
tant sur les canaux publics (forums, listes de courriels, appels téléphoniques ouverts,
etc.), qu’en privé (face à face, appels téléphoniques privés, courriels directs, etc.)
doivent être faites de façon professionnelle, polie et respectueuse, peu importe
l’attitude des autres parties.

## Application de la directive

Les étapes à suivre pour faire une publication libre d’un projet de la Ville sont:

1. Identifier une volonté de publication d’un projet en libre.
1. L’architecte de solutions rédige le dossier nécessaire à l’approbation et le présente
à un directeur du STI, ou à son délégué.
1. Lorsque la permission est obtenue, l’architecte de solutions désigne le responsable du
projet chargé de la publication.
1. Le responsable du projet chargé de la publication prépare le code.  En particulier il
doit:
    * Ajouter les fichiers LICENSE.md et CONTRIBUTING.md;
    * Enlever toute information privée;
    * S’assurer que la Ville détient toute la propriété intellectuelle du projet;
    * Choisir un outil/processus de CLA.
1. Lorsque le code du projet est prêt, le responsable du projet le publie sous
https://github.com/villedemontreal
1. Le ou les responsables du projet assurent le maintien du projet libre et gèrent
toutes contributions.

## Appendix A - Licences

### Licence MIT globale

Ajoutez le fichier LICENSE.md dans le le répertoire principal du projet avec le contenu suivant:
(en ayant remplacé <YEAR> par l’année de publication):

<span style="font-family: Courier New;">
Copyright <YEAR> Ville de Montreal
</span>

<span style="font-family: Courier New;">
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and
associated documentation files (the "Software"), to deal in the Software without restriction,
including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:
</span>

<span style="font-family: Courier New;">
The above copyright notice and this permission notice shall be included in all copies or substantial
portions of the Software.
</span>

<span style="font-family: Courier New;">
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT
LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
</span>

### Licence MIT locale

Ajoutez le texte suivant dans l’entête de tout fichier de code du projet.  Cela inclut de nouveaux
fichiers ajoutés après la publication initiale et faisant partie d’une contribution.  Dépendant du
langage de programmation, les “//” devront peut-être être remplacés par la syntaxe appropriée pour
des commentaires.

<span style="font-family: Courier New; word-wrap: none;">
// Copyright (c) Ville de Montreal. All rights reserved.<br>
// Licensed under the MIT license.<br>
// See LICENSE.md file in the project root for full license information.
</span>

### Licence ODbL

Ajoutez de façon claire à tout endroit nécessaire la phrase suivante (en ayant remplacé
{DATA(BASE)-NAME} avec le nom de la base de données):

<span style="font-family: Courier New; word-wrap: none;">
This {DATA(BASE)-NAME} is made available under the Open Database License:
http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual contents of the
database are licensed under the Database Contents License:
http://opendatacommons.org/licenses/dbcl/1.0/
</span>
