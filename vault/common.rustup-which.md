---
id: common.rustup-which
title: Rustup Which
desc: ''
updated: 1694927709581
created: 1694927709581
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rustup which

> Display which binary will be run for a given command managed by `rustup`.
> Like `which`, but searches a Rust toolchain instead of `$PATH`.
> More information: <https://rust-lang.github.io/rustup>.

- Display the path to the binary in the default toolchain:

`rustup which {{command}}`

- Display the path to the binary in the specified toolchain (see `rustup help toolchain` for more information):

`rustup which --toolchain {{toolchain}} {{command}}`

