Opam repository for termite packages.
========

To install termite using opam:

```sh
opam remote add termite https://github.com/termite-analyser/opam-termite.git

# Run and add this to your .bashrc.
export LD_LIBRARY_PATH=`ocamlfind printconf destdir`/stublibs

# Take a coffee, and wait for Z3's compilation.
opam install termite -v

```
