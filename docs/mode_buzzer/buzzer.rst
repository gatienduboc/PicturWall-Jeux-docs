
.. _mode_buzzer:

===============================
Jeu en mode Buzzer
===============================

Lorsque l'animateur a choisi un jeu en mode buzzer : :ref:`changer de mode de jeu <panel-animateur_parametre-mode_de_jeu>`, l'interface de jeu est sous cette forme :

.. figure:: /panel_joueur/_images/etat/jeu_buzzer.png
   :alt: Panel Joueur - Jeu en mode buzzer
   :align: center
   :width: 30%
   :figclass: align-center

   **Panel joueur en mode Buzzer**

.. figure:: /panel_animateur/_images/etat/jeu_buzzer.png
   :alt: Panel Animateur - Jeu en mode buzzer
   :align: center
   :width: 80%
   :figclass: align-center

   **Panel animateur en mode Buzzer**

.. figure:: /panel_board/_images/etat/jeu_buzzer.png
   :alt: Panel Board - Jeu en mode buzzer
   :align: center
   :width: 80%
   :figclass: align-center

   **Panel board en mode Buzzer**

.. _mode_buzzer_joueur:

Panel Joueur
===============================

L'interface joueur est découpée de la sorte : 

.. figure:: /panel_joueur/_images/buzzer.png
   :alt: Panel Joueur - Jeu en mode buzzer
   :align: center
   :width: 50%
   :figclass: align-center

   **Panel Joueur en mode Buzzer**

**De haut en bas :**

* Affichage de la position du joueur et son nombre de points : **Vous êtes xième, avec y point**
* Affichage du temps restant avant la prochaine question : **Temps restant : xxxx / yyyy secondes**
* Affichage de la Question
* Buzzer
* Phrase d'aide si le joueur n'a pas comprit que c'était un buzzer :)

Voici ce que le joueur voit quand il a buzzé : 

.. figure:: /mode_buzzer/_images/joueur_buzzé.png
   :alt: Panel Joueur - Jeu en mode buzzer
   :align: center
   :width: 30%
   :figclass: align-center

   **Panel Joueur : le joueur a buzzé**

Si quelqu'un a buzzé avant lui, il sera en file d'attente

.. figure:: /mode_buzzer/_images/joueur_buzzé_file.png
   :alt: Panel Joueur - Jeu en mode buzzer
   :align: center
   :width: 30%
   :figclass: align-center

   **Panel Joueur : le joueur a buzzé mais est en file d'attente**

.. note::
   La file d'attente peut-être composée de 5 joueurs. Lorsque cette limite est atteinte, les autres buzzers seront désactivées. Lorsque place se libère, les buzzers sont réactivés jusqu'à re-atteindre 5 joueurs.

Ensuite, s'il a mal répondu, son buzzer sera bloqué jusqu'à la prochaine question :

.. figure:: /mode_buzzer/_images/joueur_buzzé_mauvais.png
   :alt: Panel Joueur - Jeu en mode buzzer, mauvais buzz
   :align: center
   :width: 30%
   :figclass: align-center

   **Panel Joueur : le joueur a mal répondu à la question**

En revanche s'il répond bien, l'ensemble des buzzers afficheront la bonne réponse dans l'encart du buzzer *(en violet)*. Ils auront un décompte jusqu'à la prochaine question, et leurs nombres de point(s) gagné(s) grâce à cette question seront affichés : 

.. figure:: /mode_buzzer/_images/joueur_buzzé_bon.png
   :alt: Panel Joueur - Jeu en mode buzzer bon buzz
   :align: center
   :width: 30%
   :figclass: align-center

   **Panel Joueur : le joueur a bien répondu, l'ensemble des buzzers affichent la bonne réponse**

.. _mode_buzzer_board:

Panel Board
===============================

L'interface board est découpée de la sorte : 

.. figure:: /mode_buzzer/_images/board.png
   :alt: Panel Board - Jeu en mode buzzer
   :align: center
   :width: 100%
   :figclass: align-center

   **Panel Board en mode Buzzer**

**De haut en bas :**

* Barre défilante du temps restant
* Affichage de la question
* Liste des joueurs en file d'attente. Il sont dans l'ordre du premier au dernier ayant buzzé

Le joueur en jaune est donc celui qui doit répondre à la question, tandis que le joueur en dessous doit se préparer à répondre si le premier à faux.

Si l'animateur refuse la question d'un joueur, son pseudo apparaîtra brièvement en rouge, et le joueur du dessous passera en jaune : 

.. figure:: /mode_buzzer/_images/board_refusé.png
   :alt: Panel Board - Jeu en mode buzzer, joueur refusé
   :align: center
   :width: 100%
   :figclass: align-center

   **Panel Board : joueur refusé**

Lorsque l'animateur a validé la réponse d'un joueur, l'affichage sur le board est le suivant : 

.. figure:: /mode_buzzer/_images/board_reponses.png
   :alt: Panel Board - Jeu en mode buzzer, affichage de la réponse
   :align: center
   :width: 100%
   :figclass: align-center

   **Panel Board : Affichage des réponses**

Le joueur ayant bien répondu est le seul restant à l'écran, et la réponse attendue est marquée en vert.

.. _mode_buzzer_animateur:

Panel Animateur
===============================

L'interface animateur est découpée de la sorte : 

.. figure:: /mode_buzzer/_images/animateur.png
   :alt: Panel Animateur - Jeu en mode buzzer
   :align: center
   :width: 100%
   :figclass: align-center

   **Panel Animateur en mode Buzzer**

**De haut en bas :**

* :ref:`Le menu <panel-animateur_menu>`
* :ref:`La barre d'action <panel-animateur_jeu_barre_action>`
* Ensuite, l'écran est séparée en deux parties :
   * A gauche, la gestion de la question en cours
   * A droite, le :ref:`tableau des scores <panel-animateur_jeu_scoreboard>`

Maintenant, focalisons nous sur la partie de gestion de la question courante :

.. figure:: /mode_buzzer/_images/animateur_specifique.png
   :alt: Panel Animateur - Spécificité du mode buzzer
   :align: center
   :width: 100%
   :figclass: align-center

   **Panel Animateur : Gestion de la question courante**

**De haut en bas :**

* Affichage du temps restant, avec deux boutons pour ajouter ou retirer du temps
* La question en cours
* L'index de la question et le nombre total de question
* Une story (histoire) sur cette question
* Le nombre de joueur ayant répondu / le nombre total de joueur (et le nombre de joueur manquant)
* La liste des joueurs ayant buzzé, à gauche celui qui a buzzé en premier
* Deux boutons :
   * l'un pour accepter la réponse, donner les points au joueur et passer à la question suivantes
   * L'autre pour refuser la question, bloquer le buzzer du joueur et passer à "Joueur 2"
* La bonne réponse