# A minimal [jq](https://stedolan.github.io/jq/) setup

based on alpine. The complete image is just over 10 MB big ...

Run a container from this image like:

    docker run --rm mwendler/jq

which should display the installed jq version:

    jq-1.5

To use `jq` like a locally installed version you can create an alias like:

    alias jq='docker run -i --rm mwendler/jq'

and then use it from the command line:

    curl 'https://api.github.com/repos/stedolan/jq/commits' | jq -C .[0]


Have fun!
