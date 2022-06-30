---
id: common.progpilot
title: Progpilot
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
# progpilot

> A PHP static analysis tool for detecting security vulnerabilities.
> More information: <https://github.com/designsecurity/progpilot>.

- Analyze the current directory:

`progpilot`

- Analyze a specific file or directory:

`progpilot {{path/to/file_or_directory}}`

- Specify a custom configuration file:

`progpilot --configuration {{path/to/configuration.yml}}`

