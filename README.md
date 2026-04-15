----FinanceCore Project
### Description
Projet de traitement de données financières : nettoyage, modélisation (3NF) et stockage dans PostgreSQL.

### Modélisation (3NF)
Organisation des données pour éviter la redondance, avec séparation en عدة tables (Client, Agence, Segment, Transaction).

### Tech Stack
Python (Pandas, SQLAlchemy), PostgreSQL, psycopg2.

### Setup
Clonage du projet, création d’un environnement virtuel et installation des dépendances.

### PostgreSQL
Création de la base de données et des tables selon le modèle relationnel.

### Configuration (.env)
Définition des variables de connexion (user, password, host, port, database).

### Connexion
Connexion à la base de données avec SQLAlchemy.

### Load Data
Import des données CSV vers PostgreSQL.

### .gitignore
Ignorer les fichiers sensibles et temporaires
