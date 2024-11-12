.. _panel-animateur_parametres:

Paramètres
==================================

Afin de pouvoir personaliser vos parties de jeu, un certains nombres de paramètres ont été mis en place.
Pour cela, rendez-vous sur l'URL suivante : `picturwall.tv/admin-parametres <https://picturwall.tv/admin-parametres>`_

.. tip::
    Il existe un environnement de test hébergé sur internet à l'adresse suivante : `Environnement de test <http://cluster01.gatien-duboc.fr:3001/admin-parametres>`_

.. important::
   L'interface a été déssiné pour être utilisé sur un écran d'ordinateur au format paysage. Il peut aussi être utilisé via une tablette de minimum 10" en format paysage.

L'interterface des paramètres ressemble à cela : 

.. figure:: /panel_animateur/_images/parametres/animateur_parametre_buzzer.png
   :alt: Panel Animateur - Page Paramètre : Mode Buzzer
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page paramètre - Mode Buzzer**

.. figure:: /panel_animateur/_images/parametres/animateur_parametre_qcm.png
   :alt: Panel Animateur - Page Paramètre : Mode QCM
   :align: center
   :width: 100%
   :figclass: align-center

**Panel Animateur : Page paramètre - Mode QCM**

.. _panel-animateur_parametres-basculer_picturwall:

Basculer en "Mode PicturWall"
-------------------------------------

Pour basculer en mode PicturWall, il vous suffit de cliquer sur "Mode PicturWall" puis de patienter 10 secondes. Vous serez automatiquement redirigé une fois la bascule terminée.

.. figure:: /panel_animateur/_images/parametres/animateur_parametre_changer_mode.png
   :alt: Panel Animateur - Page Paramètre : Basculer en mode PicturWall
   :align: center
   :width: 100%
   :figclass: align-center

   **Panel Animateur : Page paramètre - Basculer en mode PicturWall**

.. note:: 
    Vous ne pouvez pas basculer en "Mode Photo" sur l'interface de démo.

.. _panel-animateur_parametre-mode_de_jeu:

Changer de type de jeu
-------------------------------------

Plusieurs type de jeux sont disponibles sur PicturWall :
* :ref:`QCM <mode_qcm>`
* :ref:`Buzzer <mode_buzzer>`
* Sondage (en cours de développement)

.. figure:: /panel_animateur/_images/parametres/animateur_parametre_type.png
   :alt: Panel Animateur - Page Paramètre : Changer de type de jeu
   :align: center
   :width: 100%
   :figclass: align-center

   **Panel Animateur : Page paramètre - Changer de type de jeu**


.. _panel-animateur_parametre-pseudo:

Pseudo / Nom prénoms pour les inscriptions
----------------------------------------------

Vous pouvez demander soit un pseudo à l'inscription des joueurs, soit un couple prénom / nom :

.. figure:: /panel_animateur/_images/parametres/animateur_parametre_pseudo.png
   :alt: Panel Animateur - Page Paramètre : Pseudo ou couple prénom / nom
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page paramètre - Pseudo ou couple Prénom/nom pour les inscriptions des joueurs**


.. note::
    En CE, vous préferez peut-être avoir le nom et prenoms des convives, alors qu'en soirée type mariage un pseudo peut-être plus adapté.

.. _panel-animateur_parametre-temps:

Temps par question
----------------------------------------------

Vous pouvez choisir le nombre de secondes par question :

.. figure:: /panel_animateur/_images/parametres/animateur_parametre_temps.png
   :alt: Panel Animateur - Page Paramètre : Temps / question
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page paramètre - Temps par question**


.. important::
    Il faut penser à cliquer sur "Définir" lorsque vous aurez complété le nombres de secondes voulues.


.. _panel-animateur_parametre-pause:

Mettre le jeu en mode pause à chaque nouvelle question
----------------------------------------------------------------------------

Paramètre servant à passer automatiquement le jeu en pause à chaque nouvelle question.
Cela peut servir pour expliquer la question aux joueurs avant qu'ils se ruent à répondre

.. figure:: /panel_animateur/_images/parametres/animateur_parametre_pause.png
   :alt: Panel Animateur - Page Paramètre : Pause a chaque nouvelle question
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page paramètre - Pause à chaque nouvelle question**


.. note::
    Paramètre uniquement disponible en mode "QCM"



.. _panel-animateur_parametre-regles:

Règles
----------------------------------------------

Vous pouvez définir vos propres règles de jeu. Entre chaque règle, vous devez faire un retour à la ligne (Toucher "Entrée").

.. figure:: /panel_animateur/_images/parametres/animateur_parametre_regles.png
   :alt: Panel Animateur - Page Paramètre : Règles
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page paramètre - Règles**

.. important::
    Il faut penser à cliquer sur "Définir" lorsque vous aurez complété les règles.


.. _panel-animateur_parametre-qcm-prochaine_question:

(Spécifique QCM) : Passer automatiquement à la question suivante
----------------------------------------------------------------------------

Paramètre servant à passer automatiquement à la question suivante lorsque tous les joueurs ont répondu à la question.

.. figure:: /panel_animateur/_images/parametres/animateur_parametre_qcm_question_suivante.png
   :alt: Panel Animateur - Page Paramètre : Passer automatiquement à la question suivante
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page paramètre - Passage automatique à la question suivante**


.. note::
    Paramètre uniquement disponible en mode "QCM"


.. _panel-animateur_parametre-qcm-doubler_points:

(Spécifique QCM) : Doubler les points pour le premier répondant
----------------------------------------------------------------------------

Paramètre servant à doubler les points de la question au premier répondant (sans faute) à une question

.. figure:: /panel_animateur/_images/parametres/animateur_parametre_qcm_points_double.png
   :alt: Panel Animateur - Page Paramètre : Règles
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page paramètre - Doubler les points du premier répondant**

.. note::
    Paramètre uniquement disponible en mode "QCM"



.. _panel-animateur_parametre-qcm-valider_reponses:

(Spécifique QCM) : Valider automatiquement les réponses
----------------------------------------------------------------------------

Paramètre servant à valider automatiquement les réponses d'un joueur.
Les réponses seront valider uniquement lorsque le joueur à cliqué sur autant de réponses qu'il y a de réponses attendues à cette question.

.. figure:: /panel_animateur/_images/parametres/animateur_parametre_qcm_valider.png
   :alt: Panel Animateur - Page Paramètre : Règles
   :align: center
   :width: 100%
   :figclass: align-center

   **Panel Animateur : Page paramètre - Valider automatiquement les réponses des joueurs**


.. note::
    Paramètre uniquement disponible en mode "QCM"






