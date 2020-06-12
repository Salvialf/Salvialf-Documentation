---
layout: default
title: PresenceData
lang: fr_FR
pluginId: PresenceData
type: info
subtype: binaire
---

# Description

Affichez les informations de présence des membres du foyer accompagnées de l'image de votre choix à partir d'une simple commande {{page.type}}/{{page.subtype}}.

![{{page.pluginId}} - gif]({{site.baseurl}}/{{page.pluginId}}/img/{{page.pluginId}}.gif "{{page.pluginId}} - gif")

# Installation et mises à jour

## Avec le plugin Pimp my Jeedom

L'installation est aisée grâce au plugin [Pimp my Jeedom]({{site.market}}/index.php?v=d&plugin_id=4005){:target="\_blank"}, rendez vous sur la page du widget et cliquer sur le bouton **Installer**.

Pour appliquer le widget sur une ou plusieurs commandes, cliquer sur le bouton **Appliquer sur** et choisissez les commandes qui utiliseront le widget avant de cliquer sur **Valider**.

Le plugin vérifie automatiquement la disponibilité d'une mise à jour pour le widget et vous en informe directement dans Jeedom. En présence d'une mise à jour disponible, il suffit de se rendre sur la page du widget dans le plugin et cliquer sur le bouton **Mettre à jour**.

![{{page.pluginId}} - Pimp my Jeedom]({{site.baseurl}}/{{page.pluginId}}/img/{{page.pluginId}}_pimpJeedom.png "{{page.pluginId}} - Pimp my Jeedom")

## Manuellement

Les fichiers peuvent être récupérés dans un dossier compressé via ce lien : [{{page.pluginId}}_Widget-Jeedom.zip](https://github.com/Salvialf/JEEDOM-Widget-{{page.pluginId}}/raw/master/{{page.pluginId}}_WidgetJeedom.zip).

Les répertoires `dashboard` et `mobile` <small>(si disponible)</small> doivent être copiés dans le répertoire `data/customTemplates/` à l'aide du plugin *JeeXplorer*.

Appliquer le widget sur une commande {{page.type}}/{{page.subtype}} à partir de l’onglet *Affichage* de la configuration de la commande, en choisissant **Customtemp/{{page.pluginId}}** dans le menu déroulant.

En cas de mise à jour du code du widget il est nécessaire de télécharger les nouveaux fichiers et de les copier dans le répertoire `data/customTemplates/` en remplacement des anciens fichiers.

# Les paramètres optionnels

## Liste des paramètres disponibles

* ### height
Valeur en pixels permettant de modifier la hauteur de l'image. *(90 par défaut)*

* ### width
Valeur en pixels permettant de modifier la largeur de l'image. *(90 par défaut)*

* ### image
Pour choisir la taille de la date en pixels. **default** ou **woman** *(default par défaut)*
> **A savoir**    
Il est possible d'inclure les images de son choix en plaçant le(s) fichier(s) `*.png` dans le répertoire **/data/img/{{page.pluginId}}/**.    
Les images doivent être nommées "**Nom**\_*on.png*" & "**Nom**\_*off.png*".

* ### vertical
Pour passer le widget en affichage vertical. **checked** ou **unchecked** *(unchecked par défaut)*

* ### duration
Pour afficher la durée de présence ou d'absence. **checked** ou **unchecked** *(checked par défaut)*

## Avec le plugin Pimp my Jeedom

Le plugin [Pimp my Jeedom]({{site.market}}/index.php?v=d&plugin_id=4005){:target="\_blank"} rend l'usage et la configuration des paramètres optionnels très simple et rapide.

Rendez vous sur la page du widget dans le plugin. Sélectionnez la commande que vous souhaitez personnaliser en cochant la case présente juste avant le nom de la commande pour ouvrir le panneau de personnalisation :

![{{page.pluginId}} - Params_pimpJeedom]({{site.baseurl}}/{{page.pluginId}}/img/{{page.pluginId}}_Params_pimpJeedom.png "{{page.pluginId}} - Params_pimpJeedom")

> **Info**    
Le bouton **Envoyer une image** présent sur la page du widget permet d'ajouter des images directement dans le répertoire **/data/img/{{page.pluginId}}/** et de les retrouver dans la liste des choix possibles.

## Manuellement

Pour appliquer de nouveaux paramètres optionnels, il faut se rendre dans la configuration de la commande puis onglet *Affichage* -> **Paramètres optionnels widget**.    
Cliquez sur **Ajouter** et renseigner le nom et la valeur de chaque paramètre :

![{{page.pluginId}} - Params_exemple]({{site.baseurl}}/{{page.pluginId}}/img/{{page.pluginId}}_Params_Example.png "{{page.pluginId}} - Params_exemple")

# Sur le forum

[Accéder au sujet sur le forum](https://community.jeedom.com/t/salvialf-widget-presencedata-info-binaire/6161){:target="\_blank"}

# Changelog

[Voir le changelog]({{site.baseurl}}/{{page.pluginId}}/{{page.lang}}/changelog)
