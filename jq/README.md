# A minimal [jq](https://stedolan.github.io/jq/) setup

based on [alpine](https://hub.docker.com/_/alpine/). The complete image is just over 10 MB big ...

Run a container from this image like:

    docker run -i --rm mwendler/jq

which should display the installed jq version:

    jq-1.5

### Use `jq` like a locally installed version

* Create an alias like:

    alias jq='docker run -i --rm mwendler/jq'

* use it from the command line, e.g.:

    curl 'https://api.github.com/repos/m-wendler/dockerfiles/commits' | jq -C .[0]


Have fun!
