---
layout: default
title: Changelog Pimp my Jeedom
lang: fr_FR
pluginId: pimpJeedom
---

# Changelog

## 10-07-2020

- En prévention de la suppression automatique des fichiers inutiles par le core, lors d'une mise à jour du plugin les widgets installés sont automatiquement sauvegardés avant la mise à jour et restaurés après.

## 09-07-2020

- Ajout du widget **IconInfo** pour commandes info/binaire.
- Ajout du widget **IconAction** pour commandes action/défaut.
- Remplacement eqLogic par Config -> nécessite la mise à jour de tous les widgets déjà installés. (merci @naboleo)
- Passage de la dernière BETA en STABLE.

## 16-06-2020 (BETA)

- Ajout du widget **ColorSlider** pour commandes action/couleur.
- Réécriture complète du widget **ColorCircle** qui n'utilise plus d'images.
- Nouveau message en cas de succès d'une mise à jour de widget.

## 15-06-2020

- Correction du non-affichage des widgets tiers contenant un tiret-bas dans leur nom.

## 12-06-2020

- Passage BETA en STABLE. (Il peut être nécessaire de réappliquer certains paramètres sur quelques widgets)

## 10-06-2020 (BETA)

- Sur les widgets qui le propose le plugin ira chercher directement les images `*.png` dans le répertoire `/data/img/Nom_du_Widget/` pour les ajouter aux images disponibles par défaut.
- Ajout d'un bouton permettant d'envoyer ses propres images ou fichiers de polices d'écriture directement dans le bon répertoire selon les options du widget.
- Correction de la prévisualisation des widgets tiers.

## 08-06-2020 (BETA)

- Redimensionnement automatique des tuiles de prévisualisation si plus larges que l'espace disponible et ajout de la possibilité de réduire la tuile en largeur.
- Ajout d'un bouton qui renvoie vers la documentation dédiée (icône livre) de chaque widget by Salvialf. Le contenu est encore en cours de rédaction.
- Ajout du widget **PresenceData** pour commandes info/binaire.

## 06-06-2020 (BETA)

- Prise en charge de la langue anglaise.
- Mise en place de 2 versions des widgets ("*beta*" ou "*stable*") correspondants aux 2 versions du plugin.
- Réorganisation des paramètres optionnels et passage définitif en langue anglaise pour l'internationalisation. Ceci peut avoir pour effet de réinitialiser certains paramètres déjà renseignés.
- Sur les widgets qui le propose le plugin ira chercher directement les fichiers de polices d'écriture `*.ttf` du répertoire `/data/fonts/` pour les appliquer sur le widget.

## 03-06-2020

- Widgets Tiers : Optimisations générales + ajout de logs (BETA).
- Correction du décalage sur la page d'un widget (BETA).
- Affichage de l'équipement complet en prévisualisation (STABLE).

## 02-06-2020

- Correction de messages générés dans le log http.error (STABLE).
- Optimisation des pages détaillées des widgets tiers (BETA).

## 01-06-2020

- Passage du plugin en STABLE.

## 28-05-2020

- Mise à disposition du plugin en BETA.

# Documentation

[Voir la documentation]({{site.baseurl}}/{{page.pluginId}}/{{page.lang}})
