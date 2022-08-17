# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

#### Spec Restaurant model
- Un restaurant doit avoir un nom, une adresse et une catégorie.
- La catégorie du restaurant doit appartenir à cette liste fixe : ["chinese", "italian", "japanese", "french", "belgian"].
- Quand un restaurant est supprimé, tous ses avis doivent aussi être supprimés.

#### Spec Reviews model
- Un avis doit appartenir à un restaurant.
- Un avis doit avoir un contenu.
- Un avis doit avoir une note.
- La note d’un avis doit être un nombre entre 0 et 5.
- La note d’un avis doit être un entier. Par exemple, un avis avec une note de 2,5 doit être invalide !
