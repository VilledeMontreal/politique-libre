[English](#english-version)

# Directive sur la publication et le maintien d’un projet Ville en libre

## Introduction
Suivant sa politique sur l’utilisation et le développement des logiciels
et du matériel libres, la Ville de Montréal publiera des
projets développés par et pour la Ville, en tant que projets libres.

Le présent document décrit les grandes lignes du processus à suivre afin
de publier un tel projet et de le maintenir.

## Portée

Cette directive s’adresse à l’ensemble des unités administratives de la
Ville de Montréal susceptibles d’avoir à publier des projets logiciels
ou matériels en tant que projet libres.

Cette directive s’applique autant aux employés de la Ville qu’à ses
contractants ou aux tierces parties appelées à publier des projets
logiciels ou matériels au nom de la Ville, en tant que projets libres.

## Définitions
**Contrat de licence du contributeur *(Contributor License Agreement)*
(*CLA*)**: Accord entre un contributeur et l’entité juridique gérant un
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
estimation de la durée de la participation, etc.).

## Publication

### Propriété intellectuelle

Afin de pouvoir publier librement un projet logiciel au nom de la
Ville, un responsable du projet doit s’assurer que la Ville détient
les droits légaux nécessaires à une telle publication.  Pour cela,
le responsable du projet doit:
1. s’assurer que tout fichier faisant partie de la publication est,
de façon exclusive, la propriété intellectuelle de la Ville;<br>
ou,
1. s’assurer que la Ville possède les droits nécessaires pour publier
tous les fichiers faisant partie de la publication sous la licence
libre en question (voir la section sur la licence).

La publication libre d’un tel projet est faite au nom de la Ville
dans le dépôt public identifié par le Service des TI.

Lorsqu’un projet devient disponible en tant que projet libre, toutes
contributions futures sont régies par la Directive de contribution à
un projet logiciel existant.

### Forge de logiciels libres

La publication de projet sera faite dans GitHub sous le compte de la 
Ville: github.com/villedemontreal

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
après qu’ils aient démontré les compétences nécessaires pour assurer ce rôle.  Une
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

Pour les bases de données, la licence *Open Data Commons Open Database License (ODbL)*
sera utilisée (voir l’appendice A).

### Information sensible

Une publication libre d’un projet doit respecter la Loi sur la protection des
renseignements personnels du Québec; ne pas nuire à la protection de la vie privée
à la sécurité publique ou à la sécurité de l’information de la Ville de Montréal.

Il est de la responsabilité du responsable de projet faisant la publication de
s’assurer que le projet à publier ne contient pas ce type d’information.

Une liste non-exhaustive d’exceptions est fournie:

- ***À REMPLIR***

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
* github.com/dotnet/corefx/blob/master/Documentation/project-docs/contributing.md
* github.com/angular/angular.js/blob/master/CONTRIBUTING.md
* github.com/robbyrussell/oh-my-zsh/blob/master/CONTRIBUTING.md
* github.com/facebook/react/blob/master/CONTRIBUTING.md

### Licence

Chaque composante faisant partie d’une contribution devra utiliser la licence appropriée
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

L’utilisation d’un contrat de licence du contributeur (*CLA*) par le projet est recommandée
afin de gérer les contributions au projet.  Différentes solutions encadrant la gestion de
*CLA* dans GitHub sont disponibles:
* www.clahub.com/
* cla-assistant.io/
* clabot.github.io/

### Droits d’auteurs

Les droits d’auteurs pour chaque contribution resteront avec l’auteur original de la
contribution. 

### Contributions par un responsable du projet

Une modification faite par un responsable du projet et respectant le *CLA* peut être acceptée
sans plus de formalité.

### Contributions externes

Une contribution par une personne n’étant pas un responsable du projet est considérée
“externe”, et ce, même si elle est faite par une personne associée à la Ville.  Toute
contribution externe devra être approuvée par un responsable du projet.  Avant d’accepter
une contribution, il est de la responsabilité du responsable du projet de s’assurer que:
1. le *CLA* est respecté,
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
    1. Ajouter les fichiers LICENSE.md et CONTRIBUTING.md;
    1. Enlever toute information privée;
    1. S’assurer que la Ville détient toute la propriété intellectuelle du projet;
    1. Choisir un outil/processus de *CLA*.
1. Lorsque le code du projet est prêt, le responsable du projet le publie sous
github.com/villedemontreal
1. Le ou les responsables du projet assurent le maintien du projet libre et gèrent
toutes contributions.

## Appendix A - Licences

### Licence MIT globale

Ajoutez le fichier LICENSE.md dans le le répertoire principal du projet avec le contenu suivant:
(en ayant remplacé <YEAR> par l’année de publication):

