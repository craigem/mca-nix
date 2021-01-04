MCA Common Nix Code
===================

This is a localised fork of iohk-nix_. The canonical source for this fork is
mca-nix_.


Original README continues below:

-----


This repo contains build code and tools shared between IOHK projects.

1. Pinned versions of [input-output-hk/nixpkgs](https://github.com/input-output-hk/nixpkgs).
2. Scripts for regenerating code with `nix-tools`.
3. Some util functions such as source filtering or helpers for [Haskell.nix](https://github.com/input-output-hk/haskell.nix).
4. Nix builds of development tools such as HLint, ShellCheck, Stylish Haskell, SHC, cache-s3.
5. Nix packages and overlay for the [rust-cardano](https://github.com/input-output-hk/rust-cardano)
   projects.


How to use in your project
--------------------------

See [new project skeleton](https://github.com/input-output-hk/cardano-skeleton/).

When making changes to `iohk-nix`
---------------------------------

Please document any change that might affect project builds in the
[ChangeLog](./changelog.md). For example:

- Bumping `nixpkgs` to a different branch.
- Changing API (renaming attributes, changing function parameters, etc).

Also update the [`skeleton`](https://github.com/input-output-hk/cardano-skeleton/) project if necessary.

.. _iohk-nix: https://github.com/input-output-hk/iohk-nix
.. _mca-nix:  https://github.com/craigem/mca-nix
