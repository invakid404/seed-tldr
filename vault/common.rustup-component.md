---
id: common.rustup-component
title: Rustup Component
desc: ''
updated: 1695129589196
created: 1695129589196
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rustup component

> Modify a toolchain's installed components.
> Without the `--toolchain` option `rustup` will use the default toolchain. See `rustup help toolchain` for more information about toolchains.
> More information: <https://rust-lang.github.io/rustup>.

- Add a component to a toolchain:

`rustup component add --toolchain {{toolchain}} {{component}}`

- Remove a component from a toolchain:

`rustup component remove --toolchain {{toolchain}} {{component}}`

- List installed and available components for a toolchain:

`rustup component list --toolchain {{toolchain}}`

- List installed components for a toolchain:

`rustup component list --toolchain {{toolchain}} --installed`

