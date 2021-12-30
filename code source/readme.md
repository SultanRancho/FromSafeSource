## **Développement**
FromSafeSource a été écrit en Python.

Le code source contient plusieurs fichiers, chacun associé à une tache.

**adaptation.py** : assemble le texte donné par l'utilisateur et la réponse

**choix_commande.py** : choisi la commande qui va rechercher l'information voulu par l'utilisateur

**commande.py** : contient les commandes qui vont chercher l'information dans wikipédia

**comprehension.py** : reconnait le type d'information recherché par l'utilisateur et sur quel sujet (ex: naissance, prénom)

**conversion.py** : convertis le sujet de la recherche (ex: prénom) et le convertis pour pouvoir l'intégrer dans l'url

**extraction_donnees.py** : intégre les données de la base dans des listes python

**lien.py** : récupère tous les liens d'une page html, en filtrant par mot-clés, et en gérant des exclusions

**list_source** : extrait les bons paramètres en fonction du type de source utilisé

**main.py** : déclenche le logiciel, gère les notifiactions et le texte de surlignage

**metadata.py** : extrait le titre de la source

**recherche.py** : ordonne les fonctions de recherche de la réponse

**source.py** : extrait le texte d'un fichier html

**struct_source** : extrait le texte d'un fichier html sous une forme de liste strucuturée
