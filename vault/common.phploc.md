---
id: common.phploc
title: Phploc
desc: ''
updated: 1656591837542
created: 1656591837542
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# phploc

> A tool for quickly measuring the size and analyzing the structure of a PHP project.
> More information: <https://github.com/sebastianbergmann/phploc>.

- Analyze a directory and print the result:

`phploc {{path/to/directory}}`

- Include only specific files from a comma-separated list (globs are allowed):

`phploc {{path/to/directory}} --names {{files}}`

- Exclude specific files from a comma-separated list (globs are allowed):

`phploc {{path/to/directory}} --names-exclude {{files}}`

- Exclude a specific directory from analysis:

`phploc {{path/to/directory}} --exclude {{path/to/exclude_directory}}`

- Log the results to a specific CSV file:

`phploc {{path/to/directory}} --log-csv {{path/to/file}}`

- Log the results to a specific XML file:

`phploc {{path/to/directory}} --log-xml {{path/to/file}}`

- Count PHPUnit test case classes and test methods:

`phploc {{path/to/directory}} --count-tests`

