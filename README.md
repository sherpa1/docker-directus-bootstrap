# Directus + Postgres + Redis in Docker

## Installation initiale

- Créer un fichier ./db/.env basé sur le fichier d'exemple
- Créer un fichier ./directus/.env basé sur le fichier d'exemple
- Commencer par initialiser la base de données Postgres : `docker compose up database`
- Lorsque la base de données a fini son initialisation (cf. message de log _"LOG:  database system is ready to accept connections"_), stopper les services (ctrl + c)
- Initialiser l'ensemble des services : `docker compose up`
- Attendre que Directus termine son initialisation (cf. message de log _"INFO (...): Server started at http://0.0.0.0:8055"_)

## Accès

- Back Office : http://0.0.0.0:8055
- API : 

## Documentation

### Image Docker Directus
https://hub.docker.com/r/directus/directus

### Directus
https://docs.directus.io/

---
Alexandre Leroux

_Enseignant / Formateur_<br>
_Développeur logiciel web & mobile_

Nancy (Grand Est, France)

https://sherpa.one
