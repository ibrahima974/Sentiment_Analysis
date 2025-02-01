Description des données:

La table contient des données textuelles associées à des sentiments exprimés sur les réseaux sociaux. Elle est sera utilisée pour entraîner et évaluer un modèle de classification de sentiment associé aux tweet.
La table comprend les colonnes suivantes :

target: Cette colonne représente la polarité du sentiment exprimé dans le texte. Elle peut prendre deux valeurs :
   Valeur 0 : correspond à un sentiment négatif.
   Valeur 4 : correspond à un sentiment positif.
ids: Identifiant unique associé à chaque enregistrement.

date: La date et l'heure de la publication du texte.

flag: Un marqueur indiquant la provenance des données. Il peut prendre les valeurs suivantes :

"NO_QUERY" : indique que les données ne proviennent pas d'une requête spécifique.

Autres valeurs : peuvent indiquer la requête ou l'origine des données.

user: Le nom d'utilisateur de l'auteur du texte.

text: Le texte du tweet ou du message exprimant le sentiment.

Lien des donnees : https://www.kaggle.com/datasets/kazanova/sentiment140
