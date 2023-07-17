# S06 - QCM4

Quelle information est vraie ?
- insérer 'coucou' dans un VARCHAR(7) lève une erreur.
- insérer 'coucou' dans un VARCHAR lève une erreur.
- le type VARCHAR(42) accepte uniquement les chaines de caractère qui font exactement 42 caractères. 
- elles sont toutes vraies
- elles sont toutes fausses


Une clé primaire composite est une clé primaire : 
- basée sur plusieurs tables
- basée sur plusieurs champs d'une table
- qui mute selon l'état de la base de données


`GET`, `POST`, `PUT`, `PATCH`... c'est quoi ? 
- le chemin (🇬🇧 path) de la requête HTTP
- le verbe (🇬🇧 method) de la requête HTTP
- l'hôte (🇬🇧 host) de la requête HTTP


Imaginons une API REST. Pour mettre à jour la `date de naissance` de l'étudiant `étudiant` n°42, j'aurais tendance à utiliser la route : 
- `GET /students/42` avec un body `{ "birthdate": "1970-01-01" }`
- `PATCH /students/42` avec un body `{ "birthdate": "1970-01-01" }`
- `PATCH /students/42/updateBirthDate/1970-01-01`

