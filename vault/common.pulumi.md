---
id: common.pulumi
title: Pulumi
desc: ''
updated: 1664113079480
created: 1664113079480
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pulumi

> Define infrastructure on any cloud using familiar programming languages.
> More information: <https://www.pulumi.com/docs/reference/cli>.

- Create a new project using a template:

`pulumi new`

- Create a new stack using an isolated deployment target:

`pulumi stack init`

- Configure variables (e.g. keys, regions, etc.) interactively:

`pulumi config`

- Preview and deploy changes to a program and/or infrastructure:

`pulumi up`

- Preview deployment changes without performing them (dry-run):

`pulumi preview`

- Destroy a program and its infrastructure:

`pulumi destroy`

