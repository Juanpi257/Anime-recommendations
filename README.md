# Anime-recommendations
Anime recommendations based on a dataset where users rate the anime
# This dataset is named anime
The dataset contains a set of 12,294 records under 7 attributes:
| Column Name | Description|
| --- | --- |
| Anime_id: | Myanimelist.net's unique id identifying an anime. |
| Name: | Full name of anime. |
| Genre: | Comma separated list of genres for this anime. |
| Type: |	Movie, TV, OVA, etc. |
| Episodes: | How many episodes in this show. (1 if movie). |
| Rating: |	Average rating out of 10 for this anime. |
| Members: | Number of community members that are in this anime's "group". |

# This dataset is named rating
The dataset contains a set of 7,813,737 records under 3 attributes:
|Column Name | Description|
| --- | --- |
| User_id: | Non identifiable randomly generated user id. |
| Anime_id: |	The anime that this user has rated. |
| Rating: |	Rating out of 10 this user has assigned (-1 if the user watched without assigning) |

