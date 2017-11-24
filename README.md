# Supercronic Heroku Buildpack

A simple buildpack to install supercronic as a cron daemon.

## Variables

* `SUPERCRONIC_VERSION` supercronic version number, default: `v0.1.4`
* `SUPERCRONIC` supercronic bin filename, default: `supercronic-linux-amd64`
* `SUPERCRONIC_URL` URL to download supercronic from, default: `https://github.com/aptible/supercronic/releases/download/$SUPERCRONIC_VERSION/$SUPERCRONIC`
* `SUPERCRONIC_SHA1SUM` sha1sum for supercronic bin file, default: `3a631023f9f9dd155cfa0d1bb517a063d375055a`