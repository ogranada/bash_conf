Bash Conf
=========
Bash Terminal configuration (optimized for debian based distros).

# Features
* Auto completion
* Different bash configurations for Linux, OSX, Cygwin(Msys)
* Easy alias management
* Magic prompt (Works with git)
* pip cache enabled

## Auto completion
When you use tab key it complete many instructions.
Ej.
On 

```
git sta[TAB]
```
It show
```
stage    stash    status
```

## Alias Management
You can add a persistent alias with addalias:

```
addalias lsl ls\ -l # equivalent to alias lsl="ls -l"
```

#### Note:
If your alais instruction have spaces put \ character after.

You can remove remove alias with rmalias:

```
rmalias lsl # equivalent to unalias lsl
```

#### Note:
rmalias support completion

TODO
====
- ~~easy alias management~~
- ~~*nix based terminals compatibility~~
- easy install
