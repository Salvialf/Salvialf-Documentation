---
layout: default
title: ConsigneThermostat
lang: fr_FR
pluginId: ConsigneThermostat
type: action
subtype: curseur
---

# Description

Widget au visuel simple et efficace, permettant de gérer la température de consigne d'un thermostat grâce aux boutons "+" et "--".

![{{page.pluginId}} - gif]({{site.baseurl}}/{{page.pluginId}}/img/{{page.pluginId}}.gif "{{page.pluginId}} - gif")

L'icône en forme de thermomètre change de couleur et se remplit ou se vide en fonction de la température choisie.

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

[Accéder au sujet sur le forum](https://community.jeedom.com/t/salvialf-widget-consigne-thermostat-action-curseur/22070){:target="\_blank"}

# Changelog

[Voir le changelog]({{site.baseurl}}/{{page.pluginId}}/{{page.lang}}/changelog)
