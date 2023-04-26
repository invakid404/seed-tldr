---
id: common.nix3-why-depends
title: Nix3 Why Depends
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
# nix why-depends

> Show why a package depends on another package.
> More information: <https://nixos.org/manual/nix/stable/command-ref/new-cli/nix3-why-depends.html>.

- Show why the currently running NixOS system requires a certain store path:

`nix why-depends {{/run/current-system}} {{/nix/store/...}}`

- Show why a package from nixpkgs requires another package as a _build-time_ dependency:

`nix why-depends --derivation {{nixpkgs#dependent}} {{nixpkgs#dependency}}`

