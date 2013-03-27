mojito-cli [![Build Status](https://travis-ci.org/isao/mojito-cli.png)](https://travis-ci.org/isao/mojito-cli)
==========

`mojito-cli` is a command line tool for [Mojito](https://github.com/yahoo/mojito) developers. `mojito` components that are unrelated to the core library and runtime will be moving to separate packages.


Install mojito-cli
------------------

With [npm](http://npmjs.org/), do

    npm install --global mojito-cli

Try it

    mojito help

Note that if `mojito` was already installed globally, it will be uninstalled. It is recommended to only install the core `mojito` package as a local dependency in your mojito application. Users should not have any loss of functionality.

Quickstart
----------

Create an app (which installs `mojito` locally using npm) and a mojit.

    mojito create app myapp
    cd myapp
    mojito create mojito hellomojit

Start the server

    mojito start

In a browser, open

    http://localhost:8666/@hellomojit/index

Commands
--------

### help

To show top-level help for this command line tool:

    % mojito help

To show help for a specific command:

    $ mojito help <command>



Discussion/Forums
-----------------

http://developer.yahoo.com/forum/Yahoo-Mojito

Licensing and Contributions
---------------------------

`mojito-cli` is licensed under a BSD license (see LICENSE.txt). To contribute to the Mojito project, please see [Contributing](https://github.com/yahoo/mojito/wiki/Contributing-Code-to-Mojito). 

The Mojito project is a [meritocratic, consensus-based community project](https://github.com/yahoo/mojito/wiki/Governance-Model) which allows anyone to contribute and gain additional responsibilities.
