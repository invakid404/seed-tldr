---
id: common.xml
title: Xml
desc: ''
updated: 1670142131035
created: 1670142131035
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xml

> XMLStarlet Toolkit: Query, edit, check, convert and transform XML documents.
> This command also has documentation about its subcommands, e.g. `xml validate`.
> More information: <http://xmlstar.sourceforge.net/docs.php>.

- Display general help, including the list of subcommands:

`xml --help`

- Execute a subcommand with input from a file or URI, printing to `stdout`:

`xml {{subcommand}} {{options}} {{path/to/input.xml|URI}}`

- Execute a subcommand using `stdin` and `stdout`:

`xml {{subcommand}} {{options}}`

- Execute a subcommand with input from a file or URI and output to a file:

`xml {{subcommand}} {{options}} {{path/to/input.xml|URI}} > {{path/to/output}}`

- Display help for a subcommand:

`xml {{subcommand}} --help`

- Display the version of the XMLStarlet Toolkit:

`xml --version`

