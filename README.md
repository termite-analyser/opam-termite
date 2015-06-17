Opam repository for termite packages.
========

[termite][termite] is a termination analyser.

To install termite using opam:

- Install llvm 3.6

- Add the repository.
  ```sh
  opam remote add termite https://github.com/termite-analyser/opam-termite.git
  ```

- Take a coffee, and wait for Z3's compilation.
  ```
  opam install termite -v
  ```

- Install [Pagai](http://pagai.forge.imag.fr/). The Z3 version doesn't matter but the llvm version used by pagai should be the same than the one used by termite.

- Clang is also very recommended.


[termite]: https://termite-analyser.github.io/
