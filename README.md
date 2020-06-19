# A [Giter8][g8]/[docker-compose][docker-compose]/[postgres][postgres] template

A Giter8 template for creating a docker-compose file which creates a postgres database. The template is super beginner friendly. It generates a lot of docker-compose helper scripts so zero docker or docker-compose knowledge is required. It even includes install scripts for both docker and docker-compose. The template was **only** tested in Ubuntu.

```bash
sbt new devinsideyou/docker-compose-postgres.g8
```

or

```bash
g8 devinsideyou/docker-compose-postgres
```

After running one these take a look at the `seed.sql` file, `./create` your container which will run the postgres server and connect to it via the `./client`.

[g8]: http://www.foundweekends.org/giter8/
[docker-compose]: https://docs.docker.com/compose/
[postgres]: https://hub.docker.com/_/postgres
