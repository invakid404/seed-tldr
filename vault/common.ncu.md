---
id: common.ncu
title: Ncu
desc: ''
updated: 1692828854239
created: 1692828854239
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ncu

> Find newer versions of package dependencies and check outdated npm packages locally or globally.
> `ncu` only updates dependency versions in `package.json`. To install the new versions, run `npm install` afterwards.
> More information: <https://github.com/raineorshine/npm-check-updates>.

- List outdated dependencies in the current directory:

`ncu`

- List outdated global npm packages:

`ncu -g`

- Upgrade all dependencies in the current directory:

`ncu -u`

- Interactively upgrade dependencies in the current directory:

`ncu -i`

- Display help:

`ncu -h`

