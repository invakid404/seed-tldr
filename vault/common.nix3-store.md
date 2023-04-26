---
id: common.nix3-store
title: Nix3 Store
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
# nix store

> Manipulate the Nix store.
> See also: `tldr nix-store`.
> More information: <https://nixos.org/manual/nix/stable/command-ref/new-cli/nix3-store.html>.

- Collect garbage, i.e. remove unused paths to reduce space usage:

`nix store gc`

- Hard-link identical files together to reduce space usage:

`nix store optimise`

- Delete a specific store path (most be unused):

`nix store delete {{/nix/store/...}}`

- List a contents of the store path, on a remote store:

`nix store --store {{https://cache.nixos.org}} ls {{/nix/store/...}}`

- Show the differences in versions between two store paths, with their respective dependencies:

`nix store diff-closures {{/nix/store/...}} {{/nix/store/...}}`

