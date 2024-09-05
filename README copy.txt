





	

	#testimonials {
		padding: 4em 0; /* Plus de padding pour mieux respirer */
		text-align: center;
		background-color: #2E3142 /*  linear-gradient(135deg, #1a1a1a 0%, #2c2c2c 50%, #1a1a1a 100%);; /* Harmonisation avec le fond de la section précédente */
		color: #ffffff; /* Texte blanc pour contraster avec le fond sombre */
	}
	


	.carousel-slide {
		display: flex;
		transition: transform 0.5s ease-in-out;
		margin: 0;
		padding: 0;
		min-height: 200px;
		width: 100%; /* Chaque témoignage occupe 100% du conteneur */
	}
	
	.testimonial {
		min-width: 100%;
		box-sizing: border-box;
		padding: 30px;
		background: #2E3142; /* Couleur de fond plus claire pour s'harmoniser avec le reste */
		box-shadow: 0 4px 8px rgba(0,0,0,0.3); /* Ombre subtile pour créer de la profondeur */
		border-radius: 8px; /* Angle des coins cohérent avec les autres sections */
		margin: 20px 0;
	}
	
	.testimonial h4 {
		margin-top: 15px;
		font-style: normal; /* Aligné avec les titres sur le reste du site */
		color: #f39c12; /* Utilisation d'une couleur accent pour le nom du client */
		font-size: 1.2em; /* Taille cohérente avec les autres titres */
		text-align: center;
		text-transform: none;
		font-weight: 550; /* Légère augmentation du poids pour une meilleure lisibilité */
	}
	
	.testimonial p {
		font-style: normal; /* Retrait de l'italique pour s'harmoniser avec le reste du texte */
		font-size: 1.1em;
		color: #cccccc; /* Texte plus clair pour un bon contraste sur le fond */
		margin-bottom: 15px;
		line-height: 1.6; /* Espacement des lignes pour améliorer la lisibilité */
	}
	
	.testimonial::before, .testimonial::after {
		font-size: 2em; /* Réduction de la taille des guillemets pour qu'ils ne dominent pas le texte */
		color: #f39c12; /* Maintien de la couleur accent */
	}
	

	/* Arrière-plan du carousel */
	.carousel-container {
		background-color: transparent; /* Couleur de fond complémentaire */
		padding: 20px; /* Ajoute du padding tout autour du carousel */
		border-radius: 10px; /* Coins arrondis */
		margin-top: 0 !important; /* Forcer la marge à 0 en haut */
		padding-top: 0 !important;
		margin-bottom: 0 !important; /* Forcer la marge à 0 en bas */
		padding-bottom: 0 !important;
		
		margin: 0 auto; /* Centre le carousel horizontalement */
		position: relative; /* Nécessaire pour le positionnement des éléments internes */
		
		max-width: 1000px; /* Largeur maximale du carousel */
    	overflow: hidden; /* Cache les extrémités des témoignages voisins */
	}
	

	
	.testimonial {
		background-color: #4C5C68; /* Couleur de fond, ici en gris clair */
		color: #C9CCD0; /* Couleur du texte (assure-toi que le contraste est bon) */
		padding: 15px;
		border-radius: 10px; /* Ajoute des coins arrondis si souhaité */
		box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Ajoute une ombre pour plus de style */
		font-style: italic;
		text-align: center; /* Centrer le texte */
   	 	display: flex;
    	flex-direction: column; /* S'assurer que les éléments s'alignent en colonne */
    	justify-content: center; /* Centrer verticalement */
    	align-items: center; /* Centrer horizontalement */
    	height: 100%; /* S'assurer que les éléments occupent toute la hauteur si nécessaire */
		min-width: 100%; /* Chaque témoignage prend 100% de la largeur */

		flex: 0 0 100%; /* Chaque témoignage prend exactement 100% de la largeur du carousel */
		margin: 0; /* Supprime les marges entre les témoignages */
	}
	
	
	
	/* Ajouter des effets pour la transition du carousel */

	
	.testimonial h4 {
		color: #F39C12; /* Couleur complémentaire pour le nom */
		font-weight: bold;
	}
	
	.wrapper .spotlight .image {
		max-width: 100%; /* Assure-toi que l'image prend la largeur correcte */
		border-radius: 10px; /* Pour ajouter des coins arrondis, si souhaité */
		display: block;
	}
	
	.wrapper .spotlight .content {
		flex: 1;
		padding: 20px; /* Ajuster le padding si nécessaire */
	}



