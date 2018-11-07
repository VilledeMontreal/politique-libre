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
ou matériels en tant que projets libres.

Cette directive s’applique autant aux employés de la Ville qu’à ses
contractants ou aux tierces parties appelées à publier des projets
logiciels ou matériels au nom de la Ville, en tant que projets libres.

## Définitions
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
intellectuelles tel que des artéfacts logiciels ou des plans de matériels.

**Publication libre**: Action de rendre un projet logiciel ou 
matériel disponible au grand public.

**Responsable du projet (*Maintainer*)**: Personne responsable de
l'exécution de l'ensemble des opérations qui sont jugées nécessaires
pour garantir le bon fonctionnement d'un projet de logiciel ou matériel
libres, conformément à des spécifications définies.

## Publication

Lorsque l’unité d’affaires juge appropriée la publication libre d’un projet,
une consultation du Comité du Libre est nécessaire afin d'entamer la
publication du projet.

La publication en libre sera faite dans l'organisation GitHub de la Ville.

### Propriété intellectuelle

Afin de pouvoir publier librement un projet logiciel au nom de la
Ville, un responsable du projet doit:
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

### Responsable du projet libre

Avant la publication, un responsable du projet libre doit être désigné.
Un responsable devrait normalement avoir une connaissance des détails
du projet et pourra en gérer le code et autres aspects. Le role d’un
responsable est d'accompagner le projet dans son évolution
en libre afin que la Ville puisse bénéficier des avantages de la
publication.

### Licences
Tout code du projet publié en libre utilisera la licence *MIT*. Un ficher LICENSE
tel que défini dans l’appendice A, doit être mis dans le répertoire de base du
projet, et ce, dès la publication initiale.

Pour les autres composantes du projet, tel les images et la documentation, une des
licences *Creative Commons* sera utilisée.

Pour les bases de données, la licence *Open Data Commons Open Database License (ODbL)*
sera utilisée (voir l’appendice A).

### Information sensible

Une publication libre d’un projet doit respecter la Loi sur la protection des
renseignements personnels du Québec et ne pas nuire à la protection de la vie privée.

## Code de conduite

Le [Code de Conduite](http://ville.montreal.qc.ca/pls/portal/docs/page/intra_fr/media/documents/code_conduite_employes.pdf)
des employés de la Ville de Montréal s'applique à toutes interactions
relatives au maintien du projet libre.

## Application de la directive

Les étapes à suivre pour faire une publication libre d’un projet de la Ville sont illustrées dans [ce diagramme](https://www.lucidchart.com/documents/view/ce501f7d-1c88-48e4-a2f8-08dd782e6742).

Le processus complet est détaillé par les étapes suivantes :
1. Identifier une volonté de publication d’un projet en libre.
1. L’architecte de solutions du projet présente la demande au Comité du Libre
1. Lorsque la permission est obtenue, l’architecte de solutions désigne le responsable du
projet chargé de la publication.
1. Le responsable du projet chargé de la publication prépare le code.  En particulier il
doit:
    1. Ajouter les fichiers LICENSE et CONTRIBUTING.md;
    1. Enlever toute information privée;
    1. S’assurer que la Ville détient toute la propriété intellectuelle du projet;
1. Lorsque le code du projet est prêt, le responsable du projet le publie sous
github.com/villedemontreal
1. Le ou les responsables du projet assurent le maintien du projet libre et gèrent
toutes contributions.

## Appendix A - Licences

### Licence MIT globale

Ajoutez le fichier LICENSE dans le le répertoire principal du projet avec le contenu suivant:
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
// See LICENSE file in the project root for full license information.
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
artifacts or plans for hardware.

**Open-access publication**: Action of making an
open-source software or hardware available to the general public.

**Maintainer**: Person responsible for performing all operations considered
necessary for ensuring the proper operation of an open-source software or hardware
project, according to established specifications.

## Publication

Once a project is identified for open-source publication, working with the
Open-Source Committee is necessary to start the publication of the project.

An open-source publication will be done in the GitHub organization of the City.

### Intellectual property

Before making an open-source plublication, a project maintainer must:
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

### Open-Source Project Maintainers

A project maintainers must be designated prior to publication.
A maintainers should usually have an in-depth understanding of the project
and will be able to oversee its coding and other features. The project
maintainer is responsible for managing project evolution to ensure
that the city can benefit from open-source publication.

### Licence

Any project code published will use the *MIT* license. A LICENSE file, as
defined in Appendix A, must be saved to the project’s base folder following
initial publication.

A *Creative Commons* license will be used for other project components, such
as images and documentation.

The Open Data Commons Open Database License (ODbL) will be used for
databases (see Appendix A).

### Sensitive Information

Open-source publication of a project must comply with Québec’s Privacy Act,
and must not jeopardize privacy.

## Code of Conduct

The [Code of conduct](http://ville.montreal.qc.ca/pls/portal/docs/page/intra_fr/media/documents/code_conduite_employes.pdf)
of the City employees applies to all interactions pertaining to open source projects.

## Application of Directive

The process of publication of a municipal project is illustrated in [this diagram](https://www.lucidchart.com/documents/view/ce501f7d-1c88-48e4-a2f8-08dd782e6742).

The complete process is detailed below:
1. Confirm that there is a desire to make open-access publication of a project.
1. The solutions architect of the project presents the request to the Open-Source Committee.
1. Once permission has been obtained, the solutions architect designates the
project maintainer in charge of publication.
1. The project maintainer responsible for publication prepares the code. In
particular, s/he must:
    1. Add the LICENSE and CONTRIBUTING.md files.
    1. Remove all private information.
    1. Make sure the city possesses all of the project’s intellectual property.
1. Once the project’s code is ready, the project maintainer publishes it in
github.com/villedemontreal
1. The project maintainer(s) ensure(s) maintenance of the open-source project
and administers all contributions.

## Appendix A — Licences

### Global MIT License

Add the file LICENSE to the project’s main folder, using the following
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
// See LICENSE file in the project root for full license information.
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

