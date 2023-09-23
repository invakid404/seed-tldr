---
id: common.cargo-update
title: Cargo Update
desc: ''
updated: 1695478400899
created: 1695478400899
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cargo update

> Update dependencies as recorded in `Cargo.lock`.
> More information: <https://doc.rust-lang.org/cargo/commands/cargo-update.html>.

- Update dependencies in `Cargo.lock` to the latest possible version:

`cargo update`

- Display what would be updated, but don't actually write the lockfile:

`cargo update --dry-run`

- Update only the specified dependencies:

`cargo update --package {{dependency1}} --package {{dependency2}} --package {{dependency3}}`

- Set a specific dependency to a specific version:

`cargo update --package {{dependency}} --precise {{1.2.3}}`

