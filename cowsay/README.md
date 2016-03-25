# A *cowsay* setup

based on debian:wheezy.

Run a container from this image like:

    docker run --rm mwendler/cowsay hello

which should display:

```
_______
< hello >
-------
       \   ^__^
        \  (oo)\_______
           (__)\       )\/\
               ||----w |
               ||     ||
```

### Use *cowsay* like a locally installed version

* Create an alias like:

    ```alias cowsay='docker run --rm mwendler/cowsay'```

* use it from the command line, e.g.:

 ```cowsay hello```


Have fun!
