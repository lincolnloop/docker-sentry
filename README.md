# Sentry on Docker

Setup to use Postgres as a database. Environment variables are used for configuration with the default conf file produced by `sentry init`.

## Required Environment Variables

* `DATABASE_URL`
* `EMAIL_URL`
* `REDIS_STORAGE_URL`
* `SENTRY_URL_PREFIX`
* `SECRET_KEY`

## Optional Environment Variables

* `REDIS_BROKER_URL`
* `SERVER_EMAIL`

