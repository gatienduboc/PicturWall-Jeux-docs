
.. _jeu-etat:

=====================================
États de Jeu et Affichage des Panels
=====================================

Ce document décrit les différents états du jeu et ce qui est affiché sur les trois panels : Animateur, Joueur et Board.

.. contents:: Table des matières
   :local:
   :depth: 1

.. _jeu-etat_init :

Initialisation
==============
**Description :**
Lors du mode *Initialisation*, le jeu n'a pas encore commencé.

+----------------------+--------------------------------------------+
| **Panel**            | **Affichage**                              |
+======================+============================================+
| Animateur            | Demande de sélection du questionnaire.     |
+----------------------+--------------------------------------------+
| Joueur               | "Aucun jeu en cours"                       |
+----------------------+--------------------------------------------+
| Board                | "Aucun jeu en cours" avec QR-Codes :       |
|                      | un pour se connecter au Wifi PicturWall,   |
|                      | l'autre pour accéder au site web.          |
+----------------------+--------------------------------------------+

.. figure:: /panel_animateur/_images/etat/initialisation.png
   :alt: Panel animateur - Initialisation
   :align: center
   :width: 80%
   :figclass: align-center

   **Panel Animateur en mode Initialisation**

.. figure:: /panel_board/_images/etat/initialisation.png
   :alt: Panel board - Initialisation
   :align: center
   :width: 80%
   :figclass: align-center

   **Panel Board en mode Initialisation**

.. figure:: /panel_joueur/_images/etat/initialisation.png
   :alt: Panel joueur - Initialisation
   :align: center
   :width: 50%
   :figclass: align-center

   **Panel Joueur en mode Initialisation**

.. note::
   Pour passer de l'état *Initialisation* à l'état *Prêt*, suivez ce lien : :ref:`Passer à Prêt <panel-animateur_jeu_etat_gestion-init_pret>`

----

.. _jeu-etat_pret :

Prêt
====
**Description :**
Le mode *Prêt* est affiché lorsque tout est configuré et que le jeu peut démarrer.

+----------------------+--------------------------------------------+
| **Panel**            | **Affichage**                              |
+======================+============================================+
| Animateur            | Nom du questionnaire, règles, et bouton    |
|                      | pour commencer la partie.                  |
+----------------------+--------------------------------------------+
| Joueur               | Nom, image du questionnaire et règles.     |
+----------------------+--------------------------------------------+
| Board                | Nom, image du questionnaire et règles.     |
+----------------------+--------------------------------------------+

.. figure:: /panel_animateur/_images/etat/pret.png
   :alt: Panel animateur - Prêt
   :align: center
   :width: 80%
   :figclass: align-center

   **Panel Animateur en mode Prêt**

.. figure:: /panel_board/_images/etat/pret.png
   :alt: Panel board - Prêt
   :align: center
   :width: 80%
   :figclass: align-center

   **Panel Board en mode Prêt**

.. figure:: /panel_joueur/_images/etat/pret.png
   :alt: Panel joueur - Prêt
   :align: center
   :width: 50%
   :figclass: align-center

   **Panel Joueur en mode Prêt**

.. attention::
   Pour passer de l'état *Prêt* à l'état *En Jeu*, suivez ce lien : :ref:`Passer à En Jeu <panel-animateur_jeu_etat_gestion-pret_jeu>`

----

.. _jeu-etat_jeu :

En Jeu
======
**Description :**
Pendant le mode *En Jeu*, les joueurs participent au quiz ou QCM.

En Jeu - Type Buzzer
--------------------
**Description :**
Le mode *En Jeu* pour un jeu de type buzzer où les joueurs doivent appuyer rapidement pour répondre.

+------------------+-------------------------------------------------+
| **Panel**        | **Affichage**                                   |
+==================+=================================================+
| Animateur        | Points des joueurs, question en cours, et       |
|                  | indication du/des joueurs les plus rapides.     |
+------------------+-------------------------------------------------+
| Joueur           | Question affichée avec la possibilité de        |
|                  | buzzer rapidement.                              |
+------------------+-------------------------------------------------+
| Board            | Affichage de la question en cours, nom du/des   |
|                  | joueurs les plus rapides, et tableau des scores.|
+------------------+-------------------------------------------------+

.. figure:: /panel_animateur/_images/etat/jeu_buzzer.png
   :alt: Panel animateur - Jeu type buzzer
   :align: center
   :width: 80%
   :figclass: align-center

   **Panel Animateur en mode Jeu type Buzzer**

.. figure:: /panel_board/_images/etat/jeu_buzzer.png
   :alt: Panel board - Jeu type buzzer
   :align: center
   :width: 80%
   :figclass: align-center

   **Panel Board en mode Jeu type Buzzer**

.. figure:: /panel_joueur/_images/etat/jeu_buzzer.png
   :alt: Panel joueur - Jeu type buzzer
   :align: center
   :width: 50%
   :figclass: align-center

   **Panel Joueur en mode Jeu type Buzzer**

