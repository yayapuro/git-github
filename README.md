# EXPOSÉ GIT & GITHUB


![Capture du repository GitHub](1.png)
## Introduction
Dans un projet numérique, une erreur ou un manque de coordination peut rapidement faire perdre du travail.
Git permet de gérer les versions d’un projet, tandis que GitHub facilite la collaboration en ligne.
Cette présentation montrera que ces outils ne servent pas seulement à programmer, mais aussi à organiser, sécuriser et partager le travail de manière efficace.
![Capture du Plan](2.png)
## Git : l’outil de gestion de versions
![Capture du repository GitHub](3.png)

1. Définition de Git
•       Git = logiciel de gestion de versions (Version Control System / VCS)
•       S'installe sur l'ordinateur, fonctionne en local (sans internet)
•       Créé en 2005 par Linus Torvalds (créateur du noyau Linux)
•       Standard mondial : utilisé par +90% des développeurs professionnels
 
2. Le problème que Git résout
•       Sans Git : multiplication des fichiers (v1, v2, final, VRAIMENT_final…)
•       Risque d'écraser le travail des autres
•       Impossible de savoir quelle est la bonne version
•       Avec Git : un historique unique, propre et structuré de toutes les modifications
 
3. Les 3 zones de travail (technique)
•       Working Directory = le dossier sur l'ordi où on travaille directement
•       Staging Area = zone de préparation : on sélectionne les fichiers à sauvegarder (commande : git add)
•       Repository local = base de données cachée où Git stocke tout l'historique (≠ repository GitHub, c'est la partie de Sofiane & Syam)
 
4. Le commit (notion centrale)
•       Commit = sauvegarde validée d'un état précis du projet (= point de sauvegarde)
•       Deux étapes : git add (sélectionner) → git commit (valider avec un message)
•       Chaque commit contient : les modifications, un message, une date, le nom de l'auteur
•       Hash = identifiant unique généré automatiquement par Git pour chaque commit (ex: a3f4b2c)
•       Permet de retrouver et restaurer n'importe quelle version à tout moment
 
5. L'historique et la traçabilité
•       Git garde tous les commits dans l'ordre chronologique
•       On voit : qui a modifié quoi, quand, et pourquoi (via le message)
•       Traçabilité = on peut identifier à quel commit un bug a été introduit
•       Possibilité de revenir à une version précédente à tout moment
 
6. La limite de Git → transition vers GitHub
•       Git fonctionne uniquement en local → historique sur l'ordi uniquement
•       Les coéquipiers n'ont pas accès aux commits
•       Si l'ordi tombe en panne → tout est perdu
•       Impossible de synchroniser le travail en équipe
•       Solution → une plateforme en ligne : GitHub (partie Sofiane & Syam)



## GitHub : la plateforme de collaboration
![Capture du repository GitHub](4.png)
![Capture du repository GitHub](5.png)

PARTIE III – GitHub : la plateforme de collaboration

1. Positionnement

GitHub = site web pour héberger un projet Git en ligne
Analogie : Google Drive mais pour les projets
Différence clé : Git = outil local / GitHub = plateforme collaborative
+100 millions d'utilisateurs, racheté par Microsoft en 2018

![Capture du repository GitHub](6.png)
2. Le Repository

Repo = dossier du projet hébergé en ligne
Contient les fichiers + tout l'historique des modifications
Clone = copier le repo sur son ordi pour travailler en local
Notre repo : fichiers, notes, Wiki, image de démo
![Capture du repository GitHub](7.png)
3. Workflow collaboratif

Commit → Push → Pull : cycle de base
Commit = sauvegarder une étape avec un message
Push = envoyer son travail sur GitHub
Pull = récupérer le travail des autres
![Capture du repository GitHub](8.png)
4. Branches

Main = version officielle et stable → on n'y touche pas directement
Branche = espace de travail isolé par membre
Feature branch workflow : une branche par personne/fonctionnalité
Merge = fusionner sa branche dans main
Conflits = deux personnes modifient le même fichier → à régler manuellement
![Capture du repository GitHub](9.png)
5. Pull Request

PR = demande de fusion formelle avant de merger
Permet la revue de code : commentaires, corrections, validation
Tout est tracé et historisé
Standard dans tous les projets professionnels
![Capture du repository GitHub](10.png)

6. Fonctionnalités complémentaires

Issues : suivi des tâches et bugs
GitHub Actions : automatisation (tests, déploiement) → CI/CD
Wiki : documentation du projet → utilisé pour centraliser nos infos de groupe
## Cas pratique
![Capture du repository GitHub](17.png)
![Capture du repository GitHub](18.png)
Dans le cadre de notre exposé, nous avons choisi d’utiliser directement GitHub comme support de travail.
Au lieu de prendre un exemple fictif, nous avons créé un repository dédié à notre présentation afin d’y regrouper les contenus, les images et les différentes étapes du projet.
![Capture du repository GitHub](14)
Le repository constitue l’espace central du projet.
Il permet d’héberger les fichiers en ligne, d’ajouter progressivement du contenu et de conserver une trace de toutes les modifications effectuées.
Nous y avons intégré :
le fichier README.md
des captures d’écran
des éléments du diaporama
les différentes parties de l’exposé
Chaque modification est enregistrée par un commit, ce qui permet de suivre précisément l’évolution du travail.
![Capture du repository GitHub](15)
Le repository apparaît dans l’espace personnel GitHub de l’utilisateur.
Il est accessible en ligne et peut être consulté ou modifié par les membres autorisés du projet.
Cette organisation permet de centraliser les ressources dans un seul espace, plutôt que de multiplier les fichiers sur différents ordinateurs.
![Capture du repository GitHub](16)
GitHub facilite le travail collaboratif.
Plusieurs membres peuvent intervenir sur le même projet, chacun en apportant ses propres modifications.
Le repository partagé permet donc :
de regrouper tous les fichiers au même endroit
d’identifier les différents contributeurs
de suivre les commits, branches et mises à jour
L’ensemble du travail reste ainsi organisé, lisible et accessible à tous les membres du groupe.
![Capture du repository GitHub](19.png)
Pour intégrer une modification importante, GitHub propose le système de Pull Request.
Cette fonctionnalité permet de proposer des changements avant leur fusion dans la branche principale.
La Pull Request sert à :
comparer les versions
relire les ajouts
commenter les modifications
valider l’intégration finale
C’est un outil essentiel dans les projets collaboratifs, car il sécurise le travail avant la fusion.
![Capture du repository GitHub](22)
Au-delà du simple stockage de fichiers, GitHub propose plusieurs fonctionnalités techniques complémentaires.
Parmi les plus importantes :
Branches
Elles permettent de travailler sur des versions séparées du projet sans modifier directement la branche principale.
Pull Requests
Elles servent à vérifier et valider les changements avant leur fusion.
GitHub Actions
Elles permettent d’automatiser certaines tâches, comme les tests ou le déploiement.
GitHub devient ainsi une véritable plateforme de développement, de vérification et d’automatisation.
![Capture du repository GitHub](23)
![Capture du repository GitHub](20.png)
![Capture du repository GitHub](25)
![Capture du repository GitHub](26)
Une fois les changements validés, la Pull Request peut être fusionnée dans la branche principale.
Cela signifie que les modifications proposées sont désormais intégrées dans la version officielle du projet.
Ce fonctionnement montre concrètement comment GitHub permet :
de structurer le travail
de contrôler les modifications
de collaborer de manière plus professionnelle
## Avantages de Git & GitHub
![Capture du repository GitHub](12.png)
## Conclusion
![Capture du repository GitHub](13.png)
