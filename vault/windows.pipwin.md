---
id: windows.pipwin
title: Pipwin
desc: ''
updated: 1693073888724
created: 1693073888724
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pipwin

> A tool to install unofficial Python package binaries on Windows.
> More information: <https://github.com/lepisma/pipwin>.

- List all available packages for download:

`pipwin list`

- Search packages:

`pipwin search {{partial_name|name}}`

- Install a package:

`pipwin install {{package}}`

- Uninstall a package:

`pipwin uninstall {{package}}`

- Download a package to a specific directory:

`pipwin download --dest {{path\to\directory}} {{package}}`

- Install packages according to `requirements.txt`:

`pipwin install --file {{path\to\requirements.txt}}`

