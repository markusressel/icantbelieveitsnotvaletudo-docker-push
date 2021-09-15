# icantbelieveitsnotvaletudo-docker-push

A simple repo to build and push an up-to-date docker image of [ICantBelieveItsNotValetudo](https://github.com/Hypfer/ICantBelieveItsNotValetudo)

## Modifications

To make this image work with mounted configuration files, the persistence is removed from the Configuration.js using [a simple sed command](https://github.com/markusressel/icantbelieveitsnotvaletudo-docker-push/blob/19acdf018af14ea173fc9458a0b2433b89ad8436/.github/workflows/dockerx-latest.yml#L26).

Other than that the source from the official repo is not modified in any way.

## Builds

The Github Action setup in this repo builds new containers on a regular basis.
You can have a look at the schedule [here](https://github.com/markusressel/icantbelieveitsnotvaletudo-docker-push/blob/19acdf018af14ea173fc9458a0b2433b89ad8436/.github/workflows/dockerx-latest.yml#L6)
