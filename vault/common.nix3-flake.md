---
id: common.nix3-flake
title: Nix3 Flake
desc: ''
updated: 1682500598900
created: 1682500598900
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nix flake

> Manage Nix flakes.
> More information: <https://nixos.org/manual/nix/stable/command-ref/new-cli/nix3-flake.html>.

- See documentation about what Nix flakes are:

`nix flake --help`

- Create a new flake (just the `flake.nix` file) from the default template, in the current directory:

`nix flake init`

- Update all inputs (dependencies) of the flake in the current directory:

`nix flake update`

- Update a specific input (dependency) of the flake in the current directory:

`nix flake lock --update-input {{input}}`

- Show all the outputs of a flake on github:

`nix flake show {{github:owner/repo}}`

