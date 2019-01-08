# Base Docker Environment for Runing Laravel.

A basic docker-compose configuration to run a Laravel application.

### Prerequisites

In your Laravel applications .env file, ensure that DB_HOST is set to the database service that you're using, e.g. `DB_HOST=mysql`.

### Quickstart

Copy docker-compose.yml into the root of your project directory and run:

```
$ docker-compose up -d
```

Then visit: http://localhost/
