# PostgreSQL

PostgreSQL database docker image. Derived from [the Docker official image for postgres](https://github.com/docker-library/docs/tree/master/postgres).

## Environment Variables

- `APP_POSTGRES_DB`: name of your app's database. The default is "app".
- `APP_POSTGRES_DB_USER`: owner of your app's database. The default is the same as the name of your database.
- `APP_POSTGRES_DB_PASSWORD`: password of owner of your app's database. The default is the same as the name of the owner.
