# Anime-recommendations
Anime recommendations based on a dataset where users rate the anime
# This dataset is named anime
The dataset contains a set of 12,294 records under 7 attributes:
Column Name	    Description
anime_id:	      myanimelist.net's unique id identifying an anime.
name:	          full name of anime.
genre:	        comma separated list of genres for this anime.
type:	          movie, TV, OVA, etc.
episodes:	      how many episodes in this show. (1 if movie).
rating:	        average rating out of 10 for this anime.
members:	      number of community members that are in this anime's "group".
# This dataset is named rating
The dataset contains a set of 7,813,737 records under 3 attributes:
Column Name	    Description
user_id:	      non identifiable randomly generated user id.
anime_id:	      the anime that this user has rated.
rating:	        rating out of 10 this user has assigned (-1 if the user watched without assigning)

