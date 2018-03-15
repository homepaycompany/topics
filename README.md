Homepay - Guide Agile


1) Sujets à traiter (aka « bac rouge »)
Issues

Scope : Tous les collaborateurs
Raccourci : https://github.com/homepaycompany/topics/
Les sujets abordés sont traités par le biais des Issues de Github. Chaque sujet est visible pour l'ensemble des collaborateurs, dans un soucis de transparence.
La description de chaque sujet doit être précise, afin que tous les collaborateurs puissent s’y référer dans le futur sans demander des explications complémentaires. Tant qu’un problème n’est pas statué, l’issue reste ouverte. 
Les sujets abordés sont classés grâce à des libellés : real estate, tech, design, produit, data. 

Exemple de description d’issue pour une question opérationnelle :

- Summary: Summarize the issue encountered concisely
- What is the current operational behavior? What actually happens
- Relevant logs and/or screenshots: Paste any relevant references to discussed issues
- Possible fixes: If you can, propose different fixes to the current operational behavior


Bugs

Scope : Tous les collaborateurs
Raccourci : https://github.com/homepaycompany/homepay_rails_monolyth/issues?q=is%3Aopen+is%3Aissue+label%3Abug
Les collaborateurs font remonter tous les bugs qu’ils rencontrent sur le produit au fur et à mesure par le biais d’une Issue avec le label “bug”. Les bugs alimentent automatiquement le Sprint backlog. Le Lead developer priorise les différents bugs en les passant dans la colonne “Current sprint”.
Exemple de description d’issue pour un bug :

- Summary: Summarize the bug encountered concisely
- Steps to reproduce: How one can reproduce the issue - this is very important
- What is the current bug behavior? What actually happens
- What is the expected correct behavior? What you should see instead
- Relevant logs and/or screenshots: Paste any relevant logs - please use code blocks (```) to format console output, logs, and code as it's very hard to read otherwise.)
- Possible fixes: If you can, link to the line of code that might be responsible for the problem
2) Product roadmap
Product roadmap

Scope : Product owner
Raccourci : https://trello.com/b/PybbiBxY/product-roadmap
Les différentes user stories développées dans notre produit sont représentées à travers notre roadmap : 

- Ideas & requests : idées d’amélioration du produit en function des retours utilisateurs et des pistes de développement business.
- Committed : user stories qui sont programmées dans le prochain milestone
- Doing : user stories qui font l’objet d’Issues dans le sprint actuel
- Shipped – Month : Ensemble des features qui ont été shippées durant le mois M


3) Organisation des sprints
Milestone

Scope : Product owner
Fréquence : variable
Raccourci : https://github.com/homepaycompany/homepay_rails_monolyth/milestones
Il est important de définir des étapes clés dans le développement de notre application afin de préserver un niveau de progression. Chaque étape clé représente une version de l’application et est définie par un milestone sur Github. 

Exemple de milestone :

- Title : Homepay v.0
- Description: Access to the form on the landing Landing page including following user stories:
    i) As a seller, I am ready to provide information on my flat online in order to sell it
    ii) As a seller, I am able to accept a purchase offer online
    iii) As a seller, I want to test a simpler and more transparent process
- End date : 16/03/2018


User story

Scope : Product owner
Fréquence : hebdomadaire
Raccourci : https://github.com/homepaycompany/homepay_rails_monolyth/labels/user%20story
Tous les vendredis soirs, le Product owner décrit et priorise les user stories qui sont à ajouter dans le Sprint backlog sur Gitlab à travers des issues avec le label “User story”. Chaque Issue est liée à un milestone afin de suivre la progression du développement de l’application. Chaque user story doit être détaillée et illustrée avec des mockups Figma afin que le Lead dev puisse la comprendre et la retranscrire d’un point de vue technique.

Exemple de user story :

- Description : As a … I want to … so that I ….


Sprint backlog

Scope : Lead developer
Fréquence : hebdomadaire
Raccourci : https://github.com/homepaycompany/homepay_rails_monolyth/projects/1
Tous les lundis matins, le Lead dev priorise les User stories à développer en accord avec le Product owner. Pour cela, il utilise les issues qui alimenteront automatiquement la table Sprint backlog.
Il définit par ailleurs des objectifs atteignables pour le sprint de la semaine, en déplaçant les Issues du Sprint Backlog à la table Current Sprint et en les assignant à un membre de l’équipe. 

Development - https://github.com/homepaycompany/topics/projects/1

- Product backlog : 
- Sprint backlog : liste qui regroupe l’ensemble des issues techniques créées par le Lead dev afin de couvrir l’ensemble d’une user story définie dans le Product backlog
- Current sprint : liste des issues techniques à réaliser pour le sprint en cours
- In progress : liste des issues en cours de développement
- Ready to verify : issues techniques qui font l’object d’une merge request
- Done : issues techniques réalisées et vérifiées



Daily note

Scope : Tous les collaborateurs
Fréquence : quotidien
Les Issues qui sont en cours sont déplacées dans la table “In progress”. Il ne doit pas y avoir plus de 2 issues traitées en même temps par un collaborateur.
Lorsqu’une Issue est terminée, elle est sujet d’une pull request et automatiquement déplacée dans la colonne “Ready to verify”.
Lorsque la pull request est examinée et traitée, l’Issue est automatiquement déplacée dans la colonne Done.   
Chaque matin, chaque membre de l’équipe décrit dans le channel Slack #sprint les Issues qu’il a réglé la veille et celles qu’il va attaquer sur la journée.

Exemple de daily note :

- Closed issues: I have tackled issue n°203 yesterday and fixed the bugs described in the issues n°244 and n°245.
- Encountered difficulties: I have spent some time on the issue n°244 as the steps to reproduce the bug were not well explained.
- Ongoing issues: I will implement a background job for the subscription in order to tackle the issue n°251.
