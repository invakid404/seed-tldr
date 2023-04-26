---
id: common.nix3-develop
title: Nix3 Develop
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
# nix develop

> Run a bash shell that provides the build environment of a derivation.
> More information: <https://nixos.org/manual/nix/stable/command-ref/new-cli/nix3-develop.html>.

- Start a shell with all dependencies of a package from nixpkgs available:

`nix develop {{nixpkgs#pkg}}`

- Start a development shell for the default package in a flake in the current directory:

`nix develop`

- In that shell, configure and build the sources:

`configurePhase; buildPhase`

