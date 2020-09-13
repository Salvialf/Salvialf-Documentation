---
layout: default
title: GaugeIMG
lang: fr_FR
pluginId: GaugeIMG
type: info
subtype: numérique
---

# Description

Embellissez vos commandes {{page.type}}/{{page.subtype}} grâce à ces magnifiques jauges colorées et animées.

![{{page.pluginId}} - gif]({{site.baseurl}}/{{page.pluginId}}/img/{{page.pluginId}}.gif "{{page.pluginId}} - gif")

Un large choix de couleurs permet de personnaliser facilement l'affichage de l'information en fonction des critères de votre choix.

> **9 couleurs disponibles pour la jauge ou pour la flèche**    
1 *"neutre"* + 8 vivement colorées :

![{{page.pluginId}} - Colors]({{site.baseurl}}/{{page.pluginId}}/img/{{page.pluginId}}_colors.png "{{page.pluginId}} - Colors")

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

* ### mini
Permet de définir une borne minimale indépendante des contraintes imposées par Jeedom. *(valeur mini de la commande par défaut)*

* ### maxi
Permet de définir une borne maximale indépendante des contraintes imposées par Jeedom. *(valeur maxi de la commande par défaut)*

* ### gauge
Permet de choisir la couleur de la jauge parmis les 9 disponibles : **blue, green, yellow, orange, red, pink, purple, turquoise, neutral**. *(blue par défaut)*

* ### arrow
Permet de choisir la couleur de la flèche parmis les 9 disponibles : **blue, green, yellow, orange, red, pink, purple, turquoise, neutral**. *(blue par défaut)*

* ### change
Permet de changer la couleur de la jauge en fonction de la valeur de la commande. *(non renseigné par défaut)*

> **Utilisation**    
Saisir la plage de valeurs séparées par un tiret-bas **(_)**, puis deux-points **(:)** suivis de la couleur désirée *(en anglais)*. Plusieurs plages peuvent être définies en les séparant par une virgule **(,)**.    

> **Exemple**     
change = `0_25:green,25_75:orange,75_90:red`

* ### size
Permet de choisir la taille de la jauge parmis les 3 disponibles **small**, **medium** et **big**. *(medium par défaut)*

![{{page.pluginId}} - Sizes]({{site.baseurl}}/{{page.pluginId}}/img/{{page.pluginId}}_sizes.png "{{page.pluginId}} - Sizes")

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

[Accéder au sujet sur le forum](https://community.jeedom.com/t/salvialf-widget-gaugeimg-info-numerique/24189){:target="\_blank"}

# Changelog

[Voir le changelog]({{site.baseurl}}/{{page.pluginId}}/{{page.lang}}/changelog)
