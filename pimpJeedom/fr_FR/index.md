---
layout: default
title: Pimp my Jeedom
lang: fr_FR
pluginId: pimpJeedom
---

# Description

Plugin pour personnaliser Jeedom.

Permet d'installer, de modifier ou de supprimer les widgets tiers ainsi que les widgets réalisés par Salvialf.

# Installation et accès

Comme tout plugin Jeedom, celui-ci doit être installé et activé.

Ensuite rendez vous dans *Plugins->Programmation->Pimp my Jeedom* pour l'utiliser.

>**Info**      
>Le plugin utilise un *cronDaily* afin de vérifier la présence d'une mise à jour pour les widgets "made by Salvialf". En cas de besoin celui-ci peut être désactivé sur la page de configuration du plugin (*Plugins->Gestion des plugins->Pimp my Jeedom*).

# Utilisation

## Widgets tiers

A l'accès au plugin, vous arrivez sur l'onglet *Général*.

Le plugin liste automatiquement l'ensemble des widgets tiers présents dans le répertoire *data/customTemplates* en les regroupant par version *(dashboard | mobile)* :    
![Widgets Tiers - Général](../img/general.png "Widgets Tiers - Général")

### Ajouter un widget Tiers

Pour ajouter un widget tiers cliquez sur le bouton **"Ajouter un Widgets Tiers"** :    
![Widgets Tiers - Ajouter](../img/AddThirdWidget.png "Widgets Tiers - Ajouter")

Une fenêtre s'ouvre afin de renseigner les caractéristiques du nouveau widget *(Nom, Version, Type, Sous-Type)*, Validez en cliquant sur le bouton **Créer** :    
![Widgets Tiers - Nouveau](../img/NewThirdWidget.png "Widgets Tiers - Nouveau")

Le nouveau widget est enregistré et vous arrivez directement sur la page de gestion de ce widget :   
![Widgets Tiers - Détails](../img/PageThirdWidget.png "Widgets Tiers - Détails")

### Gérer un widget Tiers

Pour accéder aux détails d'un widget tiers il suffit de cliquer dessus au sein de l'onglet *Général*. Vous arrivez alors sur la page de gestion du widget :    
![Widgets Tiers - Gestion](../img/ThirdWidget.png "Widgets Tiers - Gestion")

La page est divisée en plusieurs parties :
* **Général** :
Permet de modifier les propriétés du widget *(Nom, Version, Type, Sous-Type)*.

* **Commandes liées** :
Pour connaitre les commandes sur lesquelles le widget est appliqué.
>**Astuce**   
>Cliquez sur le nom de la commande pour accéder directement à ses paramètres de configuration.

* **Prévisualisation** :
Permet de visualiser le rendu du widget.

* **Édition** :
Pour voir et modifier le code du widget.

* **Boutons du menu**:
  * **Appliquer sur** : Pour choisir les commandes sur lesquelles appliquer ou désappliquer le widget.
  * **Ajouter des fichiers** : Pour ajouter ou supprimer des fichiers au widget.
  * **Sauvegarder** : Pour sauvegarder les modifications faites sur le widget.
  * **Supprimer** : Pour supprimer le widget.





## Widgets made by Salvialf
