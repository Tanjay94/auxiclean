.. image:: https://travis-ci.org/physumasso/auxiclean.svg?branch=master
    :target: https://travis-ci.org/physumasso/auxiclean
.. image:: https://coveralls.io/repos/github/physumasso/auxiclean/badge.svg?branch=master
    :target: https://coveralls.io/github/physumasso/auxiclean?branch=master


Bienvenue sur le projet Auxi-Clean
==================================

Ce projet est une initiative des étudiants et étudiantes au département
de physique de l'Université de Montréal afin de créer une approche
automatisée pour l'attribution des tâches d'assistanat d'enseignement.

Le code source initial a été écrit par Jérémi Tanguay (Tanjay94 sur GitHub).


Installation
------------

Pour installer le projet, il faut un interpréteur python 3.
Un bon example est `Miniconda <https://conda.io/miniconda.html>`__
produit par Continuum Analytics.

Ensuite, cloner ou télécharger le projet sur le `répertoire officiel 
<https://github.com/physumasso/auxiclean>`__ du projet sur GitHub
et décompresser le fichier si nécéssaire.

Pour installer le module, il faut executer le script d'installation `setup.py`::

  $ python setup.py install

Pour une installation de développement, utiliser l'argument `develop` au lieu
de `install` car d'autres dépendances sont nécéssaires afin de faire rouler les
tests.

Fonctionnement
--------------

Le code fonctionne en lui donnant deux fichiers Excel: un contenant les
données de toutes les candidatures et l'autre contenant les détails sur les
cours à attribuer.


Contribution
------------

Pour contribuer au projet, simplement faire un fork du projet sur GitHub
et soumettre des pull request ou bien contacter un des responsable
du projet via la `PHYSUM <http://www.aephysum.umontreal.ca/>`__.

Pour les développeurs, il y a des unittests qui sont écrits afin d'aider
le développement et pour vérifier que tout marche encore. Ces tests
sont exécutés par le CI runner Travis pour tous les Pull Requests.
Pour les exécuter sur une machine locale, s'assurer d'avoir
installer le module en mode 'develop'::
  
  $ python setup.py develop

Et pour exécuter les tests, il suffit d'exécuter le script `tests.py`::

  $ python tests.py
