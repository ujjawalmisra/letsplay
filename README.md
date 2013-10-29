# letsplay

Lightweight wrapper for building and managing play! framework projects. It aims at simplifying running of play! framework projects.

## License

Copyright (c) 2013 Ujjawal Misra. See the LICENSE file for license rights and limitations (MIT).


## Configuring projects

Create a file **$HOME/.letsplay.config**. This file should contain the configuration of projects to be run using letsplay.
A sample configuration in this file will be like:

    services=/usr/local/play-2.1.0;dev;9001

You can refer the sample config file *sample.letsplay.config* to understand the configuration better.


## Starting services

First prepare (compile) the code:

    ./letsplay services prepare

Now start:

    ./letsplay services start

You can check project status:

    ./letsplay services status

You can stop the project:

    ./letsplay services stop

