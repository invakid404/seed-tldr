---
id: common.rustup-target
title: Rustup Target
desc: ''
updated: 1693660581008
created: 1693660581008
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rustup target

> Modify a toolchain's supported targets.
> Without the `--toolchain` option `rustup` will use the default toolchain. See `rustup help toolchain` for more information about toolchains.
> More information: <https://rust-lang.github.io/rustup>.

- Add a target to a toolchain:

`rustup target add --toolchain {{toolchain}} {{target}}`

- Remove a target from a toolchain:

`rustup target remove --toolchain {{toolchain}} {{target}}`

- List available and installed targets for a toolchain:

`rustup target list --toolchain {{toolchain}}`

- List installed targets for a toolchain:

`rustup target list --toolchain {{toolchain}} --installed`

