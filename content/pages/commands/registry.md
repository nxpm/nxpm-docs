---
title: nxpm registry
date: Last Modified
permalink: /commands/registry/index.html
eleventyNavigation:
    key: Registry
    order: 7
    parent: Commands
    title: Registry
---

The `registry` command helps you run a local npm registry and configure `npm` and `yarn` to use it.
This can be very useful if you are developing packages and don't want to pollute the official npm registry.

It works by executing the command `npx verdaccio`. If it's not installed globally, `npx` will handle that for you. If you want to speed up this process, make sure to install `verdaccio` globally.

## Start a local registry

```shell script
nxpm registry:start
```

```
NXPM  RUNNING npx verdaccio
warn --- config file  - ~/.config/verdaccio/config.yaml
warn --- Verdaccio started
warn --- Plugin successfully loaded: verdaccio-htpasswd
warn --- Plugin successfully loaded: verdaccio-audit
warn --- http address - http://localhost:4873/ - verdaccio/4.5.1
```

## Configure npm and yarn

Configure npm and yarn to use the local registry

```shell script
nxpm registry:enable
```
