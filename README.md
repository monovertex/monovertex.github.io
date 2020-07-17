# monovertex.github.io

Contains the Jekyll blog visible at https://monovertex.github.io.

## Development

In order to run and develop the blog locally, you need to install [Docker](https://www.docker.com/).

The commands needed to interact with the blog app:
- Building & serving: `docker-compose up`.
- Updating: `docker run --rm --volume="$PWD:/srv/jekyll" -it jekyll/jekyll:3.8 bundle update`.
