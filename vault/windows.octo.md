---
id: windows.octo
title: Octo
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
# octo

> Command-line tools for Octopus Deploy.
> More information: <https://octopus.com/docs/octopus-rest-api/octo.exe-command-line>.

- Create a package:

`octo pack --id={{package}}`

- Push a package to a repository on the Octopus server:

`octo push --package={{package}}`

- Create a release:

`octo create-release --project={{project_name}} --packageversion={{version}}`

- Deploy a release:

`octo deploy-release --project={{project_name}} --packageversion={{version}} --deployto={{environment_name}} --tenant={{deployment_target}}`

