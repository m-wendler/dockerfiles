## A tiny **wget** setup

based on alpine. The complete image is just over 6 MB big ...

Run a container from this image like:

    docker run --rm mwendler/wget

which should display the wget's usage:

    wget: missing URL
    Usage: wget [OPTION]... [URL]...

    Try `wget --help' for more options.

To use wget like a locally installed version you can create an alias like:

    alias wget='docker run --rm mwendler/wget'

and then use wget from the command line:

    wget -S --no-check-certificate https://letsencrypt.org


Have fun!
