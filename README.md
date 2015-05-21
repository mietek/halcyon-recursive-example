_halcyon-recursive-example_
===========================

Example Haskell program, showing how to declare _alex,_ _happy,_ and _c2hs_ as build-time dependencies, using [Halcyon](https://halcyon.sh/).

Since _c2hs_ itself requires _alex_ and _happy_ at build-time, the [sandbox pre-build hook](https://halcyon.sh/reference/#halcyon_sandbox_pre_build_hook) is used to install _c2hs_ with a recursive `halcyon install` command.


Usage
-----

```
$ halcyon-recursive-example
```


### Installation

Installs in one command on most systems, using [Halcyon](https://halcyon.sh/):

```
$ halcyon install https://github.com/mietek/halcyon-recursive-example
```


About
-----

Made by [Miëtek Bak](https://mietek.io/).  Published under the [MIT X11 license](https://mietek.io/license/).
