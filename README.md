# pur-beurre


Ce site permet de chercher des aliments, et de trouver des substituts meilleurs et les enregistrer.

### pour le tester : 

Cloner ce repository et créer un fichier secret.py dans purbeurre/purbeurre/ contenant une votre clé secrète dans une variable SECRET_KEY, et vos paramètres de Base de données dans DATABASES_INFO.
Installer les modules, faites les migrations, puis la CLI $ Python purbeurre/manage.py import_products QUANTITY, indiquer le nombre de prosuits à importer.

utiliser, $ Python purbeurre/manage.py runserver pour lancer le site.
