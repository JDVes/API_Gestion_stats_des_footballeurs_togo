# API_Gestion_stats_des_footballeurs_togo
Création d'un API REST pour la gestion des statistiques des joueurs de foot de l'équipe nationale du Togo.

l'objectif de la creation d'un API REST pour la gestion des statistiques des jouers de l'equipe du togo va dans la logique de l'evaluation de la performance de chaques joueurs sur le terrain en vu en vu d'avoir un oeil regardant sur la  constances de leurs  performances lors d chaque matchs. Critere determinant dans le choix des joueurs le mieux en forme pour les matchs a discuter. 

aINSI POUR AVOIR Aa disposition de maniere reguliere les statistique de ces joueurs on procedera a l'utilisation d'un certain nombres de methode de collecte d'aalyse et de ;ise a jour de donner neccessaire aux entraneurs pour un suivi optimal.

Nous anrons donc les ;etodes suivantes:  

Methode GET:
Au travers de cette methode  l'API retourne les statistiques de chaque joueurs  pour chaque entrée.
Si l'entrée n'est pas trouvée, l'API retourne un message d'erreur avec le status code approprié (404)

Methode POST:

Au travers de cette methode  l'API créée les entrée correspondant a un nouveau joueur qui va disposer d'un profil ce aui permettra son suivi et l'obtention de ses statistiaues . lorsque La nouvelle entrée est bien 
L'API affiche le status code 201 après réussite de l'opération.

Methode PUT:

Au travers de cette methode  l'API procede a la mise a jour des statistique de chaque joueurs et Si la mise à jour est réussie, l'API affiche le status code 200.
Si l'entrée n'est pas trouvée, l'API retourne un message d'erreur avec le status code approprié (404)

Methode DELETE:

Au travers de cette methode  l'API  procede a la suppression d'une entrée ciblée et
Si l'entrée n'est pas trouvée, l'API retourne un message d'erreur avec le status code approprié (404)
Le back-end reste fonctionnel.


Cet API est publique et disponible pour toutes utilisation professonnel et a des fin argumentaire.


1/ lIEN repo github : https://github.com/JDVes/API_Gestion_stats_des_footballeurs_togo.git
2/ lien de deploiement sur Heroku :
https://api-togo-footballer-stats.herokuapp.com/

