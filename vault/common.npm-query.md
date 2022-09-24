---
id: common.npm-query
title: Npm Query
desc: ''
updated: 1664015078888
created: 1664015078888
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# npm query

> Print an array of dependency objects using CSS-like selectors.
> More information: <https://docs.npmjs.com/cli/v8/commands/npm-query>.

- Print direct dependencies:

`npm query ':root > *'`

- Print all direct production/development dependencies:

`npm query ':root > .{{prod|dev}}'`

- Print dependencies with a specific name:

`npm query '#{{package_name}}'`

- Print dependencies with a specific name and within a semantic versioning range:

`npm query #{{package_name}}@{{semantic_version}}`

- Print dependencies which have no dependencies:

`npm query ':empty'`

- Find all dependencies with postinstall scripts and uninstall them:

`npm query ":attr(scripts, [postinstall])" | jq 'map(.name) | join("\n")' -r | xargs -I {} npm uninstall {}`

- Find all Git dependencies and print which application requires them:

`npm query ":type(git)" | jq 'map(.name)' | xargs -I {} npm why {}`

