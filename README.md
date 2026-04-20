# tp-2-git
# Atelier Pratique 2 : Git et Travail Collaboratif

## Identification:
*  Nom : nadine
*  Email Git : naouinadine@gmail.com

## Objectifs du TP:
L'objectif de cet atelier était d'apprendre à utiliser Git dans un contexte collaboratif. J'ai appris à :
* Cloner un projet existant depuis GitHub vers mon ordinateur local.
* Envoyer mes modifications sur le serveur (Push).
* Récupérer les mises à jour effectuées par d'autres collaborateurs (Pull/Fetch).
* Gérer et résoudre manuellement un conflit de fusion (Merge Conflict).

## Journal des étapes réalisées:
1. **Configuration de l'identité :** Enregistrement de mon nom d'utilisateur et de mon adresse email dans le terminal pour signer mes futurs commits.
2. **Clonage du dépôt :** Récupération locale du dossier du projet `tp-2-git`.
3. **Création de contenu :** Ajout d'un fichier `participants.md` contenant mon nom et réalisation du premier commit.
4. **Simulation de conflit :** Modification simultanée du même fichier sur VS Code et sur l'interface web de GitHub pour provoquer un conflit lors de la synchronisation.
5. **Résolution du conflit :** Utilisation de l'outil de fusion de VS Code pour choisir l'option "Accept Both Changes" (Accepter les deux changements) afin de conserver toutes les informations.

##  les Commandes utilisées:
Voici les commandes Git manipulées durant cet atelier :
* `git config --global user.name "nadine"` : Définit le nom de l'auteur.
* `git config --global user.email "naouinadine@gmail.com"` : Définit l'email de l'auteur.
* `git clone <url>` : Télécharge le dépôt distant sur la machine locale.
* `git add participants.md` : Prépare le fichier pour le commit (Staging).
* `git commit -m "message"` : Enregistre les modifications dans l'historique local.
* `git pull` : Récupère et fusionne les changements distants sur mon ordinateur.
* `git push` : Envoie mes commits locaux vers GitHub.