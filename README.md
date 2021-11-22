# The OCaml Native Toplevel Experience

With the release of OCaml 4.14, the native toplevel libraries will be installed
by default with the compiler, finally making it easily accessible. This will
benefit quite a lot tools and workflows.

This repository exists to document the various projects involved in improving the
toplevel experience for OCaml.

- [The OCaml Compiler](https://github.com/ocaml/ocaml)
- [The flambda2 fork of the compiler](https://github.com/ocaml-flambda/flambda-backend)
- [The in process assembler/loader for the native toplevel](https://github.com/NathanReb/ocaml-jit)
- [MDX](https://github.com/realworldocaml/mdx)

In addition to those, there are also temporary forks or workaround libraries that one
can use to try the native toplevel and related tools before everything is released.

- [Findlib Metadata for a unified toplevel library](https://github.com/NathanReb/compiler-libs-either-toplevel)

## What is left

The native toplevel had been lagging behind quite a bit and there is a bit of work to
do to bring it up to date with the bytecode toplevel.
In addition, as we just started testing the MDX with native toplevel experience, we
also started uncovering bugs that impacts either of the involved tools and more often
than not, a combination of them. We use this repository's
[issue tracker](https://github.com/NathanReb/ocaml-native-toplevel-experience/issues)
and
[project board](https://github.com/NathanReb/ocaml-native-toplevel-experience/projects/1)
to keep track of the work left to do to have a native toplevel experience that matches
the bytecode.
