---
id: linux.pacman-key
title: Pacman Key
desc: ''
updated: 1666020662855
created: 1666020662855
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pacman-key

> Wrapper script for GnuPG used to manage pacman's keyring.
> More information: <https://man.archlinux.org/man/pacman-key>.

- Initialize the pacman keyring:

`sudo pacman-key --init`

- Add the default Arch Linux keys:

`sudo pacman-key --populate {{archlinux}}`

- List keys from the public keyring:

`pacman-key --list-keys`

- Add the specified keys:

`sudo pacman-key --add {{path/to/keyfile.gpg}}`

- Receive a key from a key server:

`sudo pacman-key --recv-keys "{{uid|name|email}}"`

- Print the fingerprint of a specific key:

`pacman-key --finger "{{uid|name|email}}"`

- Sign an imported key locally:

`sudo pacman-key --lsign-key "{{uid|name|email}}"`

- Remove a specific key:

`sudo pacman-key --delete "{{uid|name|email}}"`

