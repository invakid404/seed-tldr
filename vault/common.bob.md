---
id: common.bob
title: Bob
desc: ''
updated: 1683044482709
created: 1683044482709
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bob

> Manage and switch between Neovim versions.
> More information: <https://github.com/MordechaiHadad/bob>.

- Install and switch to the specified version of Neovim:

`bob use {{nightly|stable|latest|version_string|commit_hash}}`

- List installed and currently used versions of Neovim:

`bob list`

- Uninstall the specified version of Neovim:

`bob uninstall {{nightly|stable|latest|version_string|commit_hash}}`

- Uninstall Neovim and erase any changes `bob` has made:

`bob erase`

- Roll back to a previous nightly version:

`bob rollback`

