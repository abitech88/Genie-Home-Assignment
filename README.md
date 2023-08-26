## Installation
```bash
yarn install
```
## Run the app
- If you need update the environment, please change .env file.
- Start the postgres db by running docker compose up -d
- Start the application

### Watch mode
```bash
yarn run dev
```

### Production mode
```bash
yarn run start:prod
```
- Visit <http://localhost:8000/seed> to seed contents into the database.
- Visit the graphql endpoint on <http://localhost:8000/api/graphql>

#### Start the db
```bash
docker compose up -d 
```
#### Start the app
```bash
yarn dev 
```
Make a GET request to `localhost:8000/seed` to seed contents into the database.






