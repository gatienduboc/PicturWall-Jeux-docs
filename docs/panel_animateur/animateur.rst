.. _panel-animateur:

Présentation du panel animateur
==================================

Afin de pouvoir administrer la partie, vous allez devoir vous allez devoir vous connecter au réseau Wifi PicturWall 
puis vous rendre sur l'URL suivante de picturwall : `picturwall.fr/admin <https://picturwall.tv/admin>`_

.. tip::
    Il existe un environnement de test hébergé sur internet à l'adresse suivante : `Environnement de test <http://cluster01.gatien-duboc.fr:3001/admin>`_

.. important::
   L'interface a été déssiné pour être utilisé sur un écran d'ordinateur au format paysage. Il peut aussi être utilisé via une tablette de minimum 10" en format paysage.

Plusieurs administrateur peuvent utiliser l'interface en simultané.

.. _panel-animateur_menu:

Menu
===============================

Le panel animateur est composé de plusieurs pages, accessible via un menu en partie suprérieure de l'écran :

.. figure:: /panel_animateur/_images/animateur_menu.png
   :alt: Panel Animateur - Menu
   :align: center
   :width: 100%
   :figclass: align-center

   **Panel Animateur : Menu**

On y trouve, de gauche à droite :

* Admin : Sert à gérer la partie en cours
* :ref:`Paramètres<panel-animateur_parametres>` : Pour personnaliser le fonctionnement du jeu à votre gout
* :ref:`Questionnaire <panel-animateur_questionnaire>` : La gestion des questionnaires (modification, import/export....)
* `Documentation <https://docs.jeu.picturwall.fr>`_ : Celle ci !

.. note::
    La page "Questionnaire" est uniquement accessible lorsque vous êtes en mode initialisation

.. important::
    La documentation est accessible `en interne PicturWall <https://picturwall.tv/docs>`_, mais aussi `via internet <https://docs.jeu.picturwall.fr>`_


.. _panel-animateur_section:

En jeu : Section globales
===============================

Lorsque vous êtes en mode jeu, le panel est découpé en plusieurs sections : 

.. figure:: /panel_animateur/_images/etat/jeu_qcm.png
   :alt: Panel Animateur - Jeu 
   :align: center
   :width: 100%
   :figclass: align-center

   **Panel Animateur : Jeu**

De haut en bas : 

* :ref:`Le menu <panel-animateur_menu>`
* :ref:`La barre d'action <panel-animateur_jeu_barre_action>`
* Ensuite, l'écran est séparée en deux parties :
   * A gauche, la gestion de la question en cours :ref:`mode Buzzer <mode_buzzer_animateur>`, :ref:`mode QCM <mode_qcm_animateur>`
   * A droite, le :ref:`tableau des scores <panel-animateur_jeu_scoreboard>`


.. _panel-animateur_jeu_barre_action:

En Jeu : Barre d'action
===============================

Lorsque qu'on est en mode jeu, peu importe le type de jeu nous nous retrouvons avec cette barre dans la partie haute du panel : 

.. figure:: /panel_animateur/_images/animateur_barre_action.png
   :alt: Panel Animateur - Jeu en mode buzzer
   :align: center
   :width: 100%
   :figclass: align-center

   **Panel Animateur : Barre d'action**

.. figure:: /panel_animateur/_images/animateur_barre_action_reprendre.png
   :alt: Panel Animateur - Jeu en mode buzzer
   :align: center
   :width: 100%
   :figclass: align-center

   **Panel Animateur : Barre d'action en mode pause**

On y trouve, de gauche à droite :

* Un bouton pour passer à la prochaine question. Il existe aussi un :ref:`Passage automatique à la prochaine question lorsque tout les joueurs ont répondu <panel-animateur_parametres-prochaine_question>` lorsque nous sommes en mode de jeu QCM
* Un bouton pour afficher le scoreboard sur le board :ref:`Affichage du scoreboard sur le board en mode jeu <panel-board_jeu_scoreboard>`
* Un bouton pour mettre le jeu en pause // reprendre le jeu :ref:`Affichage de l'état pause sur les différents panel <jeu-etat_pause>`
* Un bouton pour afficher la question précédente côté animateur, joueur et board mais en empêchant les joueurs de répondre
* Un bouton pour arrêter la partie :ref:`Affichage de l'état fini sur les différents panel <jeu-etat_fini>`

Et sous ces boutons, un aperçu de la prochaine question qui sera posé aux convives.

.. _panel-animateur_jeu_scoreboard:

En Jeu : Scoreboard
===============================

Lorsque nous sommes en mode jeu, nous pouvons voir le scoreboard des joueurs sur la droite de votre écran.

Vous pouvez ajouter ou retirer des points aux joueurs !
Attention, pour des soucis de performance et de simplicité, seul les 20 premiers joueurs de la partie sont affichés dans le scoreboard côté animateur.

.. figure:: /panel_animateur/_images/animateur_scoreboard.png
   :alt: Panel Animateur - Scoreboard
   :align: center
   :width: 100%
   :figclass: align-center

Il suffit d'appuyer sur **"+"** pour ajouter un point à un joueur ou appuyer sur **"-"** pour lui en retirer un.

.. note::
    Vous pouvez-assigner des points négatif à un joueur !
