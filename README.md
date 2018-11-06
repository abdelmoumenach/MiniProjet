# MiniProjet
# 1 - L'architecture globale de l'application : 
# système M-V-C (Model-View-Controller)
En utilisant Le MVC pour séparer notre application en 3 couches principales :
# La couche Model
La couche Model représente la partie de l’application qui exécute la logique métier. Cela signifie qu’elle est responsable de récupérer les données, de les convertir selon des concepts chargés de sens pour votre application, tels que le traitement, la validation, l’association et beaucoup d’autres tâches concernant la manipulation des données.
A première vue, l’objet Model peut être vu comme la première couche d’interaction avec n’importe quelle base de données que vous pourriez utiliser pour votre application. Mais plus globalement, il fait partie des concepts majeurs autour desquels vous allez exécuter votre application.
Dans le cas d’un réseau social, la couche Model s’occupe des tâches comme de sauvegarder des données, de sauvegarder des associations d’amis, d’enregistrer et de récupérer les photos des utilisateurs, de trouver des suggestions de nouveaux amis, etc … Tandis que les objets Models seront « Ami », « User », « Commentaire », « Photo ».

# La couche Vue
La Vue retourne une présentation des données venant du model. Etant séparée par les Objets Model, elle est responsable de l’utilisation des informations dont elle dispose pour produire une interface de présentation de votre application.
Par exemple, de la même manière que la couche Model retourne un ensemble de données, la Vue utilise ces données pour fournir une page HTML les contenant. Ou un résultat XML formaté pour que d’autres l’utilisent.
La couche Vue n’est pas seulement limitée au HTML ou à la répresentation en texte de données. Elle peut aussi être utilisée pour offrir une grande variété de formats en fonction de vos besoins, comme les vidéos, la musique, les documents et tout autre format auquel vous pouvez penser.

# La couche Controller
La couche Controller gère les requêtes des utilisateurs. Elle est responsable de retourner une réponse avec l’aide mutuelle des couches Model et Vue.
Les Controllers peuvent être imaginés comme des managers qui ont pour mission que toutes les ressources souhaitées pour accomplir une tâche soient déléguées aux travailleurs corrects. Il attend des requêtes des clients, vérifie leur validité selon l’authentification et les règles d’autorisation, délèguent les données récupérées et traitées par le Model, et sélectionne les type de présentation correctes que le client accepte, pour finalement déléguer le processus d’affichage à la couche Vue.

# 2 - L'architecture de la couche donnée :
Le SQL c'est un langage relationnel, il manipule donc des tables (i.e. des relations, c'est-à-dire des ensembles) par l'intermédiaire de requêtes qui produisent également des tables.
# 3 - La maniere de gestion des demandes des clients :
Mode de gestion des requetes :
Iteratif:
Le Processus server traite les requetes les unes apres les autres . 

# 4 - Les technologies choisies pour le developpement :

- SQL : SQL est un langage informatique normalisé servant à exploiter des bases de données relationnelles.
- HTML : L’HyperText Markup Language, généralement abrégé HTML, est le langage de balisage conçu pour représenter les pages web.
- Bootstrap : Bootstrap is a free and open-source front-end framework for designing websites and web applications.
- Java EE : Java EE includes several specifications that serve different purposes, like generating web pages, reading and writing from a - database in a transactional way, managing distributed queues.

# ACHACHE ABDELMOUMEN
# FERGANI DIA EL EDINNE 
