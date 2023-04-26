---
id: common.nix3-registry
title: Nix3 Registry
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
# nix registry

> Manage a Nix flake registry.
> See `tldr nix3 flake` for information about flakes.
> More information: <https://nixos.org/manual/nix/stable/command-ref/new-cli/nix3-registry.html>.

- Pin the `nixpkgs` revision to the current version of the upstream repository:

`nix registry pin {{nixpkgs}}`

- Pin an entry to the latest version of the branch, or a particular reivision of a github repository:

`nix registry pin {{entry}} {{github:owner/repo/branch_or_revision}}`

- Add a new entry that always points to the latest version of a github repository, updating automatically:

`nix registry add {{entry}} {{github:owner/repo}}`

- Remove a registry entry:

`nix registry remove {{entry}}`

- See documentation about what Nix flake registries are:

`nix registry --help`

