"# API-FOOTBALL-TOGO" 
# API REST
Auteur: AFO ABDEL FADIL
Tâche : Simplo
Campus: Energy Generation
Coach: Malick Bah

CONTEXTE
    La Fédération Togolaise de Football a lancé un appel d'offre publique pour la digitalisation de son système de gestion des statistiques des joueurs. La solution conçue devra répondre aux exigences listées dans les critères de performance ci-dessous pour prétendre à gagner le marché.

LIEN DEPLOIEMENT
    + https://afternoon-mountain-45400.herokuapp.com/

PERFORMANCE
    L'API passe les tests suivants sur PostMan:
    GET:

    - Si l'entrée est trouvée, l'API retourne les statistiques en format en format JSON.
    Si l'entrée n'est pas trouvée, l'API retourne un message d'erreur avec le status code approprié (404)
    POST:

    - La nouvelle entrée est bien créée
    L'API affiche le status code 201 après réussite de l'opération.
    PUT:

    - Si la mise à jour est réussie, l'API affiche le status code 200.
    Si l'entrée n'est pas trouvée, l'API retourne un message d'erreur avec le status code approprié (404)
    DELETE:

    - L'entrée ciblée est bien supprimée
    Si l'entrée n'est pas trouvée, l'API retourne un message d'erreur avec le status code approprié (404)
    Le back-end reste fonctionnel.
