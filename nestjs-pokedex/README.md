# nestjs-pokedex

A NestJS CRUD application for Pokémon.

- Fetches Pokémon data from an external API
- Saves and manages Pokémon data in the database

<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Running in Development

1. Clone the repository
2. Install dependencies

```
npm install
```

3. Make sure you have the Nest CLI installed

```
npm i -g @nestjs/cli
```

4. Start the database

```
docker-compose up -d
```

5. Copy the file __.env.example__ and rename the copy to __.env__

6. Fill in the environment variables defined in the __.env__ file

7. Run the application in development mode:

```
npm run start:dev
```

8. Seed the database by visiting:

```
http://localhost:3000/api/v2/seed
```

## Stack Used

* MongoDB
* NestJS
