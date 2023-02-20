---
id: windows.choco-uninstall
title: Choco Uninstall
desc: ''
updated: 1676881477676
created: 1676881477676
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# choco uninstall

> Uninstall one or more packages with Chocolatey.
> More information: <https://chocolatey.org/docs/commands-uninstall>.

- Uninstall one or more space-separated packages:

`choco uninstall {{package1 package2 ...}}`

- Uninstall a specific version of a package:

`choco uninstall {{package}} --version {{version}}`

- Confirm all prompts automatically:

`choco uninstall {{package}} --yes`

- Remove all dependencies when uninstalling:

`choco uninstall {{package}} --remove-dependencies`

- Uninstall all packages:

`choco uninstall all`