```
Copyright <YEAR> Ville de Montreal

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and
associated documentation files (the "Software"), to deal in the Software without restriction,
including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial
portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT
LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

### Licence MIT locale

Ajoutez le texte suivant dans l’en-tête de tout fichier de code du projet.  Cela inclut de nouveaux
fichiers ajoutés après la publication initiale et faisant partie d’une contribution.  Dépendant du
langage de programmation, les “//” devront peut-être être remplacés par la syntaxe appropriée pour
des commentaires.

```
// Copyright (c) Ville de Montreal. All rights reserved.
// Licensed under the MIT license.
// See LICENSE.md file in the project root for full license information.
```

### Licence ODbL

Ajoutez de façon claire à tout endroit nécessaire la phrase suivante (en ayant remplacé
{DATA(BASE)-NAME} avec le nom de la base de données):

```
This {DATA(BASE)-NAME} is made available under the Open Database License:
http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual contents of the
database are licensed under the Database Contents License:
http://opendatacommons.org/licenses/dbcl/1.0/
```

---

---

---

<a id='english-version' class='anchor' aria-hidden='true'/>

# Directive on Publication and Maintenance of an Open-Source Municipal Project

## Introduction
Under its open-source software/hardware development and use policy, Montréal
will publish projects developed as open-source projects by and for the city.

The document outlines the procedure for publishing and maintaining such a project.

## Scope
This directive applies to all of Montréal’s municipal administrative units that
may contribute to open-source soft- or hardware projects.

This directive applies to city employees, contractors and third-parties publishing
open-source soft- and hardware projects on behalf of the city.

## Definitions

**Contributor License Agreement—CLA**: Agreement between a contributor and the
legal entity overseeing an open-source project, permitting a contribution to the
project’s intellectual property.

**Contributor**: Person contributing to an open-source project.

**Contribution**: Any change in code, documentation, configuration files, plans
or any other files of an open-source project, to be included in the project concerned.

**Licence**: Contract by which the holder or rights in the soft- or hardware
authorizes a third party to take certain actions with respect to this software or
hardware.

**Maintenance of an open-source project**: Efforts required to keep an open-source
project active. Such efforts include developing the code or project plans, publicly
documenting the project, providing a useful level of support (but reasonable for
users), reviewing and accepting contributions, etc.

**Open-source software project**: An application or software library with source code
and other resources that anyone can use and modify without charge.

**Open-source hardware project**: Plans for tangible artifacts (machines, devices
and all physical objects) that have been made public so that anyone can manufacture,
modify, distribute or use them.

**Intellectual property**: Legal rights to intellectual creations, such as software
or plans for hardware.

**Open-access publication**: Efforts and initial steps required to make an
open-source software or hardware available to the general public.

**Maintainer**: Person responsible for performing all operations considered
necessary for ensuring the proper operation of an open-source software or hardware
project, according to established specifications.

## Contribution Permissions

Benefits, risks and costs must be determined before open-access publication of an
open-source soft- or hardware project. Once the business unit decides that
open-access project publication is appropriate, permission must be obtained from
city’s IT director or the latter’s delegate. This permission is intended to ensure
that the benefits of open-access publication are consistent with municipal values.

Such permission shall be obtained following submission and acceptance of a file
containing at least the following information:
1. The product’s purpose.
1. Market watch document demonstrating any needs to be met or benefits in creating
a parallel open market.
1. Prospective risks.
1. Estimated costs (number of employees assigned to project, tasks required to
maintain project following publication, estimated period of participation, etc.).

## Publication

### Intellectual property

A project maintainer must ensure that the city holds the legal rights for
open-access publication of a software project on behalf of the city, before such
publication occurs. The project maintainer does so by:
1. Ensuring that any files that is to be part of the publication is exclusively
the city’s intellectual property.<br>
or
1. Ensuring that the city holds the necessary rights to publish all files to be
included in the publication under the open-source licence concerned (see the
Licence section).
Open-source publication of the project is done on behalf of city to the public
repository specified by IT.
If a project is accepted as open source, all future contributions to it are
covered by the Directive on Contributions to an Existing Software Project.

### Open-Source Software Registry

The project will be published in GitHub under the city’s account at
github.com/villedemontreal

### Project Maintainers

One or more project maintainers must be designated prior to publication.
A maintainers should usually have an in-depth understanding of the project
and will be able to oversee its coding and other features. The project
maintainer is responsible for managing project development and ensuring
that the city can benefit from open-access publication.

We recommend naming more than one maintainer to ensure maintenance of the project.

New maintainers might be appointed over the course of a project, once they have
demonstrated the necessary abilities for this role. Such an appointment must be
supported by at least one existing maintainer and not be rejected by any other
project maintainer. Once an appointment has been approved, the new maintainer
will have the same rights as the others. A person named as maintainer could be
someone associated with the city or an external contributor not associated with
the city.

A project maintainer may abandon this role at any time. Under such circumstances,
s/he advises the rest of the community to ensure a transition of responsibility,
if necessary.

### Identity to Use for Publication

One of the assigned project maintainers will handle open-access publication of
the project. This publication must be performed using the maintainer’s name and
city email address. Any changes made on behalf of the city following project
publication must also use the city email address.

Using a city email address makes it possible to distinguish between
contributions made on behalf of the city from those made outside working hours
(not paid by the city).

All contributions for which the city owns the intellectual property must be
made by an employee or contractor working for the city.

All individual contributions must be made using a personal email address.

### Licence

Any project code published will use the MIT license. A LICENSE.md file, as
defined in Appendix A, must be saved to the project’s base folder following
initial publication.

A Creative Commons license will be used for other project components, such
as images and documentation.

The Open Data Commons Open Database License (ODbL) will be used for
databases (see Appendix A).

### Sensitive Information

Open-source publication of a project must comply with Québec’s Privacy Act,
and must not jeopardize privacy, public safety or Montréal’s information
security.

The project maintainer is responsible for ensuring that the project to be
published does not contain such information.

A partial list of exceptions follows:

- ***TO BE PROVIDED***

## Contributions

An open-source project is expected to evolve following its publication.
Internal (municipal) and external (from a contributor not associated with
the city) contributions are received to fix bugs and add features. These
contributions must be properly administered.

A project maintainer is responsible for overseeing, accepting and refusing
contributions.

### Best Practices for Contributions

Project maintainers define the steps to be followed in making a contribution
to the project. A CONTRIBUTING.md file must be placed in the project’s base
directory. Best practices for a project are specific to a project and its
maintainers. Existing CONTRIBUTING.md files may serve as sources of inspiration:
* github.com/dotnet/corefx/blob/master/Documentation/project-docs/contributing.md
* github.com/angular/angular.js/blob/master/CONTRIBUTING.md
* github.com/robbyrussell/oh-my-zsh/blob/master/CONTRIBUTING.md
* github.com/facebook/react/blob/master/CONTRIBUTING.md

### Licence

Every component of a contribution must have the appropriate licence as defined
above.

### Contributor License Agreement—CLA

A project maintainer must, in the case of all contributions, ensure that the
person making them holds the necessary rights to make all the changes requested.
The contributor does so by specifically confirming that:

  1. **The contribution was written in whole or part by the contributor who holds
  the rights to publish the contribution under the required open-source licence.**<br>
  ***OR***
  1. **The contribution was provided to the contributor by another person who
  certifies that clause #1 is true, and this contribution has not been subsequently
  altered.**

We recommend that the project use a contributor licence agreement (CLA) to administer
contributions to it. Various CLA management solutions may be found in GitHub:
* www.clahub.com/
* cla-assistant.io/
* clabot.github.io/

### Copyright

The copyright for each contribution will remain with the contribution’s original author.

### Contributions by a Project maintainer

A change made by a project maintainer that complies with the CLA may be accepted
without other formalities.

### External Contributions

A contribution from someone other than a project maintainer is considered “external”
even if made by a person associated with the city. All external contributions must
be approved by a project maintainer. Before accepting a contribution, the project
maintainer must ensure that:
1. It complies with the CLA.
1. Licences have been published in the required files.
1. The contribution is appropriate and of suitable quality.

## Code of Conduct

Maintenance of open-source projects on behalf of the city have a potential impact
on Montréal’s reputation, which must be protected to preserve the city’s image.
This means that all interactions with an open-source community whether through
public (forums, email lists, open phone calls, etc.) or private (face-to-face,
private phone calls, direct emails, etc.) channels must be professional, polite
and respectful, regardless of the other parties’ attitudes.

## Application of Directive

This is how to make open-access publication of a municipal project:

1. Confirm that there is a desire to make open-access publication of a project.
1. The solutions architect prepares the file required for approval and submits
it to an IT director or the latter’s delegate.
1. Once permission has been obtained, the solutions architect designates the
project maintainer in charge of publication.
1. The project maintainer responsible for publication prepares the code. In
particular, s/he must:
    1. Add the LICENSE.md and CONTRIBUTING.md files.
    1. Remove all private information.
    1. Make sure the city possesses all of the project’s intellectual property.
    1. Select a CLA tool/process.
1. Once the project’s code is ready, the project maintainer publishes it in
github.com/villedemontreal
1. The project maintainer(s) ensure(s) maintenance of the open-source project
and administers all contributions.

## Appendix A — Licences

### Global MIT License

Add the file LICENSE.md to the project’s main folder, using the following
content (inserting the year of publication):

```
Copyright <YEAR> Ville de Montreal

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and
associated documentation files (the "Software"), to deal in the Software without restriction,
including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial
portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT
LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

### Local MIT License

Add the following text in the header of any project code file. This includes new files
that are part of a contribution and are added after the initial publication. Depending
on the programming languages, “//” should be replaced by the appropriate comment syntax.

```
// Copyright (c) Ville de Montreal. All rights reserved.
// Licensed under the MIT license.
// See LICENSE.md file in the project root for full license information.
```

### ODbL License

Clearly add wherever necessary the following sentence (replacing
{DATA(BASE)-NAME} with the appropriate information):

```
This {DATA(BASE)-NAME} is made available under the Open Database License:
http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual contents of the
database are licensed under the Database Contents License:
http://opendatacommons.org/licenses/dbcl/1.0/
```

