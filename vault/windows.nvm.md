---
id: windows.nvm
title: Nvm
desc: ''
updated: 1666696985764
created: 1666696985764
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nvm

> Install, uninstall, or switch between Node.js versions.
> Supports version numbers like "12.8" or "v16.13.1", and labels like "stable", "system", etc.
> More information: <https://github.com/coreybutler/nvm-windows>.

- Install a specific version of Node.js:

`nvm install {{node_version}}`

- Set the default version of Node.js (must be run as Administrator):

`nvm use {{node_version}}`

- List all available Node.js versions and highlight the default one:

`nvm list`

- List all remote Node.js versions:

`nvm ls-remote`

- Uninstall a given Node.js version:

`nvm uninstall {{node_version}}`

