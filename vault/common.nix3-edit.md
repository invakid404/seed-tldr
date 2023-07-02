---
id: common.nix3-edit
title: Nix3 Edit
desc: ''
updated: 1688304044929
created: 1688304044929
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nix edit

> Open the Nix expression of a Nix package in $EDITOR.
> More information: <https://nixos.org/manual/nix/stable/command-ref/new-cli/nix3-edit.html>.

- Open the source of the Nix expression of a package from nixpkgs in your `$EDITOR`:

`nix edit {{nixpkgs#pkg}}`

- Dump the source of a package to `stdout`:

`EDITOR=cat nix edit {{nixpkgs#pkg}}`

