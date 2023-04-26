---
id: common.nix3-build
title: Nix3 Build
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
# nix build

> Build a Nix expression (downloading from the cache when possible).
> See also: `tldr nix-build`. See `tldr nix3 flake` for information about flakes.
> More information: <https://nixos.org/manual/nix/stable/command-ref/new-cli/nix3-build.html>.

- Build a package from nixpkgs, symlinking the result to `./result`:

`nix build {{nixpkgs#pkg}}`

- Build a package from a flake in the current directory, showing the build logs in the process:

`nix build -L {{.#pkg}}`

- Build the default package from a flake in some directory:

`nix build {{./path/to/directory}}`

- Build a package without making the `result` symlink, instead printing the store path to the stdout:

`nix build --no-link --print-out-paths`

