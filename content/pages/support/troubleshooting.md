---
title: Troubleshooting
date: Last Modified
permalink: /support/troubleshooting/index.html
eleventyNavigation:
    key: Troubleshooting
    order: 13
    parent: Support
    title: Releasing packages
---
### ERROR No upstream configured for current branch.

This is because you did not yet push to your remote.

Commit your changes, push to your remote and try again.

```shell script
ERROR No upstream configured for current branch.
Please set an upstream branch.
Alternatively, use `--no-git.requireUpstream` to have this set this by release-it (or save `"git.requireUpstream": false` in the configuration).
 NXPM   ERROR  No upstream configured for current branch.
Please set an upstream branch.
Alternatively, use `--no-git.requireUpstream` to have this set this by release-it (or save `"git.requireUpstream": false` in the configuration).
 NXPM   ERROR  Something went wrong running 'release-it' :(
```
