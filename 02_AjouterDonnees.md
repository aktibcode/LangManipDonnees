# Chapitre : AJOUTER DES DONNEES


# Insérer dans la clause

**Insertion implicite :** insertion dans toutes les colonnes du tableau

```
INSERT INTO table_name VALUES
(
value_column1,
value_column2,
...,
value_columnn
);
```

Le nombre de valeurs de colonne doit être égal au nombre de colonnes du tableau et du même type

# Insérer dans la clause

**Insertion explicite :** insertion dans une liste de colonnes spécifiée

```
INSERT INTO table_name
(
column1,
column2,
column3
)
VALUES
(
value_column1,
value_column2,
value_column3
);
```

# Insérer dans la clause

* Les valeurs à ajouter doivent vérifier les contraintes définies sur la table des colonnes.
* Tout enregistrement qui ne vérifie pas les contraintes sera rejeté.
* Les colonnes créées avec la contrainte NOT NULL doivent avoir des valeurs.
* Nous pouvons utiliser la syntaxe suivante pour insérer des données à partir d'une table.

```
INSERT INTO table_name (column1,column2)
SELECT column1, column2 from table_name1;
```

Ces ressources peuvent vous aider

Manipulation des données

[https://www.tutorialspoint.com/sql_certificate/manipulated_data.htm](https://www.tutorialspoint.com/sql_certificate/manipulating_data.htm)
