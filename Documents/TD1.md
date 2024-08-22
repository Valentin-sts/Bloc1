# Bloc1

 # Différences entre les méthodes HTTP GET et POST
  
    ## Differéntes Méthodes:
	 - La méthode GET envoie les données via l'URL sous forme de paramètres de requête.
   	 - La méthode POST passe les paramètres dans le corps de la requête.




 | Methode         | Visibilité des données | Sécurité | longueur de données | Cache et fichier log du serveur |
| :--------------- |:---------------:| :----------:| :---------:| :---------:| 
| GET              |   Visible dans l'URL   |  Moins sécurisé (données dans l'URL) | Limitée - longueur maximale de l’URL à 2 048 caractères. | Les paramètres de l’URL sont stockés sans chiffrement |
|Post              | Caché dans le corps de la requête |   Plus sécurisé (données dans le corps) | Illimitée. | Les paramètres de l’URL ne sont pas enregistrés automatiquement. |


https://www.ionos.fr/digitalguide/sites-internet/developpement-web/get-vs-post/
