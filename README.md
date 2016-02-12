﻿Barista-Cli
=========

The Barista command line utility makes it easy to start and install Barista services as well as to execute individual Barista scripts.

Use the `barista --help` command for more detailed task information.

## Installing

```bash
$ npm install -g barista-framework
```

*Note: For a global install of `-g barista-framework`, OSX/Linux users may need to prefix the command with `sudo` or can setup [proper file permissions on OSX for npm](http://www.johnpapa.net/how-to-use-npm-global-without-sudo-on-osx/) to install without `sudo`. *


## Starting the Barista Service

```bash
$ barista start
```

## Installing Barista as a system service

```bash
$ barista install [service name]
```

## Uninstalling Barista as a system service

```bash
$ barista uninstall [service name]
```

## Running an individual barista script

```bash
$ barista run [path]
```

__Command-line flags/options:__

    [--port|-p] .............  Server HTTP port (8000 default)