---
layout: default
title: ShutterSlider
lang: fr_FR
pluginId: ShutterSlider
type: action
subtype: curseur
---

# Description

Ce widget pour commandes action/curseur permet de gérer le positionnement des ouvrants (volets et portes de garage) avec un visuel au rendu réaliste.

![{{page.pluginId}} - gif]({{site.baseurl}}/{{page.pluginId}}/img/{{page.pluginId}}.gif "{{page.pluginId}} - gif")

Pour rester dans le réalisme, le widget possède un paramètre permettant de prendre en compte le temps de décollement des lames afin que le visuel Jeedom corresponde à la position réelle du volet.

# Installation et mises à jour

## Avec le plugin Pimp my Jeedom

L'installation est aisée grâce au plugin [Pimp my Jeedom]({{site.market}}/index.php?v=d&plugin_id=4005){:target="\_blank"}, rendez vous sur la page du widget et cliquer sur le bouton **Installer**.

Pour appliquer le widget sur une ou plusieurs commandes, cliquer sur le bouton **Appliquer sur** et choisissez les commandes qui utiliseront le widget avant de cliquer sur **Valider**.

Le plugin vérifie automatiquement la disponibilité d'une mise à jour pour le widget et vous en informe directement dans Jeedom. En présence d'une mise à jour disponible, il suffit de se rendre sur la page du widget dans le plugin et cliquer sur le bouton **Mettre à jour**.

## Manuellement

Les fichiers peuvent être récupérés dans un dossier compressé via ce lien : [{{page.pluginId}}_Widget-Jeedom.zip](https://github.com/Salvialf/JEEDOM-Widget-{{page.pluginId}}/raw/master/{{page.pluginId}}_WidgetJeedom.zip).

Les répertoires `dashboard` et `mobile`(si disponible) doivent être copiés dans le répertoire `data/customTemplates/` à l'aide du plugin *JeeXplorer*.

Appliquer le widget sur une commande action/curseur à partir de l’onglet *Affichage* de la configuration de la commande, en choisissant **Customtemp/{{page.pluginId}}** dans le menu déroulant.

En cas de mise à jour du code du widget il est nécessaire de télécharger les nouveaux fichiers et de les copier dans le répertoire `data/customTemplates/` en remplacement des anciens fichiers.

# Les paramètres optionnels

## Liste des paramètres disponibles

* ### image
Permet de choisir l'image de fond parmis les 16 disponibles : **bay_white, bay_white2, bay_black, bay_black2, bay_wood, bay_wood2, window, window1, window2, window3, window4, velux, garage, garage1, garage2, garage3**.  *(bay_white par défaut)*
> **A savoir**    
Il est possible d'inclure les images de fond de son choix en plaçant le(s) fichier(s) `*.png` dans le répertoire **/data/img/ShutterSlider/**.

* ### offset
Permet de prendre en compte le temps de décollement des lames. *(null par défaut)*
> **Usage**    
Positionner le volet à environ 1% d’ouverture physique. Le pourcentage de décollement correspond à la valeur d’ouverture qui apparaît alors sur le widget. Renseigner cette valeur pour le paramètre **offset**.

* ### rails
Pour choisir le style des lames parmis les 3 disponibles : **light, dark, wood**. *(light par défaut)*

* ### handle
Pour choisir le style de la première lame qui permet le déplacement de l'ouvrant : **light, dark, wood**. *(dark par défaut)*

* ### height
Valeur en pixels permettant de modifier la hauteur du widget. *(90 par défaut)*

* ### width
Valeur en pixels permettant de modifier la largeur du widget. *(90 par défaut)*

* ### invert
Pour inverser le positionnement de l'ouvrant sur les équipements qui le nécessitent. **checked** ou **unchecked** *(unchecked par défaut)*

* ### position
Pour afficher ou non la position sous le visuel. **checked** ou **unchecked** *(checked par défaut)*

* ### time
Pour visualiser les informations de temps depuis le dernier changement d'état. 3 formats sont possibles : **duration** affiche la durée, **date** affiche le jour et l'heure, **hour** affiche l'heure avec les secondes du dernier changement d'état. *(off par défaut)*

* ### CSS-time
Permet de personnaliser la présentation du paramètre **time** en code CSS.

## Avec le plugin Pimp my Jeedom

Le plugin [Pimp my Jeedom]({{site.market}}/index.php?v=d&plugin_id=4005){:target="\_blank"} rend l'usage et la configuration des paramètres optionnels très simple et rapide.

Rendez vous sur la page du widget dans le plugin. Sélectionnez la commande que vous souhaitez personnaliser en cochant la case présente juste avant le nom de la commande pour ouvrir le panneau de personnalisation :

![{{page.pluginId}} - Params_pimpJeedom]({{site.baseurl}}/{{page.pluginId}}/img/{{page.pluginId}}_Params_pimpJeedom.png "{{page.pluginId}} - Params_pimpJeedom")

## Manuellement

Pour appliquer de nouveaux paramètres optionnels, il faut se rendre dans la configuration de la commande puis onglet *Affichage* -> **Paramètres optionnels widget**.    
Cliquez sur **Ajouter** et renseigner le nom et la valeur de chaque paramètre :

![{{page.pluginId}} - Params_exemple]({{site.baseurl}}/{{page.pluginId}}/img/{{page.pluginId}}_Params_Example.png "{{page.pluginId}} - Params_exemple")

# Sur le forum

[Accéder au sujet sur le forum](https://community.jeedom.com/t/salvialf-widget-shutterslider-action-curseur/22380){:target="\_blank"}

# Changelog

[Voir le changelog]({{site.baseurl}}/{{page.pluginId}}/{{page.lang}}/changelog)
