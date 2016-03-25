# A minimal [*figlet*](http://www.figlet.org) setup

based on [alpine](https://hub.docker.com/_/alpine/). The complete image is just over 6 MB big ...

Run a container from this image like:

    docker run --rm mwendler/figlet hello figlet

which should display:

```
 _          _ _          __ _       _      _
| |__   ___| | | ___    / _(_) __ _| | ___| |_
| '_ \ / _ \ | |/ _ \  | |_| |/ _` | |/ _ \ __|
| | | |  __/ | | (_) | |  _| | (_| | |  __/ |_
|_| |_|\___|_|_|\___/  |_| |_|\__, |_|\___|\__|
                         |___/
```

### Use *figlet* like a locally installed version

* Create an alias like:

    ```alias figlet='docker run --rm mwendler/figlet'```

* use it from the command line, e.g.:

 ```figlet yeah figlet on docker```


Have fun!
