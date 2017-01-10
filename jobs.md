---
title: Travaux en cours
---

Lorsqu'un usager lance une tâche susceptible de durer un certain temps, comme un import via l'API, il peut visualiser la progression de cette tâche à partir du lien *Jobs* du tableau de bord.  

Une table affiche l'état de chacune des tâches : achevé, arrêté ou en erreur. Cette table indique aussi identifiant *ID*, *class*, *Status* et *Owner* (l'usager qui a lancé la tâche). Vous pouvez trier les lignes, par ordre croissant ou décroissant, identifiant *ID*, *class*, *Status* et *Owner*  en utilisant les menus déroulants et le bouton situés au dessus de la table en haut à droite.

![Table of jobs including all status messages](/files/jobstable.png)

Pour voir les détails d'une tâche, cliquez sur son identifiant.

Dans cette page qui détaille une tâche, vous pourrez consulter les information suivantes :
- *Status* - In Progress (en cours), Error (en erreur), Completed (achevé), Stopped (arrêté)
- *Started* (démarré) et *Ended* (terminé) (horodaté)
- *Class* (origine de la tâche, par exemple `DspaceConnector\Job\Import`)
- *Owner*
- *Args*
- *Log* - Cliquez sur *view log* pour consulter d'éventuelles erreurs ou d'autres messages.

![The Logs heading with “view logs” below in orange, indicating it is a link](/files/jobs_viewlog.png)
