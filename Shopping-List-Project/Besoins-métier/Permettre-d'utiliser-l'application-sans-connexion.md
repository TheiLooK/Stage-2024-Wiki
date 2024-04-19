# Contexte
Aujourd'hui les utilisateurs doivent être connectés pour pouvoir accéder aux fonctionnalités de l'application.
Ils ont accès à l'ensemble des fonctionnalités. Sans l'API l'application n'est pas utilisable.


# Objectif
Permettre l'utilisation de l'application Mobile sans connexion.
Pouvoir à plus long terme contrôler les fonctionnalités additionnelle proposées à chaque utilisateur pour une éventuelle facturation des services.

# Périmètre


# Description fonctionnelle
**1. Par défaut l'application ne se connecte pas à l'API sauf pour:**
- chargement des produits de base
- chargement des catégories

En cas de problème de chargement l'utilisateur ne reçoit pas d'erreur, les listes sont vides et seulement alimentées par ce que l'utilisateur aura saisi.

L'utilisateur n'a pas besoin de fournir son adresse mail.

**2. Lorsque l'utilisateur ajoute de nouveaux produits ils ne sont pas joutés sur le serveur**

**3. Lorsque l'utilisateur veut partager une liste il doit fournir son adresse mail**

**4. Lorsque la liste est partagée toutes les données sont synchronisées sur le serveur**

**5. Lorsqu'un utilisateur inscrit partage une liste, le destinataire doit saisir son adresse mail pour y accéder**

# Délais




