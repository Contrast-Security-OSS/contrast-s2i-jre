# Contrast Security Openshift s2i Runtime Image

This is an example of how you can inject the Contrast Security Java Agent into your Dockerized application and launch it on Redhat Openshift.

For information on this particular bit of technology, read about s2i runtime images here: https://github.com/openshift/source-to-image/blob/master/docs/runtime_image.md

## Usage

Inject into your s2i image with `--runtime-image=contrast/contrast-s2i-jre` in your `s2i build` command.

## On Docker Hub

https://hub.docker.com/r/contrast/contrast-s2i-jre

## Development

* (Make changes)
* `docker build . -t contrast/contrast-s2i-jre:latest`
* `docker push contrast/contrast-s2i-jre:latest`
