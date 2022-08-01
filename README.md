# pur-beurre

Ce site permet de chercher des aliments, et de trouver des substituts meilleurs et les enregistrer.

### pour le tester : 

Cloner ce repository, créer un environement virtuel et depuis celui ci installer les moduls nécessaire avec la comande: `pip install -r django-web-app/requirements.txt`

Dirriger vous avec votre invite de commande dans le dossier "django-web-app" et faite les migrations avec la commande: `python merchex/manage.py migrate`

Charger les données de l'api openff avec la commande: `python merchex/manage.py load_data (nombre de produits par catégories)`

utiliser,  `Python purbeurre/manage.py runserver` pour lancer le site.
