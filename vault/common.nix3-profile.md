---
id: common.nix3-profile
title: Nix3 Profile
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
# nix profile

> Install, update and remove packages from Nix profiles.
> More information: <https://nixos.org/manual/nix/stable/command-ref/new-cli/nix3-profile.html>.

- Install some packages from nixpkgs into the default profile:

`nix profile install {{nixpkgs#pkg1 nixpkgs#pkg2 ...}}`

- Install a package from a flake on GitHub into a custom profile:

`nix profile install {{github:owner/repo/pkg}} --profile {{./path/to/directory}}`

- List packages currently installed in the default profile:

`nix profile list`

- Remove a package installed from nixpkgs from the default profile, by name:

`nix profile remove {{legacyPackages.x86_64-linux.pkg}}`

- Upgrade packages in the default to the latest available versions:

`nix profile upgrade`

- Rollback (cancel) the latest action on the default profile:

`nix profile rollback`

