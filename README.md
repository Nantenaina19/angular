Playlist de type youtube, avec player video en mean
============================

> Structure du projet

### Dossiers du répertoire


	.
    ├── config                  # Connexion à la base de données mongoDB
    ├── models                  # Structure de chaque table dans la base données
    ├── routes                  # Répertoire qui contient les api	
    ├── public                  # Répertoire qui contient les.html et assets
    ├── public/js/
		├── controllers             # Listes des controllers
    │   ├── services        	  # Service
    │   └── ...            		  # 
    └── ...
	
### Liste des pages html

	Public
    ├── index.html              # Liste des musiques trié par genre de musique 
    ├── musicgenre.html         # Liste des musiques selon un genre choisi
    ├── details.html            # Détails d'une musique choisi
    ├── genres.html				      # Liste des genres de musique
	  ├── resultat.html		        # Résultat d'une recherche
    ├── connexion.html          # 
    ├── inscription.html		    #
    ├── playlist.html			      # Liste des playlists de l'utilisateur connecté
    ├── videos.html        	  	# Liste des vidéos publiés par l'utilisateur connect
	  ├── upload.html        		  # Uploader un nouveau morceau         		 
    └── profil.html
	
	
