### Organisation des sprints
#### Milestone
**Scope :** Product owner
**Fréquence :** variable
**Raccourci :** https://github.com/homepaycompany/homepay_rails_monolyth/milestones
Il est important de définir des étapes clés dans le développement de notre application afin de préserver un niveau de progression. Chaque étape clé représente une version de l’application et est définie par un milestone sur Github. 

Exemple de milestone :
- **Title:** Homepay v.0
- **Description:** Access to the form on the landing Landing page including following user stories:
    i) As a seller, I am ready to provide information on my flat online in order to sell it
    ii) As a seller, I am able to accept a purchase offer online
    iii) As a seller, I want to test a simpler and more transparent process
- **End date:** 16/03/2018

---

#### User story
**Scope :** Product owner
**Fréquence :** hebdomadaire
**Raccourci :** https://github.com/homepaycompany/homepay_rails_monolyth/labels/user%20story
Tous les vendredis soirs, le Product owner décrit et priorise les user stories qui sont à ajouter dans le Sprint backlog sur Gitlab à travers des issues avec le label “User story”. Chaque Issue est liée à un milestone afin de suivre la progression du développement de l’application. Chaque user story doit être détaillée et illustrée avec des mockups Figma afin que le Lead dev puisse la comprendre et la retranscrire d’un point de vue technique.

Exemple de user story :
- **Description:** As a … I want to … so that I ….

---

#### Sprint backlog

**Scope :** Lead developer
**Fréquence :** hebdomadaire
**Raccourci :** https://github.com/homepaycompany/homepay_rails_monolyth/projects/1
Tous les lundis matins, le Lead dev priorise les User stories à développer en accord avec le Product owner. Pour cela, il utilise les issues qui alimenteront automatiquement la table Sprint backlog.
Il définit par ailleurs des objectifs atteignables pour le sprint de la semaine, en déplaçant les Issues du Sprint Backlog à la table Current Sprint et en les assignant à un membre de l’équipe. 
Une issue peut être fermée à partir d’une pull request en utilisant la syntaxe suivante dans le Body de la pull request : “Pull request for the Issue #1”. 

**Development - https://github.com/homepaycompany/topics/projects/1**
**- Product backlog :** liste qui regroupe l'ensemble des user stories abordées durant le sprint
**- Sprint backlog :** liste qui regroupe l’ensemble des issues techniques créées par le Lead dev afin de couvrir l’ensemble d’une user story définie dans le Product backlog
**- Current sprint :** liste des issues techniques à réaliser pour le sprint en cours
**- In progress :** liste des issues en cours de développement
**- Ready to verify :** issues techniques qui font l’object d’une merge request
**- Done :** issues techniques réalisées et vérifiées

---

### Daily note

**Scope :** Tous les collaborateurs
**Fréquence :** quotidien
Les Issues qui sont en cours sont déplacées dans la table “In progress”. Il ne doit pas y avoir plus de 2 issues traitées en même temps par un collaborateur.
Lorsqu’une Issue est terminée, elle est sujet d’une pull request et automatiquement déplacée dans la colonne “Ready to verify”.
Lorsque la pull request est examinée et traitée, l’Issue est automatiquement déplacée dans la colonne Done.   
Chaque matin, chaque membre de l’équipe décrit dans le channel Slack #sprint les Issues qu’il a réglé la veille et celles qu’il va attaquer sur la journée.

Exemple de daily note :
- **Closed issues:** I have tackled issue n°203 yesterday and fixed the bugs described in the issues n°244 and n°245.
- **Encountered difficulties:** I have spent some time on the issue n°244 as the steps to reproduce the bug were not well explained.
- **Ongoing issues:** I will implement a background job for the subscription in order to tackle the issue n°251.
