---
layout: default
title: ColorSlider
lang: fr_FR
pluginId: ColorSlider
type: action
subtype: couleur
---

# Description

Roue chromatique proposant diverses options de disposition et d'affichage sur base de sliders.

![{{page.pluginId}} - gif]({{site.baseurl}}/{{page.pluginId}}/img/{{page.pluginId}}.gif "{{page.pluginId}} - gif")

# Installation et mises à jour

## Avec le plugin Pimp my Jeedom

![{{page.pluginId}} - Pimp my Jeedom]({{site.baseurl}}/{{page.pluginId}}/img/{{page.pluginId}}_pimpJeedom.png "{{page.pluginId}} - Pimp my Jeedom")

L'installation est aisée grâce au plugin [Pimp my Jeedom]({{site.market}}/index.php?v=d&plugin_id=4005){:target="\_blank"}, rendez vous sur la page du widget et cliquez sur le bouton **Installer**.

Pour appliquer le widget sur une ou plusieurs commandes, cliquez sur le bouton **Appliquer sur** et choisissez les commandes qui utiliseront le widget avant de cliquer sur **Valider**.

Le plugin vérifie automatiquement la disponibilité d'une mise à jour pour le widget et vous en informe directement dans Jeedom. En présence d'une mise à jour disponible, il suffit de se rendre sur la page du widget dans le plugin et cliquer sur le bouton **Mettre à jour**.

## Manuellement

Les fichiers peuvent être récupérés dans un dossier compressé via ce lien : [{{page.pluginId}}_Widget-Jeedom.zip](https://github.com/Salvialf/JEEDOM-Widget-{{page.pluginId}}/raw/master/{{page.pluginId}}_WidgetJeedom.zip).

Les répertoires `dashboard` et `mobile` <small>(si disponible)</small> doivent être copiés dans le répertoire `data/customTemplates/` à l'aide du plugin *JeeXplorer*.

Appliquer le widget sur une commande {{page.type}}/{{page.subtype}} à partir de l’onglet *Affichage* de la configuration de la commande, en choisissant **Customtemp/{{page.pluginId}}** dans le menu déroulant.

En cas de mise à jour du code du widget il est nécessaire de télécharger les nouveaux fichiers et de les copier dans le répertoire `data/customTemplates/` en remplacement des anciens fichiers.

# Les paramètres optionnels

## Liste des paramètres disponibles

* ### hue
Permet de choisir la forme de la roue chromatique : **wheel**, **slider**, **circle** ou **off** *(wheel par défaut)*

* ### value
Permet de choisir la forme du sélecteur de teinte : **slider**, **box**, **circle** ou **off** *(slider par défaut)*

* ### saturation
Permet de choisir la forme du sélecteur de saturation : **slider**, **circle** ou **off** *(off par défaut)*

* ### slider-size
Pour choisir l'épaisseur des sliders. *(20 par défaut)*

* ### disposition
Permet de choisir la disposition des éléments : **vertical** ou **horizontal** *(vertical par défaut)*

* ### wheel-angle
Permet de choisir l'orientation de la roue chromatique. *(0 par défaut)*

* ### size
Valeur en pixels permettant de modifier la taille du widget. *(140 par défaut)*

* ### margin
Valeur en pixels permettant de modifier l'espace entre les différents éléments'. *(10 par défaut)*

* ### handle-size
Valeur en pixels permettant de modifier la taille du rond sélecteur. *(9 par défaut)*

* ### handle-padding
Valeur en pixels permettant de modifier l'écartement du rond sélecteur par rapport aux bords de la roue chromatique. *(2 par défaut)*

* ### border-size
Valeur en pixels permettant de modifier la taille de la bordure des différents éléments. *(0 par défaut)*

* ### border-color
Permet de choisir la couleur de la bordure des différents éléments. *(white par défaut)*

## Avec le plugin Pimp my Jeedom

Le plugin [Pimp my Jeedom]({{site.market}}/index.php?v=d&plugin_id=4005){:target="\_blank"} rend l'usage et la configuration des paramètres optionnels très simple et rapide.

Rendez vous sur la page du widget dans le plugin. Sélectionnez la commande que vous souhaitez personnaliser en cochant la case présente juste avant le nom de la commande pour ouvrir le panneau de personnalisation :

![{{page.pluginId}} - Params_pimpJeedom]({{site.baseurl}}/{{page.pluginId}}/img/{{page.pluginId}}_Params_pimpJeedom.png "{{page.pluginId}} - Params_pimpJeedom")

## Manuellement

Pour appliquer de nouveaux paramètres optionnels, il faut se rendre dans la configuration de la commande puis onglet *Affichage* -> **Paramètres optionnels widget**.    
Cliquez sur **Ajouter** et renseigner le nom et la valeur de chaque paramètre :

![{{page.pluginId}} - Params_exemple]({{site.baseurl}}/{{page.pluginId}}/img/{{page.pluginId}}_Params_Example.png "{{page.pluginId}} - Params_exemple")

# Sources

Ce widget a été réalisé à partir de la librairie [iro.js](https://iro.js.org){:target="\_blank"}.

# Changelog

[Voir le changelog]({{site.baseurl}}/{{page.pluginId}}/{{page.lang}}/changelog)
