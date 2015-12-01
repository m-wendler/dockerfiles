
# A minimalist [packer](https://www.packer.io/) setup

based on alpine. The complete image is ~ 500 MB big and contains the *COMPLETE* packer installation.

Run a container from this image like:

    docker run --rm -v `pwd`:/data mwendler/packer packer -v

which should display the installed packer version:

    0.8.6

To make packer usable like a locally installed version you can create an alias like:

    alias packer='docker run --rm -v `pwd`:/data mwendler/packer packer'

and then use packer from the command line:

    packer -v

Have fun!
