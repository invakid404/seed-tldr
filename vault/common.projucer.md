---
id: common.projucer
title: Projucer
desc: ''
updated: 1664678009492
created: 1664678009492
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# Projucer

> A project manager for JUCE framework applications.
> More information: <https://juce.com/discover/stories/projucer-manual#10.4-command-line-tools>.

- Display information about a project:

`Projucer --status {{path/to/project_file}}`

- Resave all files and resources in a project:

`Projucer --resave {{path/to/project_file}}`

- Update the version number in a project:

`Projucer --set-version {{version_number}} {{path/to/project_file}}`

- Generate a JUCE project from a PIP file:

`Projucer --create-project-from-pip {{path/to/PIP}} {{path/to/output}}`

- Remove all JUCE-style comments (`//=====`, `//-----` or `///////`):

`Projucer --tidy-divider-comments {{path/to/target_folder}}`

- Display help:

`Projucer --help`

