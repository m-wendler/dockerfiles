# A *fortune* setup

based on debian:wheezy. ([![](https://badge.imagelayers.io/mwendler/fortune:latest.svg)](https://imagelayers.io/?images=mwendler/fortune:latest 'Get your own badge on imagelayers.io'))

Run a container from this image like:

    docker run --rm mwendler/fortune

which should display a fortune like:

```
Stay away from hurricanes for a while.
```

### Use *fortune* like a locally installed version

* Create an alias like:

    ```alias fortune='docker run --rm mwendler/fortune'```

* use it from the command line, e.g.:

 ```fortune```


Have fun!
