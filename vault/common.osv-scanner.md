---
id: common.osv-scanner
title: Osv Scanner
desc: ''
updated: 1675739975398
created: 1675739975398
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# osv-scanner

> Scan various mediums for dependencies and matches them against the OSV database.
> More information: <https://osv.dev/about>.

- Scan a docker image:

`osv-scanner -D {{docker_image_name}}`

- Scan a package lockfile:

`osv-scanner -L {{path/to/lockfile}}`

- Scan an SBOM file:

`osv-scanner -S {{path/to/sbom_file}}`

- Scan multiple directories recursively:

`osv-scanner -r {{directory1 directory2 ...}}`

- Skip scanning git repositories:

`osv-scanner --skip-git {{-r|-D}} {{target}}`

- Output result in JSON format:

`osv-scanner --json {{-D|-L|-S|-r}} {{target}}`

