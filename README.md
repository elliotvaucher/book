![modulo-banner](https://github.com/edunumsec2/modulo2/blob/main/source/_static/assets/modulo-head-banner.svg)

# Informatique au Gymnase / Pilote

## Introduction

Des moyens d'enseignement pour l'informatique en discipline obligatoire au niveau Secondaire II ont été produits par un groupe de travail issu d'une collaboration entre la DGEP, l'EPFL, la HEP Vaud et l'UNIL. Dans le cadre de l’introduction de cette discipline, prévue à la rentrée 2022 dans le canton de Vaud, l'objectif de ces ressources est de proposer aux enseignant·e·s d'informatique des contenus théoriques, des séries d'exercices et des idées d'activités.

En accord avec la DGEP, une partie de ce matériel est déjà mise à disposition des enseignant·e·s vaudois·e·s pour une première phase pilote.

Les ressources sont accessibles via le [site web](https://edunumsec2.ch) (Username : edunum, Password : Edunumsecondaire2). Elles peuvent être utilisées telles quelles ou modifiées via un [dépôt GitHub](https://github.com/edunumsec2/book).

## Table des matières

---

- [Introduction](#introduction)
- [Utilisation](#utilisation)
- [Documents importants](#documents-importants)
- [Chapitrage du livre](#chapitrage)
- [Structure du dépôt GitHub : à modifier](#structure-dépôt-GitHub)
- [Installation](#installation)
  - [Installation recommandée](#installation-recommandée)
  - [Pré-requis](#pré-requis)
  - [Installation rapide](#installation-rapide)
  - [Utilisation](#utiisation)
  - [Génération de build](#génération-de-build)
- [Exemples d'utilisation des ressources](#exemples-dutilisation-des-ressources)
  - [Utilisation en ligne](#utilisation-en-ligne)
  - [Modifications indépendantes](#modifications-indépendantes)
  - [Participation au développement](#participation-au-développement)
- [Comité de rédaction](#comité-de-rédaction)


### Votre avis et ceux de vos élèves sont importants

En tant que membre du projet pilote, nous vous remercions par avance pour votre participation au processus d’enquête. Les données recueillies permettront d'évaluer la pertinence des contenus afin de réaliser les ajustements nécessaires. La démarche porte uniquement sur les ressources et les élèves, il ne s'agit en aucun cas d'évaluer la qualité de l'enseignement dispensé. Toutes les données seront traitées de façon confidentielle. En dernier lieu, ces données agrégées et anonymisées feront l'objet d'analyses statistiques à la fin de chaque semestre. 
  

## Utilisation

L'utilisation **standard** des ressources ne requiert pas d'installation particulière et peut-être effectuée immédiatement à l'adresse https://modulo-info.ch. 

Dans le cadre du projet pilote, nous vous saurions gré de suivre le protocole minimal décrit ci-dessous :  

1. Participer aux sondages suivants (10 min par sondage) : 
    - [Questionnaire de rentrée / élève](https://www.surveymonkey.com/r/VVZQYRR)
    - [Questionnaire de rentrée / enseignant·e](https://www.surveymonkey.com/r/s2enspre)
    - [Questionnaire post-thématique / élève](https://www.surveymonkey.com/r/s2elpostthem)
    - [Questionnaire post-thématique / enseignant·e](https://www.surveymonkey.com/r/s2enspostthem)
    - [Questionnaire post thématique enjeux sociaux / enseignant·e](https://www.surveymonkey.com/r/s2postensejs)

2. Ecrire à nathalie.farenc@epfl.ch pour la tenir informée du début et de la fin d'un cours donné sur l'un ou l'autre des sujets du Plan d'études.
3. Signaler tout défaut éventuel des ressources à nathalie.farenc@epfl.ch ou directement à la personne en charge de la thématique en question, dont vous trouverez l'adresse sous [comité de rédaction](#comité-de-rédaction).

L'utilisation **avancée** des ressources comprend, en outre, les étapes suivantes : 

4. Utiliser les fonctionnalités de GitHub telles que [issues](https://github.com/edunumsec2/book/issues) et [discussions](https://github.com/edunumsec2/book/discussions) pour signaler des améliorations potentielles. 

Après la phase **pilote**, les enseignant.es pourront en outre : 

6. Proposer et rédiger des modifications via la création d'une [branche](https://github.com/edunumsec2/book/branches). 
7. Forker le dépôt pour en faire un clone indépendant via le mécanisme de [fork](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo). 
8. Utiliser l'environnement [Sphinx- ](#installation) pour tester ses améliorations en local sur sa propre machine. 

## Documents importants

* [Livret de cours](https://files.edunumsec2.ch/livret.pdf) décrivant le découpage du plan d'études dans le détail. 
* [Questionnaire de rentrée / élève](https://www.surveymonkey.com/r/VVZQYRR)
* [Questionnaire de rentrée / enseignant·e](https://www.surveymonkey.com/r/s2enspre)
* [Questionnaire post-thématique / élève](https://www.surveymonkey.com/r/s2elpostthem)
* [Questionnaire post-thématique / enseignant·e](https://www.surveymonkey.com/r/s2enspostthem)
* [Questionnaire post thématique enjeux sociax / enseignant·e](https://www.surveymonkey.com/r/s2postensejs)

## Chapitrage

Les ressources sont découpées selon un chapitrage qui correspond au plan d'études romand (voir ci-dessus). Elles sont divisées en quatre parties, dont nulle n'a de préséance sur les autres. Il appartient à l'enseignante ou l'enseignant de choisir l'ordre dans lequel les contenus sont abordés. Le fait que les chapitres soient successifs est le résultat des limitations de l'affichage. Pour atténuer quelque peu ce problème, nous avons choisi de renoncer à une numérotation des chapitres. 

[Représentation de l'information](https://apprendre.modulo-info.ch/content/appr/theme/rep-info/accueil/eleve.html)
: Où il est question du passage du système décimal au *système binaire*, ainsi que des problématiques de traitement des données telles que *l'encodage*, *la compression*, *l'échantillonnage*, *le cryptage*, et la *représentation des caractères, des images et des sons* sous forme de bits. 

[Algorithmique I](https://apprendre.modulo-info.ch/content/appr/theme/algo1/accueil/eleve.html)
: Ce chapitre propose une *définition générale de l'algorithmique*, ainsi qu'une présentation de certains *algorithmes classiques*. 

[Programmation I](https://apprendre.modulo-info.ch/content/appr/theme/prog1/accueil/elevenew.html)
: Après avoir présenté un échantillon de langages de programmation et leurs différences respectives, ce chapitre *pose les bases du langage Python*. 

[Architecture des ordinateurs](https://apprendre.modulo-info.ch/content/appr/theme/archi/accueil/eleve.html)
: Il est question ici de notions telles que *les portes logiques*, *les transistors*, *l'architecture de Von Neumann*, et autres concepts essentiels à la compréhension de ce qui se passe au niveau physique et électronique dans un ordinateur.

## Structure dépôt GitHub (:warning: à modifier)

* [config](https://github.com/edunumsec2/book/tree/master/config) contient essentiellement les documents .yml et .py qui servent à générer la version html statique de la documentation. Ce qui est présent dans ce dossier tire sa source dans la documentation [Sphinx](https://www.sphinx-doc.org/en/master/index.html), ainsi que la documentation [jupyter-book](https://jupyterbook.org/intro.html). 
* [content](https://github.com/edunumsec2/book/tree/master/content) contient le contenu du cours, découpé en *annexes*, *enjeux* (pour enjeux de société), *readme*, *theme*. C'est dans le dossier *theme* que vous trouverez les documents sources des différentes thématiques. Dans les documents sources, il existe deux extensions : les documents .md, et les .ipynb. Les documents .md sont rédigés dans une sytanxe Mardown étendue, le [MyST](https://myst-parser.readthedocs.io/en/latest/). Les documents .ipynb sont à l'origine des documents créés pour [jupyter notebook](https://jupyter.org/). Les deux syntaxes sont tolérées pour la génération du site html statique via l'outil [jupyter-book](https://jupyterbook.org/intro.html). 
* [docs](https://github.com/edunumsec2/book/tree/master/docs) contient les *archives* de la documentation, à savoir des fichiers qui ne sont plus utilisés dans la version actuelle du livre. Le dossier *landing*, contient le .html qui génère la [page d'accueil](https://edunumsec2.ch/). *media*, comme d'ailleurs tous les autres dossiers portant ce nom, contient les media utilisés dans le dossier parent en question. *palette* contient des indications relatives à la palette graphique du projet. *wiki* contient les tutoriels nécessaires à l'utilisation du dépôt GitHub. 

## Installation 

⚠️ *Attention : l'installation qui suit N'EST PAS nécessaire dans le cadre du projet pilote. Elle figure ici à titre informatif pour celles et ceux qui souhaitent comprendre l'architecture globale du projet et veulent avoir une idée de l'intégralité des possibilités qu'offre un modèle de projet open source. Après la première année de pilote, et compte tenu des retours qui auront été faits, le projet se déploiera entièrement, et les enseignant.es d'informatique auront tout le loisir d'installer l'environnement ci-dessous et de s'amuser à leur guise avec la documentation open source de ce dépôt GitHub.* 

Pour ceux et celles qui souhaitent utiliser l'environnement Jupyter Book pour tester des contenus et participer au développement, la marche à suivre est la suivante : 

### Installation recommandée

Modulo2 est basé sur le générateur de documentation [Sphinx](https://www.sphinx-doc.org/en/master/) et utilise le template [Furo](https://github.com/pradyunsg/furo).

### Pré-requis

- Python 3.x et pip ([Installation MacOSX](https://docs.python-guide.org/starting/install3/osx/)) ([Installation Windows](https://docs.python-guide.org/starting/install3/win/)) ([Installation rapide](https://www.python.org/downloads/))
- [virtualenv](https://virtualenv.pypa.io/en/latest/) (`$ pip install virtualenv`)
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

Pour vérifier la bonne installation de l'environnement de base :
- `$ python --version`
- `$ virtualenv --version`
- `$ git --version`

Pour simplifier les actions fréquentes (build, clean), le projet contient un workspace pour [Visual Studio Code](https://code.visualstudio.com/). L'utilisation de VSCode est optionnelle, vous pouvez bien sûr utiliser votre éditeur de code préféré.

### Installation rapide

1. Récupération du projet : `git clone git@github.com:edunumsec2/book.git`
2. Vers la racine du projet : `cd book` 
3. Création d'un environnement virtuel : `virtualenv .env`
4. Activation de l'environnement virtuel : 
  - Sur MacOS : `source .env/bin/activate`
  - Sur Windows : `.env\Scripts\activate`
5. Installation des librairies dans l'environnement virtuel : `pip install -r requirements.txt -U`

**Remarque** : à chaque fois que vous travaillez sur le projet, l'environnement virtuel devrait être activé (point 4).

### Utilisation

Le projet utilise [sphinx-autobuild](https://github.com/executablebooks/sphinx-autobuild) qui démarre un serveur sur http://localhost:8000 (ou http://127.0.0.1:8000) et rebuild la documentation automatiquement lorsqu'un changement est détecté. 
1. Activation de l'environnement virtuel (si pas déjà fait)
2. Activation du serveur local :
  - Documentation 'Apprendre' : `sphinx-autobuild src/appr build --watch source --open-browser -a --delay 1`
  - Documentation 'Enseigner' : `sphinx-autobuild src/ens build --watch source --open-browser -a --delay 1`

Pour arrêter le serveur : <kbd>CTRL</kbd>+<kbd>c</kbd> ou <kbd>⌘</kbd>+<kbd>c</kbd>

### Génération de build

- Génération du build 'Apprendre' : `sphinx-build -b html docs/apprendre build/apprendre`
- Génération du build 'Enseigner' : `sphinx-build -b html docs/enseigner build/enseigner`

## Exemples d'utilisation des ressources

⚠️ *Attention : les utilisations suivantes sont présentes à titre indicatif mais ne seront effectives qu'après la phase pilote.* 

### Utilisation en ligne

1. Je me rends sur https://edunumsec2.ch
2. Je navigue à travers les différents chapitres du cours. 
3. Si une information m'intéresse, par exemple une anecdote historique, un angle d'attaque pour une notion, un exemple particulier, voire même une séquence entière de cours théorique, je prends des notes et la réutilise à souhait dans mes leçons. 
4. Je parcours les idées d'activité et je choisis celles qui m'intéressent. 
5. J'utilise les séries d'exercices à disposition comme "devoirs" pour mes élèves. 
6. Je demande à mes élèves de lire certains chapitres en préparation des cours. Je reprends les notions essentielles en classe.  

### Modifications indépendantes

1. Si certains contenus m'intéressent mais que je considère qu'ils pourraient être transformés pour être plus efficaces, je peux à tout moment aller consulter les fichiers sources. 
2. Je reviens sur ce dépôt Github.
3. Je retrouve le chapitre qui m'intéresse. 
4. Je télécharge le fichier source. 
5. Je le retravaille pour en faire ma propre version. 

### Participation au développement

1. Je me réfère au chapitre [installation](#installation). 
2. Une fois que l'environnement est installé, plusieurs options s'offrent à moi. 
3. Je peux travailler à l'amélioration des ressources en tant que *correcteur*. Dans ce cas, j'utilise les fonctions [issues](https://github.com/edunumsec2/book/issues) et [discussions](https://github.com/edunumsec2/book/discussions) de Github et je propose des améliorations ou des modifications qui me paraissent importantes. 
4. Je peux travailler en tant que *rédacteur*. Dans ce cas je crée une branche, je propose des contenus originaux à l'intérieur d'un chapitre - séquences théoriques, activités, séries d'exercices, et je les soumets aux autres utilisateurs pour validation via un pull-request.

## Comité de rédaction

- Représentation de l'information : David Da Silva (david.dasilva@eduvaud.ch) - Gymnase de Chamblandes & Javier Iglesias (javier.iglesias@eduvaud.ch) - Gymnase de Renens
- Algorithmique : Biljana Petreska (biljana.petreska@fileinformatique.ch) - Gymnase d'Yverdon & Micha Hersch (demander contact à nathalie.farenc@epfl.ch) Gymnase de Renens / HEP Vaud
- Programmation : Raphaël Holzer (raphael.holzer@eduvaud.ch) - Gymnase du Bugnon & Gilles Racine (gilles.racine@eduvaud.ch) - Gymnase de Sevelin
- Architecture des ordinateurs : Philippe Rochat (philippe.rochat@fileinformatique.ch) - Gymnase de Morges & Jean-Philippe Pellet (jean-philippe.pellet@fileinformatique.ch) - HEP Vaud
- Enjeux sociaux : Lucile Berset (lucile.berset@epfl.ch) - EPFL ;  Virginia Haussauer (virginia.haussauer@epfl.ch) - EPFL;  Frank Dayen (frank.dayen@eduvaud.ch) - Gymnase de Morges & Boris Beaude (boris.beaude@unil.ch) - UNIL
- Plateforme : Romain Edelmann (romain.edelmann@epfl.ch) - EPFL & Grégoire Gavin (gregoire.gavin@epfl.ch) - EPFL
- Charte éditoriale, plateforme, rédaction : Elliot Vaucher (elliot.vaucher@epfl.ch) - EPFL
- Coordination : Nathalie Farenc (nathalie.farenc@epfl.ch) - EPFL
