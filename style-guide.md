# Style Guide

## Terminologie

**Admin/Administrative Dashboard**: le tableau de bord à partir duquel est administrée la totalité de l'installation Omeka S et d'où sont gérés items, vocabularies, modules, etc.

**Site Dashboard**: tableau de bord spécifique à chaque site pour la gestion des contenus et de leur agencement, etc.

**sidebar**:  the things which slide open on the right of the screen when you click an ellipses.

Voir aussi le [glossaire](glossary.md)

## Formatage

Les noms de pages doivent comporter des minuscules (non accentuées) et les espaces sont remplacés par des tirets(soit admin-dashboard.md pour Administrative Dashboard page).

Tous les liens relatifs doivent commencer par .. (soit .. / content / etc.)

Chaque référence interne à une images à afficher est un chemin relatif débutant par ./ ou ../ suivi du chemin vers cette image ; si l'image est au même niveau que le document qui l'appelle, indiquer seulement son nom.

- Omeka S s'écrit *avec* une espace entre Omeka et le S.
- Les intitulés de boutons sont en *italique*
- Les intitulés d'options sont en *italique*
- Describe icons based on their tooltip, ex. edit (pencil icon), delete (trash can icon), details (ellipses icon). This way the text is useful for people using screen readers as well as those who are not.
- Les actions Ajouter (Add), Editer (Edit) et (Delete) doivent êtres décrites séparément, chacune avec son propre entête.
- Utiliser H2 (##) pour chaque sous-sections d'une page de la documentation.

## Générer la documentation au format pdf

pour la version francophone, utilisation de pandoc
