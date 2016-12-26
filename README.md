# Codeminer42 Elixir Images for CI builds

Docker Elixir images used by Gitlab CI.

## Dependencies

The following dependencies are being installed on all images:

* Node.js v4.4.7 and npm
* PhantomJS v1.9.8

## Tags

We currently have images for the following versions:

- `1.3`, `latest` [Dockerfile](https://github.com/Codeminer42/docker-ci-elixir/blob/master/1.3/Dockerfile)

## Contributing

`Dockerfiles` are stored under folders for each version.

For updating the images, just open a _pull request_ with
the new `Dockerfile` version and, after accepted, Docker
Hub will build automatically after a few minutes.

The images should setup an environment that is widely used,
please don't install dependencies that are specific to a
project. It's also good to have a pattern and all images
support the same things.
