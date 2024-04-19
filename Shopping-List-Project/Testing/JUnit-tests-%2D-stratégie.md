Par convention (Maven) tous les tests JUnit sont dans le répertoire src/test/java et sont placés dans le même package que la classe à tester.
Chaque test (methode de test) doit être atomique, indépendant des autres tests. Ils peuvent être lancés dans un ordre aléatoire.

# **Controllers**

Les controllers sont testés de manière unitaire en utilisant SpringBoot MockMVc et en mockant les services.

Le but du test des controllers est de tester les que les urls sont correctes, que les services sont bien appelés et que les réponses sont correctes (body json, différents codes http  (200, 404, 500, ...), messages de retour, ...) en fonction du type de service.

# **Services**

En rêgle générale les services sont testés de manière unitaire en mockant les repositories.

Vu que les services sont simples dans notre application, nous testeront les services sans mocker les repositories.
Ils couvreront donc aussi les tests d'integration en utilisant une base de donnée initialisée (voir **Repositories**)

# **Repositories**

En rêgle générale les repositories sont testés de manière intégrée avec une base de donnée qui a été préalablement chargée avec des données initiales.

Chaque test est par défaut inclut dans une transaction. Les données modifiées dans chaque méthode de test sont réinitialisées automatiquement.