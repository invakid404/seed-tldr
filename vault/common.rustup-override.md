---
id: common.rustup-override
title: Rustup Override
desc: ''
updated: 1695129589197
created: 1695129589197
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rustup override

> Modify directory toolchain overrides.
> See `rustup help toolchain` for more information about toolchains.
> More information: <https://rust-lang.github.io/rustup>.

- List directiory toolchain overrides:

`rustup override list`

- Set the override toolchain for the current directory (i.e. tell `rustup` to run `cargo`, `rustc`, etc. from a specific toolchain when in that directory):

`rustup override set {{toolchain}}`

- Remove the toolchain override for the current directory:

`rustup override unset`

- Remove all toolchain overrides for directories that no longer exist:

`rustup override unset --nonexistent`

