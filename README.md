# SYMFONY - RELATIONS
- **QUÊTE** - PHP Symfony - *Relations dans le CRUD*
- *171026_SymfonyCrudRelations/171026_SymfonyCrudRelations_Quete*
----
**Mise en place des relations**

Le challenge est simple : Il te faut mettre à jour les entités et les configs de Doctrine pour qu'elles correspondent au nouveau schéma de BDD. Il te faut donc : - Mettre à jour la table Reservation pour un champ restant. - Créer une entité et la lier avec User avec 2 champs en particulier. - Mettre à jour la table Flight concernant 3 champs. - Mettre à jour tous les CRUD dont l'entité a été modifiée sauf pour l'entité Review.

Attention ! Les relations bidirectionnelles ne sont pas pertinentes à chaque fois. Veille donc à bien visualiser les relations entre les tables notamment en imaginant le fonctionnement général du projet et en te posant plusieurs questions clés : - Il y a t'il plusieurs utilisateurs pour un seul avis, ou plusieurs avis pour un utilisateur ? - Un vol de particuliers contient-il plusieurs pilotes ou un seul ? Est-ce qu'un pilote peut réaliser plusieurs vols ? - Etc ..

Pour finir, voici un petit conseil : Lorsque que tu ajoutes des relations entre tables (ex: FK), évite de le faire avec celles-ci remplies, car tu peux tomber sur des contraintes d'intégrités et de violations.

Une fois le challenge terminé, regarde les erreurs ou les warnings soulignés par PHPStorm (il te faut avoir installé le plugin Symfony des premières quêtes). En effet, tu changes des champs en clés étrangères mais les anciennes méthodes associées existent toujours. Il en va de même pour les chemins absolus générés par la CLI Doctrine.
Critéres de validation

**Critéres de validation**
- Les entités correspondent exactement au nouveau schéma de BDD
- Il n'y a pas d'erreur quand on lance un doctrine:schema:update
- Les relations bidirectionnelles sont utilisées à bon escient et dans le bon sens
- Les CRUD ont été mis à jour sauf pour l'entité Review
- Les fichiers ne contiennent aucun warning relevé par PHPStorm
- Toutes les routes (référencées en debug:router) sont fonctionnelles

> [WildCodeSchool](https://wildcodeschool.fr/)










