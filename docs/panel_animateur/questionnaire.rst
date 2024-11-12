.. _panel-animateur_questionnaire:

Gestion des questionnaires
=======================================

Afin de pouvoir personaliser vos questionnaires, un certains nombre de mécanisme ont été mit en place.
Pour cela, rendez-vous sur l'URL suivante : `picturwall.tv/admin-questionnaires <https://picturwall.tv/admin-questionnaires>`_

.. tip::
    Il existe un environnement de test hébergé sur internet à l'adresse suivante : `Environnement de test <http://cluster01.gatien-duboc.fr:3001/admin-questionnaires>`_

.. important::
   L'interface a été déssiné pour être utilisé sur un écran d'ordinateur au format paysage. Il peut aussi être utilisé via une tablette de minimum 10" en format paysage.

L'interterface des questionnaire ressemble à cela : 

.. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire.png
   :alt: Panel Animateur - Page Questionnaire
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page questionnaire**

.. note::
    Vous pouvez uniquement intéragir les questionnaire du mode de jeu courant. Le mode de jeu courant est écrit juste après Gestion des Questionnaires (mode de jeu)

.. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire_gestion_quizz.png
   :alt: Panel Animateur - Page Questionnaire : Gestion Quizz
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page questionnaire - Mode Quizz**

.. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire_gestion_qcm.png
   :alt: Panel Animateur - Page Questionnaire : Gestion QCM
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page questionnaire - Mode QCM**

----

.. _panel-animateur_questionnaire-modifier:

Modifier un questionnaire
------------------------------------------

Afin de modifier un questionnaire, il faut déjà le sélectionner :

.. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire_selectionner.png
   :alt: Panel Animateur - Page Questionnaire : Sélectionner un questionnaire
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page questionnaire - Sélectionner un questionnaire**

Ensuite, si vous êtes en mode QCM, vous allez voir une page qui ressemble à cela : 

.. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire_gestion_qcm.png
   :alt: Panel Animateur - Page Questionnaire : Gestion QCM
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page questionnaire - Mode QCM**

La page est découpée en plusieurs parties. De haut en bas :

 * :ref:`Le menu <panel-animateur_menu>`
 * Le nom de la page, avec l'indication du mode de jeu entre parenthèse
 * :ref:`Le nom <panel-animateur_questionnaire-gestion_nom>` et :ref:`L'image <panel-animateur_questionnaire-gestion_image>` associée au questionnaire
 * :ref:`Une barre d'action <panel-animateur_questionnaire-gestion_action>`
 * :ref:`Un tableau avec les questions et réponses associées <panel-animateur_questionnaire-gestion_modification>`
 * Un bouton pour ajouter une nouvelle question (tout en bas)

.. _panel-animateur_questionnaire-gestion_nom:

Edition du nom d'un questionnaire:
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Vous pouvez re-définir le nom de votre questionnaire :

.. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire_gestion_nom.png
   :alt: Panel Animateur - Page Questionnaire : Gestion du nom
   :align: center
   :width: 100%
   :figclass: align-center

   **Panel Animateur : Page questionnaire - Edition du nom**

.. _panel-animateur_questionnaire-gestion_image:

Edition de l'image d'un questionnaire:
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Vous pouvez re-définir l'image de votre questionnaire :

.. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire_gestion_image.png
   :alt: Panel Animateur - Page Questionnaire : Gestion de l'image
   :align: center
   :width: 100%
   :figclass: align-center

   **Panel Animateur : Page questionnaire - Edition de l'image**

.. _panel-animateur_questionnaire-gestion_action:

Barre d'action d'un questionnaire:
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire_gestion_action.png
   :alt: Panel Animateur - Page Questionnaire : Barre d'action
   :align: center
   :width: 100%
   :figclass: align-center

   **Panel Animateur : Page questionnaire - Barre d'action**

Sur la barre d'action d'un questionnaire, vous avez plusieurs bouton (de gauche à droite) :

* Enregistrer le questionnaire
* Supprimer le questionnaire
* :ref:`Exporter le questionnaire<panel-animateur_questionnaire-exporter_un>`
* Mélanger les réponses (uniquement disponible en mode QCM)
* Retour dans enregistrer les modifitions apportées au questionnaire

.. _panel-animateur_questionnaire-gestion_modification:

Modification d'un question ou d'une réponse:
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire_gestion_question_reponse.png
   :alt: Panel Animateur - Page Questionnaire : Barre d'action
   :align: center
   :width: 100%
   :figclass: align-center

   **Panel Animateur : Page questionnaire - Modifier une question ou une réponse**

Pour chaque **question**, vous pouvez :

* Modifier son **texte**
* Associer une **image** à cette question (uniquement diffusé sur le board) **-> Format .png**
* Associer un **audio** à cette question (uniquement diffusé sur le board) **-> Format .mp3**
* Ajouter une **story** (une histoire pour développer la réponse)
* Définir le **nombre de points** pour la question
* Modifier la **position de la question** dans le questionnaire (grâce au burger situé à gauche du texte de la question)

Pour chaque **réponse**, vous pouvez :

