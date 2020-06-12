---
layout: default
title: Linky
lang: fr_FR
pluginId: Linky
type: info
subtype: numérique
---

# Description

Affichez les informations de consommation électrique de votre logement sur un widget très réaliste à l'effigie du compteur *Linky*.

![{{page.pluginId}} - gif]({{site.baseurl}}/{{page.pluginId}}/img/{{page.pluginId}}.gif "{{page.pluginId}} - gif")

Le widget doit être appliqué sur 4 commandes {{page.type}}/{{page.subtype}} qui doivent impérativement être nommées :    
* **Conso Annuelle**    
* **conso Mensuelle**    
* **Conso Jour**    
* **Conso Horaire**    

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

# Sur le forum

[Accéder au sujet sur le forum](https://community.jeedom.com/t/salvialf-widget-linky-v4-info-numerique/5253){:target="\_blank"}

# Changelog

[Voir le changelog]({{site.baseurl}}/{{page.pluginId}}/{{page.lang}}/changelog)
