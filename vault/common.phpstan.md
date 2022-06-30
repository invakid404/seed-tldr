---
id: common.phpstan
title: Phpstan
desc: ''
updated: 1656591837543
created: 1656591837543
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# phpstan

> A PHP static analysis tool to discover bugs in code.
> More information: <https://github.com/phpstan/phpstan>.

- Display available options for analysis:

`phpstan analyse --help`

- Analyze the specified space-separated directories:

`phpstan analyse {{path/to/directory}}`

- Analyze a directory using a configuration file:

`phpstan analyse {{path/to/directory}} --configuration {{path/to/config}}`

- Analyze using a specific rule level (0-7, higher is stricter):

`phpstan analyse {{path/to/directory}} --level {{level}}`

- Specify an autoload file to load before analyzing:

`phpstan analyse {{path/to/directory}} --autoload-file {{path/to/autoload_file}}`

- Specify a memory limit during analysis:

`phpstan analyse {{path/to/directory}} --memory-limit {{memory_limit}}`

