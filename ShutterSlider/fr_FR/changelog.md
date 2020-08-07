---
layout: default
title: ShutterSlider changelog
lang: fr_FR
pluginId: ShutterSlider
---

# Changelog

## 07-08-2020

- Correction de la position du volet ouvert pour les modules définisant l'ouverture maximale à 99% + paramètre *offset* renseigné.      
**Pour les modules dont la valeur d'ouverture maximum est de 99% il sera dorénavant nécessaire de renseigner la valeur Max de la commande de positionnement à** `99`.
![{{page.pluginId}} - Max Commande]({{site.baseurl}}/{{page.pluginId}}/img/{{page.pluginId}}_MaxCmd.png "{{page.pluginId}} - Max Commande")

## 10-06-2020

- Uniformisation des paramètres optionnels en langue anglaise.
- Ajout du paramètre **time** qui permet d'afficher les informations du dernier changement d'état (durée, date ou heure).
- Ajout du paramètre **CSS-time** qui permet de personnaliser l'affichage du dernier changement d'état.
- Possibilité de charger sa propre image de fond à partir du répertoire `/data/img/{{page.pluginId}}/`

## 31-03-2020

- Partage du widget sur Community.

# Documentation

[Voir la documentation]({{site.baseurl}}/{{page.pluginId}}/{{page.lang}})
