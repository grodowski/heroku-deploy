# heroku-deploy

A Dockerfile that we use to deploy stuff to Heroku with.

### Configuration

Expose heroku credentials to the container via: `HEROKU_LOGIN` and `HEROKU_API_KEY` variables (set in CircleCI's UI or `config.yml`)
