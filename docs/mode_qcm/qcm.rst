
.. _mode_qcm:

===============================
Jeu en mode QCM
===============================

Lorsque l'animateur a choisi un jeu en mode QCM : :ref:`changer de mode de jeu <panel-animateur_parametre-mode_de_jeu>`, l'interface de jeu est sous cette forme :

.. figure:: /panel_joueur/_images/etat/jeu_qcm.png
   :alt: Panel Joueur - Jeu en mode QCM
   :align: center
   :width: 30%
   :figclass: align-center

   **Panel joueur en mode QCM**

.. figure:: /panel_animateur/_images/etat/jeu_qcm.png
   :alt: Panel Animateur - Jeu en mode QCM
   :align: center
   :width: 80%
   :figclass: align-center

   **Panel animateur en mode QCM**

.. figure:: /panel_board/_images/etat/jeu_qcm.png
   :alt: Panel Board - Jeu en mode QCM
   :align: center
   :width: 80%
   :figclass: align-center

   **Panel board en mode QCM**

.. _mode_qcm_joueur:

Panel Joueur
===============================

L'interface joueur est découpée de la sorte : 

.. figure:: /panel_joueur/_images/qcm.png
   :alt: Panel Joueur - Jeu en mode QCM
   :align: center
   :width: 50%
   :figclass: align-center

   **Panel Joueur en mode QCM**

**De haut en bas :**

* Affichage de la position du joueur et son nombre de points : **Vous êtes xième, avec y point**
* Affichage du temps restant avant la prochaine question : **Temps restant : xxxx / yyyy secondes**
* Affichage de la Question
* Affichage du / des réponses
* Bouton pour valider les choix ():ref:`si la validation des choix n'est pas en mode automatique <panel-animateur_parametre-choix>`)

Voici ce que le joueur voit quand il a appuyé sur un choix : 

.. figure:: /mode_qcm/_images/joueur_coche.png
   :alt: Panel Joueur - Jeu en mode QCM
   :align: center
   :width: 30%
   :figclass: align-center

   **Panel Joueur : le joueur a sélectionné un choix mais n'a pas validé**

Si le joueur valide ses réponses :

.. figure:: /mode_qcm/_images/joueur_envoye.png
   :alt: Panel Joueur - Jeu en mode QCM, choix envoyé
   :align: center
   :width: 30%
   :figclass: align-center

   **Panel Joueur : le joueur a validé ses choix**
   
.. note::
   Si l'animateur décide de :ref:`valider automatiquement le choix des joueurs <panel-animateur_parametre-choix>`, l'interface côté joueur sera figée lorsque l'utilisateur aura sélecitonnée le nombre de réponses attendues.


Lorsque le temps est écoulé, que tout les joueurs ont répondu à la question (:ref:`si le passage automatique à la prochaine question est sélectionnée <panel-animateur_parametres-prochaine_question>`), ou que l'animateur
a choisi de passer à la prochaine question, nous voyons ceci côté joueur : 

.. figure:: /mode_qcm/_images/joueur_reponses.png
   :alt: Panel Joueur - Jeu en mode QCM, Affuchage des réponses
   :align: center
   :width: 30%
   :figclass: align-center

   **Panel Joueur : affichage des réponses**

Les bonnes réponses sont affichées en vert, les mauvaises en rouge. Le nombre de point(s) gagné(s) par le joueur s'affiche pendant un court instant au centre de son écran.


.. _mode_qcm_board:

Panel Board
===============================

L'interface board est découpée de la sorte : 

.. figure:: /mode_qcm/_images/board.png
   :alt: Panel Board - Jeu en mode QCM
   :align: center
   :width: 100%
   :figclass: align-center

   **Panel Board en mode QCM**

.. figure:: /mode_qcm/_images/board_images.png
   :alt: Panel Board - Jeu en mode QCM, avec des images
   :align: center
   :width: 100%
   :figclass: align-center

   **Panel Board en mode QCM avec des images dans la question et certaines réponses**

**De haut en bas :**

* Barre défilante du temps restant
* Affichage de la question
* Affichage des réponses

Lorsque le temps est écoulé, que tout les joueurs ont répondu à la question (:ref:`si le passage automatique à la prochaine question est sélectionnée <panel-animateur_parametres-prochaine_question>`), ou que l'animateur
a choisi de passer à la prochaine question, nous voyons ceci côté board : 

.. figure:: /mode_qcm/_images/board_reponses.png
   :alt: Panel Joueur - Jeu en mode QCM, Affichage des réponses
   :align: center
   :width: 30%
   :figclass: align-center

   **Panel Board : affichage des réponses**

Les bonnes réponses sont affichées en vert, les mauvaises en rouge.

.. _mode_qcm_animateur:

Panel Animateur
===============================

L'interface animateur est découpée de la sorte, de haut en bas : 

.. figure:: /mode_qcm/_images/animateur.png
   :alt: Panel Animateur - Jeu en mode qcm
   :align: center
   :width: 100%
   :figclass: align-center

   **Panel Animateur en mode QCM**

* :ref:`Le menu <panel-animateur_menu>`
* :ref:`La barre d'action <panel-animateur_jeu_barre_action>`
* Ensuite, l'écran est séparée en deux parties :
   * A gauche, la gestion de la question en cours
   * A droite, le :ref:`tableau des scores <panel-animateur_jeu_scoreboard>`

Maintenant, focalisons nous sur la partie de gestion de la question courante :

.. figure:: /mode_qcm/_images/animateur_specifique.png
   :alt: Panel Animateur - Spécificité du mode qcm
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
* L'affichage des réponses
   * Les bonnes réponses sont en vert
   * Les mauvaises réponses sont en rouge
   * Nous vyons d'indiqué le premier joueur ayant répondu cette réponse, ainsi que le % de joueur ayant répondu cette réponse

.. important::
   Si un joueur sélectionne les bonnes réponses mais avec une mauvaise en +, il ne sera pas considéré comme étant le premier à avoir répondu à la question. Il n'aura d'ailleurs pas de point pour cette question.