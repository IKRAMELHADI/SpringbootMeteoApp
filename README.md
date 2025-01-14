TP3 - Étape 5 : Description des dépendances
Spring Web :
Permet de gérer le développement d'applications web en prenant en charge les requêtes HTTP.

Spring Data JPA :
Simplifie l'accès aux bases de données grâce à l'utilisation d'annotations, notamment pour définir les entités.

H2 Database :
Utilisée comme base de données pendant les phases de développement et de tests.

Spring Boot DevTools :
Fournit des outils de développement, comme la recompilation automatique du code après chaque modification.

Thymeleaf :
Moteur de template basé sur HTML, permettant de générer des vues dynamiques.

TP3 - Étape 13 : Controller
Paramétrage de l’URL d’appel :
L’URL /greeting est définie grâce à l’annotation @GetMapping("/greeting").

Choix du fichier HTML :
Le fichier HTML affiché est sélectionné avec la ligne : return "greeting";.

Envoi d’informations à la vue :
L'attribut nomTemplate est associé à la valeur de name précisée dans l'URL via la méthode addAttribute().

TP3 - Étape 17 : Nouvelle table générée
Une nouvelle table correspondant à l'entité Address est créée.
TP3 - Étape 18 : Génération de la table
La table Address est générée automatiquement grâce à l'annotation @Entity sur la classe Address.
Cette annotation indique à Hibernate (le fournisseur JPA utilisé par Spring Boot) de créer une table correspondant à cette entité. Hibernate analyse les entités au démarrage de l'application et génère le schéma de la base de données en fonction des annotations.
TP3 - Étape 20 : Requête sur la table
Après exécution d'une requête SELECT sur la table Address, on peut visualiser les entrées ajoutées dans le fichier data.sql.
TP3 - Étape 22 : Injection de dépendances avec @Autowired
L'annotation @Autowired permet à Spring de rechercher et d'injecter automatiquement un bean correspondant dans une classe ou un composant.
