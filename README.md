### dockerfile-apache-php

Docker image with Apache and PHP7

### Branches for different Docker image tags

The `master` branch is always associated to the `latest` tag of the Docker image.

This repository also comes with different feature branches for different Docker image tags.

For example, the branch: `feature/php71` is associated with the tag `php7.1`.


### Build

> docker build -t ludovicvalente/apache-php -f ./Dockerfile .
> docker login -u "ludovicvalente" docker.io
> docker image push ludovicvalente/apache-php