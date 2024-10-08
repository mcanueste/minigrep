# minigrep
Example implementation of grep from the Rust Book

## Nix Template

This repository can also be used as a nix template to start a new simple Rust CLI project without any dependencies.

```sh
mkdir my-project && cd my-project
nix flake init --template github:mcanueste/minigrep#default
```

Then you can edit `flake.nix` to address `FIXME` comments and start developing your project. You should also
update the `LICENSE` file if you don't want to use the MIT license.
