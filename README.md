# SYMFONY - CRUD
- **QUÊTE** - PHP Symfony - *Créer un CRUD*
- *171017_SymfonyCrud/171017_SymfonyCrud_Quete*
----
**Générons du CRUD**

Pour finir en beauté, je te propose de générer les entités suivantes et les CRUD qui vont avec. Seuls les administrateurs pourront créer de nouveaux terrains, alors nous ne génèrerons pas les actions d'écriture pour cette entité. Poste le lien de la release (q_crud) quand tu as fini (n'oublie pas de push).

**Schéma entités**

Pas de panique, Symfony n'est pas qu'une histoire de génération. Nous mettrons les mains dans le code dès la prochaine quête.
Pour info, en aviation les terrains (aéroports, aérodromes, altiports, …) sont identifiés par un code à 4 lettres, attribué par l'ICAO (International Civil Aviation Organization).

Pense à mettre à jour le schéma de ta BDD

**Critéres de validation**
- Les entités sont toutes générées dans le bon bundle
- Elles sont nommées en CamelCase
- Elles contiennent les bonnes propriétés et ces propriétés sont nommées et typées correctement
- La config de chaque entité est en annotation
- Les CRUD sont générés pour chaque entité
- Les entités Flight et Reservation ont des actions d'écriture mais pas le Terrain
- La config des CRUD est en annotation
- Les routes sont cohérentes et fonctionnelles (même si le générateur n'a pas réussi à tout faire tout seul)
- L'accès aux tables (par Phpmyadmin ou l'onglet Database de PhpStorm) est fonctionnel.


> [WildCodeSchool](https://wildcodeschool.fr/)










