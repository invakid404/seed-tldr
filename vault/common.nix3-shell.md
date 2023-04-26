---
id: common.nix3-shell
title: Nix3 Shell
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
# nix shell

> Start a shell in which the specified packages are available.
> See also: `tldr nix-shell`. See `tldr nix3 flake` for information about flakes.
> More information: <https://nixos.org/manual/nix/stable/command-ref/new-cli/nix3-shell.html>.

- Start an interactive shell with some packages from `nixpkgs`:

`nix shell {{nixpkgs#pkg1 nixpkgs#packageSet.pkg2 ...}}`

- Start a shell providing a package from an older version of `nixpkgs` (21.05):

`nix shell {{nixpkgs/nixos-21.05#pkg}}`

- Start a shell with the "default package" from a flake in the current directory, printing build logs if any builds happen:

`nix shell -L`

- Start a shell with a package from a flake on GitHub:

`nix shell {{github:owner/repo#pkg}}`

- Run a command in a shell with a package:

`nix shell {{nixpkgs#pkg}} -c {{some-cmd --someflag 'Some other arguments'}}`