* Indiquer si la réponse est vraie ou fausse (grâce à la coche)
* Modifier son **texte**
* Associer une **image** à cette question (uniquement diffusé sur le board)
* Modifier la **position de la réponse** dans la question (grâce au burger situé à gauche du texte de la réponse)
* **Ajouter une réponse** si le nombre de réponse est inférieure à 4 (et que c'est un questionnaire mode QCM)


.. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire_gestion_reponse.png
   :alt: Panel Animateur - Page Questionnaire : Gestion des réponses
   :align: center
   :width: 100%
   :figclass: align-center

   **Panel Animateur : Page questionnaire - Modifier une réponse**

.. important::
   En mode Quizz, vous avez une seule réponse possible, et vous ne pouvez pas y associer d'image

   .. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire_gestion_quizz.png
      :alt: Panel Animateur - Page Questionnaire : Gestion des Quizz
      :align: center
      :width: 100%
      :figclass: align-center

   **Panel Animateur : Page questionnaire - Mode Quizz**   

----

.. _panel-animateur_questionnaire-ajout:

Ajout d'un nouveau questionnaire
------------------------------------------

Afin d'ajouter un nouveau questionnaire, il suffit de cliquer sur "Ajout d'un nouveau questionnaire", de compléter à minimum le nom et la photo du questionnaire et de cliquer sur "Enregistrer"

.. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire_action.png
   :alt: Panel Animateur - Page Questionnaire : Bandeau d'actions
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page questionnaire - Bandeau d'actions**


.. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire_ajout.png
   :alt: Panel Animateur - Page Questionnaire : Ajout d'un questionnaire
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page questionnaire - Ajout d'un questionnaire**

----


.. _panel-animateur_questionnaire-exporter_un:

Exporter un questionnaire
------------------------------------------

Afin d'exporter un seul questionnaire, il suffit de le sélectionner puis de cliquer sur le bouton bleu "Exporter"

.. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire_selectionner.png
   :alt: Panel Animateur - Page Questionnaire : Sélectionner un questionnaire
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page questionnaire - Sélectionner un questionnaire**

.. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire_gestion_action.png
   :alt: Panel Animateur - Page Questionnaire : Edition Questionnaire - Export
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page questionnaire - Exporter un questionnaire**

.. note::
    Lorsque vous exportez un questionnaire : les sons et images associées au questionnaire sont aussi exportées

----

.. _panel-animateur_questionnaire-exporter_tout:

Exporter tout les questionnaires
------------------------------------------

Afin d'exporter tout les questionnaires, il suffit de cliquer sur "Exporter tout les questionnaires", un nouvau fichier sera téléchargé contenant l'ensemble des questionnaires de votre mode de jeu courant.

.. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire_action.png
   :alt: Panel Animateur - Page Questionnaire : Bandeau d'actions
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page questionnaire - Bandeau d'actions**

.. important::
    Attention, opération à répéter pour chacun des modes de jeu


.. note::
    Lorsque vous exportez tout les questionnaires : les sons et images associées sont aussi exportées

----

.. _panel-animateur_questionnaire-import:

Importer un/des questionnaire(s) : Format JSON
---------------------------------------------------------------

Afin d'importer un questionnaire, vous devez cliquer sur le bouton "Importer des questionnaires" puis sélectionner votre fichier au format .json

.. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire_action.png
   :alt: Panel Animateur - Page Questionnaire : Bandeau d'actions
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page questionnaire - Bandeau d'actions**

.. note::
    Prenez garde à sélectionner le mode de jeu dans lequel vous voulez importer votre questionnaire.

.. note::
    Lorsque vous importer un questionnaire : les sons et images associées au questionnaire sont aussi importées

----

.. _panel-animateur_questionnaire-import_openquizzdb:

Importer un/des questionnaire(s) : OpenQuizzDB
--------------------------------------------------------------

Afin d'importer un questionnaire, vous devez cliquer sur le bouton "Importer des questionnaires" puis sélectionner votre fichier OpenQuizzDB au format .json

.. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire_action.png
   :alt: Panel Animateur - Page Questionnaire : Bandeau d'actions
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page questionnaire - Bandeau d'actions**

Maintenant, sélectionner le niveau que vous voulez importer : 

.. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire_openquizzdb_import.png
   :alt: Panel Animateur - Page Questionnaire : Bandeau d'actions
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page questionnaire - Importer questionnaire OpenQuizzDB**

.. important::
    Les questionnaires OpenQuizzDB sont téléchargeables ici : `OpenQuizzDB <https://www.openquizzdb.org/>`_

.. _panel-animateur_questionnaire-import_excel:

----

Importer un/des questionnaire(s) : Excel
---------------------------------------------------

Vous pouvez également importer des questionnaires au format Excel !! Pour cela, vous pouvez télécharger le patron via le lien "Télécharger un exemple de questionnaire"

.. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire_action_excel.png
   :alt: Panel Animateur - Page Questionnaire : Bandeau d'actions avec import Excel
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page questionnaire - Import de questionnaire au format Excel**

.. important::
    Vous pourrez importer des images et sons en modifiant le questionnaire.

Import questionnaire QCM :
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

En mode QCM, complétez le fichier de la sorte : 

.. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire_import_excel_qcm.png
   :alt: Panel Animateur - Page Questionnaire : Import de questionnaire EXCEL mode QCM
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page questionnaire - Import de questionnaire EXCEL mode QCM**


.. important::
    "Les réponses correctes" doivent être séparées par des virgules.

.. note::
    Vous n'êtes pas obligé de remplir toutes les réponses.


Import questionnaire Buzzer :
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
En mode Buzzer, complétez le fichier de la sorte : 

.. figure:: /panel_animateur/_images/questionnaires/animateur_questionnaire_import_excel_quizz.png
   :alt: Panel Animateur - Page Questionnaire : Import de questionnaire EXCEL mode Quizz
   :align: center
   :width: 100%
   :figclass: align-center
   
   **Panel Animateur : Page questionnaire - Import de questionnaire EXCEL mode Quizz**

.. note::
    Vous devez uniquement remplir la première case réponse et laisser les colonnes réponses 2 à 4 et réponses correctes vides

