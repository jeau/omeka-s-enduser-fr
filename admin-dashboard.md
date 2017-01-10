---
title: Tableau de bord d'administration
---

Le tableau de bord d'administration permet de gérer les contenus partagés par tous les sites créés sur l'installation Omeka S et d'accéder aux fonctionnalités principales de cette installation.

## Page principale d'administration

Lorsqu'un usager se connecte, la première page à laquelle il accède est le tableau de bord d'administration.

![Admin dashboard full view](/files/admindashfullview.png)

En plus de la zone de navigation à gauche présente sur toutes les pages (voir ci-dessous), le tableau de bord d'administration présente deux zones : la gestion des ressources et et la gestion des sites.

La zone de gestion des ressources (*Manage Resources*) affiche les  liens vers les ressources suivantes, leur nombre est indiqué entre parenthèses : [Items](/content/items.md), [Lots d'items (Sets)](/content/item-sets.md), [Ontologie (Vocabularies)](/content/vocabularies.md), et les [Modèles de ressources (Resource Templates)](/content/resource-template.md).
En cliquant sur l'étiquette de la ressource, vous accédez à la page de navigation de cette ressource. En cliquant sur le bouton *Plus* à droite de l'étiquette, vous accédez à la page d'ajout de ce type de ressource.

![Close up of manage resources and manage sites boxes](/files/admindashmanage.png)

La zone *Administration des sites (Manage Sites)* liste les [Sites](/sites/sites.md) hébergés par l'installation. Cliquez sur le nom d'un site vous permettra d'accéder à la partie publique de ce site et sur le bouton d'édition (le crayon) d'accéder à la page d'information et d'édition de ce site.


## Navigation située à gauche

Le contenu suivant apparaît sur le côté gauche du tableau de bord ainsi que sur toutes les pages de l'interface d'administration de l'installation.

![View of the left hand navigation on the admin dashboard, which also appears consistently throughout the admin interface, with options as described below](/files/leftnav.png)

Dans le coin en haut à gauche est indiqué l'intitulé de l'installation. C'est un lien cliquable qui vous renverra toujours au tableau de bord d'administration.

Juste en dessous de ce titre se trouve le message "Signed in as *User*" où *User* est l'affichage du nom de l'usager qui est connecté. À proximité (à droite ou en dessous en fonction de la largeur de la fenêtre d'affichage) du nom de l'usager se trouve un bouton  *Logout*.

En dessous du nom de l'usager connecté, se trouve un champ de recherche auquel est associé une option de recherche avancée (points de suspension) en plus du bouton de recherche (loupe). Utilisez ce champ pour effectuer une recherche sur toutes les ressources de l'installation.

Les options de recherche avancée (points de suspension) permettent d'affiner la recherche par type de ressource ; en cliquant sur le bouton radio en regard d'un type de ressource, *items*, *item sets* (lots d'items) ou *médias* il est possible de restreindre la recherche à ce type de ressource.

![Advanced search options](/files/search.png)

La partie centrale de la colonne de gauche du tableau de bord est divisée en deux sections relatives aux sites, aux ressources et aux fonctions d'administration :

- [Sites](/sites/sites.md): Liste des sites de l'installation Omeka S et accès à leur administration. (icône ordinateur)
- Ressources : création et gestion des contenus et des métadonnées :
    - [Items](/content/items.md) : gestion de chacune des ressources. (icône boîte)
    - [Item Sets](/content/item-sets.md): gestion des groupes de ressources (items). (icône plusieurs boîtes)
    - [Vocabularies](/content/vocabularies.md): gestion des ontologies des métadonnées. (icône livre)
    - [Resource Templates](/content/resource-template.md): gestion des modèles de formulaires prédéfinis de propriétés à utiliser pour créer des ressources (items). (crayon dans une icône carrée)
- Admin: interface d'administration (à noter que certaines options ne sont pas accessibles à tous les rôles attribués aux usagers)
    - [Users](/users.md): gestion des usagers pour l'ensemble de l'installation et chacun des sites. (icône buste)
    - [Modules](/modules/modules.md): ajout de fonctionnalités nouvelles à l'installation. (signe + dans une icône carrée)
    - [Travaux (Jobs)](https://github.com/omeka/omeka-s-enduser/blob/master/jobs.md): affiche les travaux en cours lancés par l'usager. NB: les travaux n'apparaissent que si ils sont actifs. (icône aux trois barres)
    - [Paramètres (Settings)](https://github.com/omeka/omeka-s-enduser/blob/master/settings.md): gère les paramètres globaux de tous les sites, des tableaux de bord d'administration et de tous les sites. (icône engrenage)

Si vous avez installé des modules, ils peuvent apparaître à gauche sous les paramètres dans la section *Admin* de la navigation.

Notez que les utilisateurs disposant d'autorisations plus limitées ne verront que certaines de ces options de navigation.

## Information sur le système

Dans le coin en bas à droite se trouve un affichage succinct de la version courante de Omeka S. Cliquer sur le lien *System Information* permet d'accéder à une page avec tous les détails.

![Example system information page](/files/systeminfo.png)
