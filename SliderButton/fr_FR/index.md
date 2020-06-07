---
layout: default
title: SliderButton
lang: fr_FR
pluginId: SliderButton
---

# Description

Ce widget pour commandes action/curseur est inspiré du widget core *"Button"*. Il allie design moderne et élégant, fonctionnalités et possibilités de personnalisation avancées.

![Sliderbutton - gif](https://github.com/Salvialf/JEEDOM-Widget-SliderButton/blob/master/doc/SliderButton.gif?raw=true "SliderButton - gif")

> **Astuce**    
En plus des boutons « **-** » et « **+** », il est possible de saisir la valeur en cliquant directement dessus.    
Il faut alors soit cliquer en dehors du widget pour valider ou appuyer sur la touche Entrée.

Entièrement personnalisable grâce à ses nombreux paramètres optionnels *(voir chapitre "Les paramètres optionnels")*, ce widget propose 2 thèmes *(dark/light)* ainsi que 8 couleurs de boutons différentes *(turquoise, green, yellow, orange, red, pink, purple, neutral)* :

![Sliderbutton - color](https://github.com/Salvialf/JEEDOM-Widget-SliderButton/blob/master/doc/SliderButton_Colors.png?raw=true "SliderButton - colors")

# Installation et mises à jour

## Avec le plugin Pimp my Jeedom

L'installation est aisée grâce au plugin <a href="{{site.market}}/index.php?v=d&plugin_id=4005" target="\_blank">Pimp my Jeedom</a>, rendez vous sur la page du widget et cliquer sur le bouton **Installer**.

Pour appliquer le widget sur une ou plusieurs commandes, cliquer sur le bouton **Appliquer sur** et choisissez les commandes qui utiliseront le widget avant de cliquer sur **Valider**.

Le plugin vérifie automatiquement la disponibilité d'une mise à jour pour le widget et vous en informe directement dans Jeedom. En présence d'une mise à jour disponible, il suffit de se rendre sur la page du widget dans le plugin et cliquer sur le bouton **Mettre à jour**.

## Manuellement

Les fichiers peuvent être récupérés dans un dossier compressé via ce lien : [SliderButton_Widget-Jeedom.zip](https://github.com/Salvialf/JEEDOM-Widget-SliderButton/raw/master/SliderButton_WidgetJeedom.zip).

Les répertoires `dashboard` et/ou `mobile` doivent être copiés dans le répertoire `data/customTemplates/` à l'aide du plugin *JeeXplorer*.

Appliquer le widget sur une commande action/curseur à partir de l’onglet *Affichage* de la configuration de la commande, en choisissant **Customtemp/SliderButton** dans le menu déroulant.

En cas de mise à jour du code du widget il est nécessaire de télécharger les nouveaux fichiers et de les copier dans le répertoire `data/customTemplates/` en remplacement des anciens fichiers.

# Les paramètres optionnels

## Liste des paramètres disponibles

### theme
Permet de choisir le thème du widget entre **dark** et **light**. *(light par défaut)*

### step
Permet de modifier le "pas" du widget. *(0.5 par défaut)*

### minus
Permet de choisir la couleur du bouton "moins"(-) parmis les 8 disponibles : **turquoise, green, yellow, orange, red, pink, purple, neutral**. *(turquoise par défaut)*

### plus
Permet de choisir la couleur du bouton "plus"(+) parmis les 8 disponibles : **turquoise, green, yellow, orange, red, pink, purple, neutral**. *(red par défaut)*

### height
Valeur en pixels permettant de modifier la hauteur du widget. *(40 par défaut)*

### width
Valeur en pixels permettant de modifier la largeur du widget. *(50 par défaut)*

### font
Permet de changer la police d'écriture de la valeur centrale. Les fichiers `*.ttf` doivent se trouver dans le répertoire Jeedom `/data/fonts/`. Seul le nom du fichier est à renseigner sans l'extension `.ttf`. *("nasalization" par défaut)*

### font-size
Pour choisir la taille de la police d'écriture en pixels. *(12 par défaut)*

### font-color
Permet de choisir la couleur de la police d'écriture. *(black par défaut)*

### time
Pour visualiser les informations de temps depuis le dernier changement d'état. 3 formats sont possibles : **duration** affiche la durée, **date** affiche le jour et l'heure, **hour** affiche l'heure avec les secondes du dernier changement d'état. *(off par défaut)*

### CSS-time
Permet de personnaliser la présentation du paramètre **time** en code CSS.

## Avec le plugin Pimp my Jeedom

Le plugin <a href="{{site.market}}/index.php?v=d&plugin_id=4005" target="\_blank">Pimp my Jeedom</a> rend l'usage et la configuration des paramètres optionnels très simple et rapide.

Rendez vous sur la page du widget dans le plugin. Sélectionnez la commande que vous souhaitez personnaliser en cochant la case présente juste avant le nom de la commande pour ouvrir le panneau de personnalisation :

![Sliderbutton - Params_pimpJeedom](https://github.com/Salvialf/JEEDOM-Widget-SliderButton/blob/master/doc/Params_pimpJeedom.png?raw=true "SliderButton - Params_pimpJeedom")

> **Bon à savoir**
> - Les polices d'écriture présentes dans le répertoire `/data/fonts/` et ayant une extension de fichier `ttf` sont automatiquement ajoutées dans la liste du paramètre **font**.
> - Concernant le paramètre **CSS-time**, un effet d'ombrage est renseigné par défaut.

## Manuellement

Pour appliquer de nouveaux paramètres optionnels, il faut se rendre dans la configuration de la commande puis onglet *Affichage* -> **Paramètres optionnels widget**.    
Cliquez sur **Ajouter** et renseigner le nom et la valeur de chaque paramètre :

![Sliderbutton - Params_exemple](https://github.com/Salvialf/JEEDOM-Widget-SliderButton/blob/master/doc/Params_example.png?raw=true "SliderButton - Params_exemple")

# Remerciements

Un grand merci à @Dankoss pour la réalisation des images du widget.

# Changelog

[Voir le changelog]({{site.baseurl}}/{{page.pluginId}}/{{page.lang}}/changelog)
