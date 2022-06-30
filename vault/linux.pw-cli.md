---
id: linux.pw-cli
title: Pw CLI
desc: ''
updated: 1656591837647
created: 1656591837647
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pw-cli

> The PipeWire Command Line Interface.
> More information: <https://docs.pipewire.org/page_man_pw_cli_1.html>.

- Print all nodes (sinks and sources) along with their IDs:

`pw-cli list-objects Node`

- Print information about an object with a specific ID:

`pw-cli info {{4}}`

- Print all objects' information:

`pw-cli info all`

