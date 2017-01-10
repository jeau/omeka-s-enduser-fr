---
title: Glossaire des termes utilisés dans Omeka S
---

Le glossaire suivant devrait vous aider à préciser le sens des termes utilisés avec Omeka S et qui vous sont les moins familiers. Le cas échéant, nous précisons le terme à peu près équivalent de Omeka Classic, bien que certaines analogies soient plus limitées que d'autres.

**Class**: Une sorte de ressource, définie par une ontologie (Vocabulary). Couramment, les ontologies impliquent que des propriétés particulières soient utilisées avec des classes particulières. Par exemple, un `foaf: Person` n'aura pas de propriété ` dcterms: publisher`, mais on pourra s'attendre à ce qu'il ait une propriété `foaf: familyName`.
*Analogie Omeka Classic*: Type de contenu (Item Type)

**File**: Document versé sur une installation Omeka S et associé directement à un enregistrement (Item) (voir aussi: Media).    
*Analogie Omeka Classic*: Fichier (File) (mais cette analogie est faible)

**Global Admin**: Un administrateur qui possède le contrôle sur l'ensemble de l'installation. Typiquement, ce peut-être la personne qui a créé l'installation.  
*Analogie Omeka Classic*: Superuser

**Installation**: Une instance de Omeka S. Typiquement, un service informatique qui a procédé à l'installation et probablement a aussi créé les sites pour d'autres.

**Item**: L'enregistrement qui est à la base de la mise en oeuvre d'un site Omeka S. Ces items sont partagés et disponibles pour chaque site de l'installation hormis si ils sont explicitement exclus du partage.  
*Analogie Omeka Classic*: Contenu (Item)

**Item Set**: Un agrégat d'items. Les items peuvent appartenir à plusieurs lots d'items.  
*Analogie Omeka Classic*: Collection, Items avec un même mot clé

**Media**: Représentation ou description additionnelle d'un item en plus des métadonnées. Typiquement, c'est un document qui peut-être un fichier (de n'importe quel type, y compris du texte ou des fragments de HTML) ou bien une ressource externe comme une vidéo YouTube, une présentation Slideshare, un flux Dspace, etc.  
*Analogie Omeka Classic*: Fichier (File) (analogie faible)

**Property**: A defined — to one degree or another — kind of metadata used to describe a Resource. The most common is dcterms:title, for the written, human-readable title of an Item. The Values for Properties can be written language intended for humans or other sentient beings to read (‘Literals’), Resources (understood here as internal to an Omeka S Installation), or External URIs (e.g., a URI to a DBpedia resource page).  
*Omeka Classic analogy*: Element

**Resource Template**: A set of pre-defined Properties, and optionally a Class, to use to guide Item creation and interpretation of Properties. Typical usage is to create a template for, e.g., a `foaf:Person` that makes Items using that template show the inputs for the expected or desired `foaf: properties`, and sets the Class of the Item to `foaf:Person`.  
*Omeka Classic analogy*: Item Type (but the analogy is weak) cf. Class

**Site Admin**: L'administrateur d'un site particulier au sein d'une installation Omeka S.
*Analogie Omeka Classic*: Superuser role

**Value**: The actual data that fills out the Resource-Property-Value triple. If the property is 'dcterms:title', a reasonable Value might be “Heart of Darkness”. Literal Values might also have information about the language in which that Value is expressed attached. Values can also be Resources or URIs to external data (preferably URIs that return RDF data, but I don’t think we’re going to enforce that).   
*Omeka Classic analogy*: Element Text

**Vocabulary**: Ontologie ou schéma de métadonnées. C'est un ensemble de classes et de propriétés de métadonnées au format RDF pour décrire une ressource. Ils ont été créés préalablement et peuvent êtres importés (avec quelques limitations) pour êtres utilisés dans une installation. L'ensemble le plus utilisé est celui des propriétés Dublin Core (dcterms:).  
*Omeka Classic analogy*: Jeux de métadonnées (Element Set)
