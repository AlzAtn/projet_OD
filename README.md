
# Nos API
Nos API proviennent de : https://data.iledefrance.fr/pages/home/ 

Nous avons selectioné 2 portants sur le secteur médical en Ile-de-France.

La première permet de récupérer des informations sur les médecins des communes d'IdF. 
Les paramètres utilisés pour effectuer la requête sont le code postal et le nom de la commune, cela permet de récupérer un ensemble d'informations sur les médecins (Nom, adresse, téléphone, spécialité...)

Lien API médecin : https://data.iledefrance.fr/explore/dataset/annuaire-et-localisation-des-professionnels-de-sante/information/

La seconde API est semblable  la première, fonctionne de la même facon mais porte sur les laboratoires d'analyses médicaaux. Le paramètre que nous avons utilisé est le code postal.
Cela nous permet de récupérer le nom du laboratoire et son adresse, cette dernière est moins fourni que la première.

Lien API Laboratoire : https://data.iledefrance.fr/explore/dataset/laboratoires_de_biologie_medicale/api/

Nous n'affichons pas l'ensemble des résultats que nous renvoient les API. En effet nous avons sélectionné les informations qui nous semblaient intéressantes à proposées mais aussi les informations qui étaient complètes, certaines variables étaient peu renseignées.


# Heroku

URL Heroku : https://projetodmiashs.herokuapp.com/

# Nos routes


route : '/laboratoire' utiliser pour recuperer les adresses et les noms des laboratoires
--- exemple : https://projetodmiashs.herokuapp.com/laboratoire

route : '/medecin' utiliser pour recuperer les noms, les spécialités de medcins ainsi que les numeros de téléphones
--- exemple : https://projetodmiashs.herokuapp.com/medecin





