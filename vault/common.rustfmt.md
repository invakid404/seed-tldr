---
id: common.rustfmt
title: Rustfmt
desc: ''
updated: 1672809374591
created: 1672809374591
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rustfmt

> Tool for formatting Rust source code.
> More information: <https://github.com/rust-lang/rustfmt>.

- Format a file, overwriting the original file in-place:

`rustfmt {{path/to/source.rs}}`

- Check a file for formatting and display any changes on the console:

`rustfmt --check {{path/to/source.rs}}`

- Backup any modified files before formatting (the original file is renamed with a `.bk` extension):

`rustfmt --backup {{path/to/source.rs}}`

