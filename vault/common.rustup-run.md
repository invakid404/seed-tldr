---
id: common.rustup-run
title: Rustup Run
desc: ''
updated: 1694927709580
created: 1694927709580
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rustup run

> Run a command with an environment configured for a given Rust toolchain.
> Note: all commands managed by `rustup` have a shorthand for this: for example, `cargo +nightly build` is equivalent to `rustup run nightly cargo build`.
> More information: <https://rust-lang.github.io/rustup>.

- Run a command using a given Rust toolchain (see `rustup help toolchain` for more information):

`rustup run {{toolchain}} {{command}}`

