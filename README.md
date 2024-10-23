# Data-Manipulation-language-DML-Checkpoint

Voici les commandes SQL pour insérer les données fournies dans les tables Customer, Product, et Orders.

Insertion dans la table Product
sqlINSERT
('P02', 'ASUS Notebook', 'PC',4599);  
Insertion dans la table Customer
sqlINSERT
('C02', 'ASMA', '77345823');  
Insertion dans la table Orders
Pour la date de commande, si vous utilisez un format de date standard (par exemple, ANSI), la commande peut être modifiée. Voici comment insérer les données :

sqlINSERT
('C02', 'P01', '2020-05-28',1,3299);  
Notez que :

Pour OrderDate, j'ai utilisé le format 'YYYY-MM-DD'. Si votre base de données nécessite un autre format, assurez-vous de l'ajuster en conséquence.
L'exemple ci-dessus suppose que l'ID de produit et l'ID de client existent déjà dans les tables correspondantes, ce qui est garanti par les insertions précédentes.
