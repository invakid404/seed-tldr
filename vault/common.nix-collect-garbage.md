---
id: common.nix-collect-garbage
title: Nix Collect Garbage
desc: ''
updated: 1671672264733
created: 1671672264733
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nix-collect-garbage

> Delete unused and unreachable nix store paths.
> Generations can be listed using `nix-env --list-generations`.
> More information: <https://nixos.org/releases/nix/latest/manual/#sec-nix-collect-garbage>.

- Delete all store paths unused by current generations of each profile:

`sudo nix-collect-garbage --delete-old`

- Simulate the deletion of old store paths:

`sudo nix-collect-garbage --delete-old --dry-run`

- Delete all store paths older than 30 days:

`sudo nix-collect-garbage --delete-older-than 30d`

