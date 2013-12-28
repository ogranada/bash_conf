bash_conf
=========
Bash Terminal configuration (optimized for debian based distros).

Features
--------
* Auto completion
* Easy alias management
* Magic prompt (Works with git)
* pip cache enabled

Alias Management
================
You can add a persistent alias with addalias:

```bash 
addalias lsl ls\ -l # equivalent to alias lsl="ls -l"
```

Note:
-----
If your alais instruction have spaces put \ character after.

You can remove remove alias with rmalias:

```bash 
rmalias lsl # equivalent to unalias lsl
```

Note:
-----
rmalias support completion

TODO
====
- [X] easy alias management
- [ ] easy intall
- [ ] auto folder creation
- [ ] *nix based OS compatibility



