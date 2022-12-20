# Github Workflows

- [.github/workflows](./github/worflows) - reusable workflows
  - [nix-ci](./.github/workflows/nix-ci.yaml) - Install Nix and cache inputs and outputs of a flake using [flakes-tools](https://github.com/deemp/flakes/blob/main/flakes-tools/flake.nix)
- [.github/actions](./github/actions) - [composite actions](https://docs.github.com/en/actions/creating-actions/creating-a-composite-action)
  - [prepare-nix](./.github/actions/prepare-nix/action.yaml) - install Nix with a given version and config
