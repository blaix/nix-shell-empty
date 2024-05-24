# Bare Bones Nix Shell Template

This is a template for an isolated [nix shell](https://nixos.wiki/wiki/Development_environment_with_nix-shell)
that automatically loads with [direnv](https://direnv.net/).

## Requirements

* [nix](https://nix.dev/install-nix.html)
* [direnv](https://direnv.net/)
* Optional but highly recommended: [nix-direnv](https://github.com/nix-community/nix-direnv)
* Optional: [degit](https://github.com/Rich-Harris/degit) (otherwise just copy this repo however you want)

## Usage

1. `degit blaix/nix-shell-empty my-project`
2. `cd my-project`
3. `direnv allow`
