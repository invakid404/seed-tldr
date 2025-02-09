---
id: common.cs
title: Cs
desc: ''
updated: 1693909002886
created: 1693909002886
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# coursier

> Application and artifact manager for the Scala language, it can install Scala applications and setup your Scala development environment.
> Some subcommands such as `install`, `launch`, `java`, `fetch`, `resolve`, `complete-dep`, etc. have their own usage documentation.
> More information: <https://get-coursier.io/docs/overview>.

- Display version:

`cs version`

- Show a list of the installed applications:

`cs list`

- Install a specific application:

`cs install {{application_name}}`

- Uninstall a specific application:

`cs uninstall {{application_name}}`

- Setup machine for the Scala development:

`cs setup`

- Update all the installed applications:

`cs update`

