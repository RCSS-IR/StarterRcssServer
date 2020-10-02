# StarterRcssServer
How to install Starter rcssserver

#### Install last released version of rcssserver
[Download](https://github.com/rcsoccersim/rcssserver/releases/tag/rcssserver-16.0.0) and [Install](https://github.com/rcsoccersim/rcssserver)

#### Make install the rcssserver
```$sudo make install```

#### Run rcssserver in your terminal and terminate it using Ctrl+c
```$rcssserver```

* if you can not run the server, ```sudo ldconfig``` may help you!

#### Open rcssserver's configuration to change it to Starter configuration
```$gedit ~/.rcssserver/server.conf```

#### Change value of these parameters
| Parameters        | Old Value           | New Value  |
| ------------- |:-------------:| -----:|
| server::fullstate_l      | false | true |
| server::fullstate_r      | false      |   true |
| server::stamina_capacity | 130600      |    150000 |
| server::stamina_max | 8000 | 10000 |
|server::hear_max|1|11|
