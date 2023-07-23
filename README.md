# Data Spliter

Cette fonction permet de diviser un ensemble de données CSV en trois parties : une partie pour le format JSON, une partie pour la base de données, et le reste pour le format CSV.

## Paramètres de la fonction

- **p_json** : Pourcentage de la partie JSON.
- **p_DB** : Pourcentage de la partie base de données.
- **csv_file_name** : Nom de votre fichier d'origine au format CSV.
- **file_json_name_part** : Nom du fichier JSON.
- **server** : Nom de votre serveur SQL.
- **database** : Nom de votre base de données.
- **table_name** : Nom de votre table.
- **file_Csv_name_part** : Nom du fichier CSV résultant.

## Exemple d'utilisation

```python
# Appel de la fonction data_spliter avec les paramètres appropriés
data_spliter(p_json=30, p_DB=20, csv_file_name='donnees.csv', file_json_name_part='data_json', 
             server='mon_serveur_sql', database='ma_base_de_donnees', table_name='ma_table', 
             file_Csv_name_part='data_csv')

Assurez-vous que la somme des pourcentages p_json et p_DB est inférieure ou égale à 100, et que le fichier d'origine est au format CSV (.csv). En cas d'erreur de paramètres, un message sera affiché à l'exécution.


Vous pouvez copier et coller ce texte dans un fichier README.md à la racine de votre projet sur GitHub pour documenter la fonction "Data Spliter". N'hésitez pas à personnaliser le texte et à ajouter d'autres informations pertinentes concernant votre projet.
