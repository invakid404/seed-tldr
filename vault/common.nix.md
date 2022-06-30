---
id: common.nix
title: Nix
desc: ''
updated: 1656591837531
created: 1656591837531
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nix

> Utilities for the Nix language and store.
> More information: <https://nixos.org>.

- Search for a package via its name or description:

`nix search {{search_term}}`

- Start a Nix shell with the specified packages available:

`nix run {{nixpkgs.pkg1 nixpkgs.pkg2 nixpkgs.pkg3...}}`

- Optimise Nix store disk usage by combining duplicate files:

`nix store optimise`

- Start an interactive environment for evaluating Nix expressions:

`nix repl`

- Upgrade Nix to the latest stable version:

`nix upgrade-nix`

