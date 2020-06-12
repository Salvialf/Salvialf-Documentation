---
layout: default
title: DigitalClock
lang: fr_FR
pluginId: DigitalClock
type: info
subtype: autre
---

# Description

Ajoutez une horloge totalement paramétrable sur votre dashboard ou votre design Jeedom. 38 polices d'écriture sont incluses et il est possible d'ajouter les polices de votre choix.

![{{page.pluginId}} - gif]({{site.baseurl}}/{{page.pluginId}}/img/{{page.pluginId}}.gif "{{page.pluginId}} - gif")

> **Important**    
Ce widget est à appliquer sur une commande {{page.type}}/{{page.subtype}} issue du plugin *Virtuel*.

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

* ### date-font
Permet de sélectionner la police d'écriture de la date.  *(default par défaut)*

* ### time-font
Permet de sélectionner la police d'écriture de l'heure. *(default par défaut)*

> **38 polices sont incluses et directement sélectionnables dans le widget** :  
*alarm, arcade1, arcade2, arcade3, astronomic, atomic, clubland, digit, digital7, digital7dot, digital7led, digitaldust, dismay, frida1, frida2, frida3, grapam, habesha1, habesha2, habesha3, identification, label, lcd14, lcdmu, lcdpixel, ledboard, ledboard2, monochrome, prisma, segment, shmup, squarecurved, squareforced, squarehead, starfish, taurus, tesla, verily*.

> **A savoir**    
>Les polices d'écriture présentes dans le répertoire `/data/fonts/` et ayant une extension de fichier `ttf` sont automatiquement ajoutées dans la liste des paramètres **date-font** et **time-font**.

* ### date-size
Pour choisir la taille de la date en pixels. *(20 par défaut)*

* ### time-size
Pour choisir la taille de l'heure en pixels. *(40 par défaut)*

> **Astuce**   
Renseigner une taille à 0 fera disparaitre l'affichage de la date ou de l'heure.

* ### color
Permet de modifier la couleur de l'horloge. *(gris par défaut)*

* ### disposition
Permet de modifier la disposition du widget abrégé sur 2 lignes ou complet sur 3 lignes. **simple** ou **full** *(simple par défaut)*

* ### seconds
Pour afficher ou non les secondes sur le widget. **checked** ou **unchecked** *(checked par défaut)*

* ### halo
Pour afficher ou non un halo lumineux sur l'horloge. **checked** ou **unchecked** *(unchecked par défaut)*

## Avec le plugin Pimp my Jeedom

Le plugin [Pimp my Jeedom]({{site.market}}/index.php?v=d&plugin_id=4005){:target="\_blank"} rend l'usage et la configuration des paramètres optionnels très simple et rapide.

Rendez vous sur la page du widget dans le plugin. Sélectionnez la commande que vous souhaitez personnaliser en cochant la case présente juste avant le nom de la commande pour ouvrir le panneau de personnalisation :

![{{page.pluginId}} - Params_pimpJeedom]({{site.baseurl}}/{{page.pluginId}}/img/{{page.pluginId}}_Params_pimpJeedom.png "{{page.pluginId}} - Params_pimpJeedom")

> **Info**    
Le bouton **Envoyer une police** présent sur la page du widget permet d'ajouter des polices d'écriture directement dans le répertoire **/data/fonts/** et de les retrouver dans la liste des choix possibles.

## Manuellement

Pour appliquer de nouveaux paramètres optionnels, il faut se rendre dans la configuration de la commande puis onglet *Affichage* -> **Paramètres optionnels widget**.    
Cliquez sur **Ajouter** et renseigner le nom et la valeur de chaque paramètre :

![{{page.pluginId}} - Params_exemple]({{site.baseurl}}/{{page.pluginId}}/img/{{page.pluginId}}_Params_Example.png "{{page.pluginId}} - Params_exemple")

# Sur le forum

[Accéder au sujet sur le forum](https://community.jeedom.com/t/salvialf-widget-digitalclock-info-autre/24877){:target="\_blank"}

# Changelog

[Voir le changelog]({{site.baseurl}}/{{page.pluginId}}/{{page.lang}}/changelog)
