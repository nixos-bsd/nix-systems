# nixbsd nix-systems
For some reason [flake-utils](https://github.com/numtide/flake-utils) puts its
supported systems in a separate flake with a limited set.
This flake includes all systems in `lib.systems.flakeExposed`,
though it may also add other platforms in the future if sandboxing is implemented.
You can use this with `--override-input flake-utils/systems github:nixos-bsd/flake-systems`
