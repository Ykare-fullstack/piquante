# Projet 6 - OpenClassroom formation qualifiante WebDev #

## Construisez une API sécurisée pour une application d'avis gastronomiques ##

</br>

## Installation ##

Here are the dependancies you need to install:
- NodeJS 12.14 or 14.0.
- Angular CLI 7.0.2.
- node-sass : make sure to use the corresponding version to NodeJS. For Noe 14.0 for instance, you need node-sass in version 4.14+.

On Windows, these installations require to use PowerShell in administrator mode.

Then, clone this repo, run `npm install`, and run `npm install --save-dev run-script-os`.

</br>

## Usage ##

Run `npm start`. This should both run the local server and launch your browser.

If your browser fails to launch, or shows a 404 error, navigate your browser to http://localhost:8080.

The app should reload automatically when you make a change to a file.

Use `Ctrl+C` in the terminal to stop the local server.
</br>

## Runtime and framework versions ##

NodeJS v16.14
Mongoose 6.0.0
node-sass v7.0.1

</br>

### Compétences évaluées ###

En vous basant sur les critères d’évaluation du projet, définissez le statut d’acquisition de chaque compétence et commentez à l'aide de ces instructions :

- [X] Validé - Commentez si besoin

- [ ] Non validé - Listez les critères non remplis  

Compétences évaluées

En vous basant sur les critères d’évaluation du projet, définissez le statut d’acquisition de chaque compétence et commentez à l'aide de ces instructions :

Validé - Validé après des modifications mineurs effectuées par Alan sous 48h.

1. Mettre en œuvre des opérations CRUD de manière sécurisée

- [X] Validé 

Commentaires :

    Toute les opérations CRUD demandé sont présentes.

2. Implémenter un modèle logique de données conformément à la réglementation

- [X] Validé 

3. Stocker des données de manière sécurisée

- [X] Validé

Commentaires :

    Les mots de passe son bien sécurisés dans la base de données.

Livrable

Points forts :

    Utilisation des variables d'environnement pour les coordonnées de la BDD, ce qui peut très très avantageu quand on travaille dans un projet à multiple environnements.

Axes d'amélioration :

    Revoir la partie sécurité (notament pour le prochain projet), ça serait plus pertinent de mettre en place la partie sécurité dans le middleware que dans les controlleurs.

Soutenance

Remarques :

</br>
</br>
</br>
English version
--------------------

# Projet 6 - OpenClassroom WebDev qualifying training program #

## Build a secure API for a gastronomic review app ##

</br>

### Evaluated skills ###

Based on the project evaluation criteria, define the level of acquisition of each particular skill as such :

- [X] Validated - Comment if needed

- [ ] Not validated - List all non-filled criteria 

Evaluated skills

Commentaries :

    Every CRUD operation is functional.

2. Implement a logical data model that follow regulation

- [X] Validated 

3. Store data securely

- [X] Validated

Commentaries :

    Passwords correctly hashed and stored in the database.

Delivrable

Stron Points :

    Usage of env variable.

Axes d'amélioration :

    Review security (should be in middleware, not in controller).

Oral presentation

Commentaries :
