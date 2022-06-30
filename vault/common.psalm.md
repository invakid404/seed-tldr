---
id: common.psalm
title: Psalm
desc: ''
updated: 1656591837550
created: 1656591837550
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# psalm

> A static analysis tool for finding errors in PHP applications.
> More information: <https://psalm.dev>.

- Generate a Psalm configuration:

`psalm --init`

- Analyze the current working directory:

`psalm`

- Analyze a specific directory or file:

`psalm {{path/to/file_or_directory}}`

- Analyze a project with a specific configuration file:

`psalm --config {{path/to/psalm.xml}}`

- Include informational findings in the output:

`psalm --show-info`

- Analyze a project and display statistics:

`psalm --stats`

- Analyze a project in parallel with 4 threads:

`psalm --threads {{4}}`

