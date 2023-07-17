# S06 - QCM5

Les étapes d'un controller : 
- ❌ // 1. Rediriger la requête vers la bonne méthode // 2. Query la BDD => `router`
- ✅ // 1. Parse & Validate inputs // 2. Fetch data // 3. Return responses
- ❌ // 1. Vérifier la présence du ticket RATP. // 2. Mettre l'amende appropriée en cas de fraude


Je suis Bob de l'équipe Frontend, et notre code client appelle l'API d'Alice, qui me retourne une `401`:
- ✅ c'est probablement la faute de l'équipe Frontend !
- ❌ c'est probablement la faute de l'équipe Backend !
- ❌ c'est probablement la faute des reptiliens

401 = unauthorized
`4XX = erreur client` = le client a mal appelé l'API. 
C'est la faute de l'équipe CLIENT s'ils appellent l'API d'Alice sans s'authentifier. Il faut qu'ils s'authentifient ! 
`5XX = erreur backend`. 


Insomnia est :
- ❌ une API web => le backend de okanban c'est la web api
- ✅ un client HTTP => client pour contacter une web api 
- ❌ un serveur HTTP => le backend de okanban c'est un serveur HTTP
- un cauchemar pour dormir la nuit 😪


