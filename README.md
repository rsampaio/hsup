# hsup

Queries the Heroku API, downloads environment variables, and then runs
a process with arguments.

Usage:

    HEROKU_ACCESS_TOKEN=... hsup [app] [executable] [args ...]

Example:

    export DOCKER_HOST=unix:///var/run/docker.sock
    export HEROKU_ACCESS_TOKEN=...
    hsup www bin/web -p $PORT