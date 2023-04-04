[![Github Badge ><](https://camo.githubusercontent.com/1118e904a8d4e042d81c6c8a66d347e51f9ecbbf58ad32a356cd41e9b5a5ffd6/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d4769746875622d3030303f7374796c653d666c61742d737175617265266c6f676f3d476974687562266c6f676f436f6c6f723d7768697465266c696e6b3d68747470733a2f2f6769746875622e636f6d2f677265676f7279367a)](https://github.com/gregory6z)  [![Linkedin Badge](https://camo.githubusercontent.com/0ba8173136b7afd8476f56ca9361a0e9ae72604461ff58d40807761c08406923/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d4c696e6b6564496e2d626c75653f7374796c653d666c61742d737175617265266c6f676f3d4c696e6b6564696e266c6f676f436f6c6f723d7768697465266c696e6b3d68747470733a2f2f7777772e6c696e6b6564696e2e636f6d2f696e2f677265676f72792d70726178656465732d3231383962343230372f)](https://www.linkedin.com/in/gregory-praxedes-2189b4207/)  [![Gmail Badge](https://camo.githubusercontent.com/375331eabb1f08d5f4ca82bc1c5aba680051d46ad91bee986f98e6e3237ac129/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d476d61696c2d6331343433383f7374796c653d666c61742d737175617265266c6f676f3d476d61696c266c6f676f436f6c6f723d7768697465266c696e6b3d6d61696c746f3a677265676f727972616740676d61696c2e636f6d)](mailto:gregoryrag@gmail.com)

# Gym API SOLID

Ceci est une API inspirée de l'application Gympass, conçue pour gérer les inscriptions et les check-ins dans des salles de sport. L'API est développée en utilisant le langage de programmation JavaScript et les technologies suivantes

## Technologies utilisées

-   [Node.js](https://nodejs.org/) - plateforme d'exécution JavaScript
- [TypeScript](https://www.typescriptlang.org/) - Langage de programmation typé
-   [Fastify](https://www.fastify.io/) - framework Web rapide
- [Docker Compose](https://docs.docker.com/compose/) - Outil pour la gestion des conteneurs Docker
-   [Prisma](https://www.prisma.io/) - ORM (Object-Relational Mapping) pour Node.js
-   [PostgreSQL](https://www.postgresql.org/) - système de gestion de base de données relationnelle
- [ViTest](https://github.com/dmitrykurmanov/vitest) - Bibliothèque de tests unitaires pour JavaScript/TypeScript.
-   [Zod](https://github.com/colinhacks/zod) - validation de schémas de données
-   [GitHub Actions](https://github.com/features/actions) - outil d'automatisation des workflows de développement logiciel
-    [Day.js](https://day.js.org/) - manipulation de dates et d'heures légères



## Installation

Pour installer et exécuter l'API, suivez les étapes ci-dessous :

## Installation

1.  Clonez ce dépôt avec `git clone https://github.com/gregory6z/gym-api-solid.git`
2.  Placez-vous dans le répertoire avec `cd gym-api-solid`
3.  Installez les dépendances avec `npm install`
4.  Lancez l'application avec `docker-compose up`

## Liste de vérification des fonctionnalités

### RF - Exigences fonctionnelles

- [x]  Il doit être possible de s'inscrire
- [x] Il doit être possible de se connecter
-  [x] Il doit être possible d'obtenir le profil de l'utilisateur connecté
- [x]  Il doit être possible d'obtenir le nombre de check-ins effectués par l'utilisateur connecté
- [x]  Il doit être possible pour l'utilisateur d'obtenir son historique de check-ins
-  [x] Il doit être possible pour l'utilisateur de rechercher des salles de gym à proximité (jusqu'à 10 km)
- [x]  Il doit être possible pour l'utilisateur de rechercher des salles de gym par nom
- [x]  Il doit être possible pour l'utilisateur de faire un check-in dans une salle de gym
- [x]  Il doit être possible de valider le check-in d'un utilisateur
- [x]  Il doit être possible d'ajouter une salle de gym

### RN - Règles métier

- [x] L'utilisateur ne doit pas pouvoir s'inscrire avec une adresse e-mail en double
- [x]  L'utilisateur ne peut pas effectuer 2 check-ins le même jour
- [x]  L'utilisateur ne peut pas faire de check-in s'il n'est pas à proximité (100m) de la salle de gym
- [x]  Le check-in ne peut être validé que jusqu'à 20 minutes après sa création
- [x]  Le check-in ne peut être validé que par des administrateurs
- [x]  La salle de gym ne peut être ajoutée que par des administrateurs

### RNF - Exigences non fonctionnelles

- [x]  Le mot de passe de l'utilisateur doit être crypté
- [x]  Les données de l'application doivent être stockées dans une base de données PostgreSQL
- [x]  Toutes les listes de données doivent être paginées avec 20 éléments par page
- [x]  L'utilisateur doit être identifié par un JWT (JSON Web Token)

&nbsp;


<p align="center">developed by  <a href="https://www.linkedin.com/in/gregory-praxedes-2189b4207/">Gregory Praxedes</a> </p>
# gym-api-solid
# gym-api-solid