----

En Jeu - Type QCM
------------------
**Description :**
Le mode *En Jeu* pour un jeu de type QCM où les joueurs doivent choisir parmi plusieurs options.

+------------------+------------------------------------------------+
| **Panel**        | **Affichage**                                  |
+==================+================================================+
| Animateur        | Points des joueurs, question en cours, et      |
|                  | les réponses possibles avec l'indication de    |
|                  | la bonne réponse.                              |
+------------------+------------------------------------------------+
| Joueur           | Question et choix multiples affichés.          |
+------------------+------------------------------------------------+
| Board            | Question et options de réponse affichées,      |
|                  | avec le tableau des scores à jour.             |
+------------------+------------------------------------------------+

.. figure:: /panel_animateur/_images/etat/jeu_qcm.png
   :alt: Panel animateur - Jeu type QCM
   :align: center
   :width: 80%
   :figclass: align-center

   **Panel Animateur en mode Jeu type QCM**

.. figure:: /panel_board/_images/etat/jeu_qcm.png
   :alt: Panel board - Jeu type QCM
   :align: center
   :width: 80%
   :figclass: align-center

   **Panel Board en mode Jeu type QCM**

.. figure:: /panel_joueur/_images/etat/jeu_qcm.png
   :alt: Panel joueur - Jeu type QCM
   :align: center
   :width: 50%
   :figclass: align-center

   **Panel Joueur en mode Jeu type QCM**

.. note::
   Pour passer du mode *En Jeu* au mode *Pause*, suivez ce lien : :ref:`Passer à Pause <panel-animateur_jeu_etat_gestion-jeu_pause>`
   Pour passer du mode *En Jeu* au mode *Partie Finie*, suivez ce lien : :ref:`Passer à Partie Finie <panel-animateur_jeu_etat_gestion-jeu_fini>`

----

.. _jeu-etat_pause :

Pause
=====
**Description :**
Le mode *Pause* fige le jeu temporairement.

+----------------------+--------------------------------------------+
| **Panel**            | **Affichage**                              |
+======================+============================================+
| Animateur            | Identique au mode *En Jeu*, mais sans      |
|                      | progression du temps.                      |
+----------------------+--------------------------------------------+
| Joueur               | "Pause" et incapacité de répondre.         |
+----------------------+--------------------------------------------+
| Board                | Question et réponses figées sans défilement|
|                      | du temps.                                  |
+----------------------+--------------------------------------------+

.. tip::
   Si une musique était diffusée pour cette question, elle sera stoppée jusqu'à la reprise du jeu.

.. figure:: /panel_animateur/_images/etat/pause.png
   :alt: Panel animateur - Pause
   :align: center
   :width: 80%
   :figclass: align-center

   **Panel Animateur en mode Pause**

.. figure:: /panel_board/_images/etat/pause.png
   :alt: Panel board - Pause
   :align: center
   :width: 80%
   :figclass: align-center

   **Panel Board en mode Pause**

.. figure:: /panel_joueur/_images/etat/pause.png
   :alt: Panel joueur - Pause
   :align: center
   :width: 50%
   :figclass: align-center

   **Panel Joueur en mode Pause**

.. important::
   Pour reprendre le jeu et passer de *Pause* à *En Jeu*, suivez ce lien : :ref:`Passer à En Jeu <panel-animateur_jeu_etat_gestion-pause_jeu>`

----

.. _jeu-etat_fini :

Partie Finie / Partie Arrêtée
=============================
**Description :**
Le mode *Partie Finie* ou *Partie Arrêtée* affiche le tableau des scores final.

+----------------------+--------------------------------------------+
| **Panel**            | **Affichage**                              |
+======================+============================================+
| Animateur            | Tableau des scores final.                  |
+----------------------+--------------------------------------------+
| Joueur               | Tableau des scores final.                  |
+----------------------+--------------------------------------------+
| Board                | Tableau des scores final.                  |
+----------------------+--------------------------------------------+

.. figure:: /panel_animateur/_images/etat/fini.png
   :alt: Panel animateur - Partie Finie / Arrêtée
   :align: center
   :width: 80%
   :figclass: align-center

   **Panel Animateur en mode Partie Finie / Partie Arrêtée**

.. figure:: /panel_board/_images/etat/fini.png
   :alt: Panel board - Partie Finie / Arrêtée
   :align: center
   :width: 80%
   :figclass: align-center

   **Panel Board en mode Partie Finie / Partie Arrêtée**

.. figure:: /panel_joueur/_images/etat/fini.png
   :alt: Panel joueur - Partie Finie / Arrêtée
   :align: center
   :width: 50%
   :figclass: align-center

   **Panel Joueur en mode Partie Finie / Partie Arrêtée**

.. tip::
   Pour réinitialiser le jeu et revenir à *Initialisation*, suivez ce lien : :ref:`Retour à Initialisation <panel-animateur_jeu_etat_gestion-jeu_fini>`
