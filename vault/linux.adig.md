---
id: linux.adig
title: Adig
desc: ''
updated: 1664692534026
created: 1664692534026
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# adig

> Prints information received from Domain Name System (DNS) servers.
> More information: <https://manned.org/adig>.

- Display A (default) record from DNS for hostname(s):

`adig {{example.com}}`

- Display extra [d]ebugging output:

`adig -d {{example.com}}`

- Connect to [s]pecified DNS server:

`adig -s {{1.2.3.4}} {{example.com}}`

- Use specified TCP port to connect to DNS server:

`adig -T {{port}} {{example.com}}`

- Use specified UDP port to connect to DNS server:

`adig -U {{port}} {{example.com}}`

