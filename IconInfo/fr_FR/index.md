---
layout: default
title: IconInfo
lang: fr_FR
pluginId: IconInfo
type: info
subtype: binaire
---

# Description

Visualisez l'état de vos équipements d'un coup d'oeil grâce à ce widget permettant d'afficher une image différente selon l'état 0 ou 1 d'une commande {{page.type}}/{{page.subtype}}.

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

* ### height
Valeur en pixels permettant de modifier la hauteur de l'image. *(75 par défaut)*

* ### width
Valeur en pixels permettant de modifier la largeur de l'image. *(75 par défaut)*

* ### image
Pour sélectionner l'image à afficher sur le widget. *(default par défaut)*

> **187 visuels sont disponibles**    
*airpur, ambilight, ambilight2, ampli, amplihc, aquarium, arrosage, aspirateur, aspixiaomi, bal, barreson, bbox, bbox2, bboxtv, bluray, box, broadlinkair, broadlinkmini, broadlinkprise, broadlinkpro, cafetiere, cam1, cam2, cam3, cam4, camext, cave, cave2, chainehifi, chauffage, chromecast, congelateur, ds918, dvd, echob, echodot, echog, echospotb, echospotw, echow, ecranproj, free, freeadsl, freebox, freeboxtv, freedelta, freewifi, frigo, frigo2, gateway, ghome, gminig, gminin, gminio, gps, hotte, hp, huev1, huev2, impr, imprimante, imprimante2, imprlaser, ipad, iphone4, jeedom, jeedomm, jeedoms1, jeedoms2, jeedoms3, jeedomsmart, jpi, kodi, kodi2, lavelinge, lavevaisselle, lgg3, linux, livebox, livebox2, livebox4, lvaisselle, mac, machinealaver, machinelaver, moustiques, nas, note8, nswitch, nuc, onetouch, orange, orvibo, paw, pc, pc2, pharmacie, playstation, playstation2, plex, pms, poele, pompe, portapple, portwin, poulailler, prise, raspbmc, raspi, refrigerateur, repwifi, repwifi2, routeur, routeur2, routeur3, sapin, sarah, sechelinge, secheserviette, sfr, sfrbox, slinge, sonosbeamB, sonosbeamW, sonosoneB, sonosoneW, sonosplayB, sonosplayW,  subwoofer, switch, synow, synob, synort1900, synort2600, tab4, tv, tv2, videoproj, vmc, wii, wiiu, xbmc, xbmc2, xbox, xbox2, xpenology, zibase*.

> **A savoir**    
Il est possible d'inclure les images de son choix en plaçant le(s) fichier(s) `*.png` dans le répertoire **/data/img/{{page.pluginId}}/**.    
Les images doivent être nommées "**type**\_*on.png*" & "**type**\_*off.png*".

* ### time
Pour visualiser les informations de temps depuis le dernier changement d'état. 3 formats sont possibles : **duration** affiche la durée, **date** affiche le jour et l'heure, **hour** affiche l'heure avec les secondes du dernier changement d'état. *(off par défaut)*

* ### CSS-time
Permet de personnaliser la présentation du paramètre **time** en code CSS.

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

[Accéder au sujet sur le forum](https://community.jeedom.com/t/salvialf-widget-iconinfo-info-binaire/7970){:target="\_blank"}

# Changelog

[Voir le changelog]({{site.baseurl}}/{{page.pluginId}}/{{page.lang}}/changelog)
