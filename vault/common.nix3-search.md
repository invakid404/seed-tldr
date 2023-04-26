---
id: common.nix3-search
title: Nix3 Search
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
# nix search

> Search for packages in a Nix flake.
> See `tldr nix3 flake` for information about flakes.
> More information: <https://nixos.org/manual/nix/stable/command-ref/new-cli/nix3-search.html>.

- Search `nixpkgs` for a package based on its name or description:

`nix search {{nixpkgs}} {{search_term...}}`

- Show description of a package from nixpkgs:

`nix search {{nixpkgs#pkg}}`

- Show all packages available from a flake on github:

`nix search {{github:owner/repo}}`

