# Building gstreamer modules with jhbuild

## Prerequisites

* jhbuild (>= 3.5)
* git
* patience

### In Ubuntu (>= 14.04)

- Ubuntu already has a package for jhbuild.
```
$ sudo apt-get install jhbuild
```

*Note*: official jhbuild package (>= 3.5) has shipped after ubuntu 14.04.

### In Debian

- Even latest version(jessie - 8) of debian, the version of jhbuild is very low. 
  Just follow the instruction "From scratch".

### From scratch

- Installing [jhbuild](https://developer.gnome.org/jhbuild/stable/getting-started.html.en#getting-started-install)
(Note that section 2.1 is all you need and you don't need to run remains)

## Build & Run

- Run 'jg build' to build latest gstreamer
- Run 'jg shell' to have latest gstreamer environment

### Gstreamer shell mark

Run 'setup-prompt.sh' to add jg shell indicator to your shell prompt.

# Credit

This project is forked from https://github.com/arkadini/jhbuild-gstreamer
