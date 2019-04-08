# Bash

Run as `root` in this directory:

```
ln -s $(pwd)/bash.* /private/etc/
```

Add at the bottom of `/private/etc/bashrc`

```
[ -r "/etc/bash.aliases" ] && . "/etc/bash.aliases"

[ -r "/etc/bash.functions" ] && . "/etc/bash.functions"
```
