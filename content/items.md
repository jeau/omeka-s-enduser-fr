# Items

Les i` tems sont les briques de base d'un service Omeka.

Avec Omeka S, les items sont gérés et rendus disponibles à partir de l'interface d'administration, d'où vous pouvez aussi ajouter ces items dans vos propres sites.

La liste des items est accessible à partir du lien *Items* (icône avec un seule cube), situé dans la zone latérale gauche de l'interface d'administration.

![Vue partielle de la page d'administration des items montrant quelques ressources](../content/contentfiles/items_browse.png)

Chaque item apparait sur une ligne avec : le titre (*Title*) ; les icônes d'*édition* (crayon), *suppression* (poubelle) et *afficher les infos* (points de suspensions) ; la classe (*Class*) ; le propriétaire de l'item (*Owner*) ; et la date de création (*Date Created*).

Les options de navigation et de création d'éléments sont affichées au-dessus de la table des items. Sur la partie gauche, s'affiche le nombre de pages d'items, et des flèches pour parcourir ces pages. Le champ contenant numéro de la page courante est éditable ; entrez un numéro de page valide et appuyez sur la touche *Entrée* ou *Retour* sur votre clavier pour accéder à cette page.

Au centre de cette partie haute de la table se trouve un bouton vers la [recherche avancée](../search.md).

On the right top of the Items window, above the table of items, is the *Add new item* button. Just above the table on the right are options for sorting the table of items, with two dropdown menus. The first lets you select between *Title*, *Class*, *Owner,* and *Date Created*; the second allows you to sort ascending or descending. To apply, click the *sort* button.

## View

To quickly view the basic information about an item, click the *view details* (ellipses) button in the row for the item, located next to the edit and delete buttons. This will open a drawer to the right of the list which displays the item’s title,  description, and visibility.

For a more detailed look at an individual item, click on its title in the items browse table or when viewing its details  
When you view an individual item , there are tabs for the item’s *Metadata* and its *Linked Resources*. The right side of the page displays the item’s media, any *item sets* to which it belongs, its creation date, owner, and visibility.

![Item browse view with details open for Case of Identity. Links to item view page squared in blue](../content/contentfiles/items_detailview.png) The blue squares indicate where to click to open the full item view.

An item’s *linked resources* (shown below) are resources, which have been added as properties to the item. The table on this tab gives the predicate (property) and a link to each object (item).

![Item view for Case of Identity, showing linked resources](../content/contentfiles/items_linked.png)

## Adding an Item

To add a new item, begin by selecting the the *Add new item* button.

Before creating items, site admins may want to create [Resource Templates](/content/resource-template.md), which will load specific fields for various item types.

### Values
The Values tab is where you enter metadata, such as title, description, etc.

![Basic view of add items page, with no content entered](../content/contentfiles/items_add1.png)

1. If available and appropriate, select a resource template from the drop-down menu. Resource templates are defined by the site administrators and editors.
  * If using a resource template, the class should automatically load.
  * If not using a resource template, select a class from the dropdown menu (these are populated from the [Vocabularies](/content/vocabularies.md) in your installation).
1. Add information to the fields provided.  
  1. You may add text, a resource from the installation, or an external link in each field.  
    * **Text** fields are entered with text, which can include HTML code. The keyboard at the top of the field input indicates text. The globe icon which appears next to it can be used to set language.
![image of text input field with keyboard icon indicating text input, the globe icon for setting language, and a trashcan delete icon](../content/contentfiles/items_textedit.png)
    * **Omeka Resource** fields create an internal link between the resource you are creating and the resource which fills that field. You have the option to use either another item or an item set. Once you select an item or item set, detailed information will load, and you must click *select resource* to finish linking the resources. You can also click the *X* button in the upper right-hand corner to go back to the list of items or item sets.
     ![Select Item menu with list of items to link in edit item view](../content/contentfiles/items_addresource.png)
    * **URI** fields link to an external website or online resource.
1. You may add other fields by selecting a property from the list on the right. Browse fields by vocabulary (Dublin Core, Bibliographic Ontology, etc), or search in the *filter properties* bar above the list of properties and vocabularies.

### Media
Use the *Media* tab to add images, video, or other files.
Using the buttons on the *Add New Media* menu on the right side of the screen, select a media type (Upload, URL, oEmbed, YouTube, or HTML)

![“Add new media” dropdown showing the options](../content/contentfiles/items_mediaadd.png)

- *Upload*: select a file to upload from your computer.
- *URL*: import media via a uri.
- *oEmbed*: insert an embedded representation of an external URL. Note that this will only work with content from [existing oEmbed implementations](http://oembed.com/#section7) - use the url in your browser’s location bar.
- *YouTube*: add a link to embed a YouTube video. Use the url from your browser’s location bar (with `/watch/` in it) rather than the `youtu.be` link.
- *HTML*: add html content as a media resource for your item.
- *IIIF*: Add an IIIF image via url.

While editing, you can delete any media instance using the delete button (trashcan) on the upper right corner of the media block.

![Blank media instance blocks all six media types](../content/contentfiles/items_mediablocks.png)

If you have more than one media instance for an item, you can reorder them by dragging and drop each media instance block, using the icon of three lines in the upper left corner of the block as the anchor when dragging (click there).

You can edit media later by going by editing an item, navigating to the *media* tab, and clicking the edit button (pencil) for a media when editing the item. You can use the delete button to remove media from an item.

![Media tab of an item being edited, with the view, edit, and delete buttons to the right of the media file name](../content/contentfiles/items_mediaedit.png)

### Item Sets
You can only add items to existing item sets.

From the right-hand menu, click on the owner of an item set, then click the name of the item set to add the item to that set.

You can also filter item sets using the text entry bar above the list of users.

To remove a connection between an item and item set, click the delete (trash can) button to the right of the item set title.

![item set tab with one item set added](../content/contentfiles/items_itemset.png)


### Visibility
Use the *make public/private* button (eye icon) to set whether the item is visible to the public or only to users of the Omeka S system.

![make public button showing an eye icon](../content/contentfiles/item_public.png) Public

![make private button showing an eye icon with a diagonal slash through it](../content/contentfiles/item_private.png)  Private

Note that if an item is private, all the media attached is private, but an item which is public can have attached media which are set to be either public or private.
