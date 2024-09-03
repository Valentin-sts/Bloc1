# 1 - Méthodes GET et POST

 	# Différences entre les méthodes HTTP GET et POST
  
#### Differéntes Méthodes:
	 - La méthode GET envoie les données via l'URL sous forme de paramètres de requête.  
   	 - La méthode POST passe les paramètres dans le corps de la requête.


# 2 – Comparaison méthodes

 | Methode         | Visibilité des données | Sécurité | longueur de données | Cache et fichier log du serveur |
| :--------------- |:---------------:| :----------:| :---------:| :---------:| 
|   `GET`              |   `Visible dans l'URL`    |  `Moins sécurisé (données dans l'URL)`   | `Limitée - longueur maximale de l’URL à 2 048 caractères`   | `Les paramètres de l’URL sont stockés sans chiffrement`   |
|  `Post`              | `Caché dans le corps de la requête`   |   `Plus sécurisé (données dans le corps)`   | `Illimitée`   | `Les paramètres de l’URL ne sont pas enregistrés automatiquement`   |


https://www.ionos.fr/digitalguide/sites-internet/developpement-web/get-vs-post/

# 3 -Extensible


	## Le protocole HTTP est extensible grâce à sa structure basée sur des en-têtes, les en-têtes permettent d'ajouter des fonctionnalités et des informations supplémentaires sans modifier le protocole de base
	
# 4 - Sans état

	## HTTP est qualifié de protocole sans état car chaque requête est indépendante et le serveur ne conserve aucune information d'une requête à l'autre, ce qui nécessite l'utilisation de cookies pour maintenir la continuité de la navigation

# 5 – URL

	## Le protocole HTTP est extensible grâce à sa structure basée sur des en-têtes, les en-têtes permettent d'ajouter des fonctionnalités et des informations supplémentaires sans modifier le protocole de base

# 6 - Codes Status
     
	 ## 1xx -Informational : Le serveur a reçu la requête et continue à la traiter
			Exemple: 100 Continue ---> Le client peut continuer à envoyer le reste de la requête.
			
	 ## 2xx -Success : La requête a été reçue, comprise et acceptée avec succès
			Exemple: 200 OK---> La requete a réussi et le serveur retourne la ressource demandée
			
	 ## 3xx -Redirection : Le client doit effectuer une action supplémentaires pour completer la requête
			Exemple: 301 Moved Permanently---> La ressource demandée a été déplacée de façcon permanente vers une nouvelle URL
			
	 ## 4xx -Client error : La requête contient une erreur ou ne peut pas répondre
			Exemple: 404 Not Found---> Le serveur ne trouve pas la ressource demandée
			
	 ## 5xx -Server error: Le serveur a rencontré une erreur ou ne peut pas répondre
			Exemple: 500 Internal Server Error---> Le serveur a rencontré une condition inattendue qui l'empêche de répondre à la requete
			
# 7 – Négociation de contenu
	## La négocition de contenu HTTP est un processus ou le client, comme un navigateur web envoie une requête au serveur en précisant ses préférences pour le type de contenue qu'il veut reçevoir. Le serveur choisi ces ressources pour envoyer la meilleur version de la ressource qui correspond le mieux au client.






# 10 – Headers

| **En-tête HTTP**      | **Rôle**                                                                                         | **Exemple**                              |
|-----------------------|--------------------------------------------------------------------------------------------------|------------------------------------------|
| `Host`                | Indique le nom de domaine du serveur auquel la requête est envoyée.                               | `Host: www.example.com`                  |
| `User-Agent`          | Identifie le client qui fait la requête (navigateur, application).                                | `User-Agent: Mozilla/5.0`                |
| `Accept`              | Spécifie les formats de contenu que le client peut traiter.                                       | `Accept: text/html, application/json`    |
| `Authorization`       | Contient les informations d'authentification pour accéder à une ressource protégée.               | `Authorization: Basic dXNlcjpwYXNz`      |
| `Content-Type`        | Indique le type de contenu envoyé au serveur (pour les requêtes POST/PUT).                        | `Content-Type: application/json`         |
| `Cookie`              | Envoie les cookies stockés sur le client au serveur.                                              | `Cookie: sessionId=abc123`               |
| `Referer`             | Indique l'URL de la page qui a conduit le client à faire cette requête.                           | `Referer: https://www.google.com/`       |

http://dev.local
