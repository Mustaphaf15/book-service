L'objectif de cet examen est de créer plusieurs services indépendamment déployables qui communiquent entre eux, en utilisant les facilités offertes par Spring Cloud et Spring Boot. Spring Cloud fournit des outils pour les développeurs pour construire rapidement et facilement des services de configuration d’enregistrement, ….
Spring Boot permet de son côté de construire des applications Spring rapidement aussi rapidement que possible, en minimisant au maximum le temps de configuration, d'habitude pénible, des applications Spring.
Questions 1 :
Créer les microservices suivants :
1. Book Service : Service principal, qui offre une API REST pour gérer (CRUD) des livres (ISBN, title, id_author, date).
2. Author Service : Service principal, qui offre une API REST pour gérer (CRUD) des auteurs (id, name, sexe).
3. Config Service : Service de configuration, dont le rôle est de centraliser les fichiers de configuration des différents microservices dans un endroit unique.
4. Proxy Service : Passerelle se chargeant du routage d’une requête vers l’une des instances d’un service, de manière à gérer automatiquement la distribution de charge.
5. Discovery Service : Service permettant l’enregistrement des instances de services en vue d’être découvertes par d’autres services.
Questions 2 :
La solution finale devra prendre en considération les contraintes suivantes :
1. Il est impossible d’ajouter des livres qui porte le même titre
2. Les noms des auteurs devraient être préfixé par Mr pour les hommes et Mdm pour les femmes.
3. Il est interdit d’ajouter plus que 100 livres par auteur
Questions 3 : L’application devrai pouvoir exposer en format JSON la liste des livres d’un auteur X incluent (nom auteur, titre livre, date de sortie).
