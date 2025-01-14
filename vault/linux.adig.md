---
id: linux.adig
title: Adig
desc: ''
updated: 1673011412883
created: 1673011412883
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

- Connect to a specific DNS [s]erver:

`adig -s {{1.2.3.4}} {{example.com}}`

- Use a specific TCP port to connect to a DNS server:

`adig -T {{port}} {{example.com}}`

- Use a specific UDP port to connect to a DNS server:

`adig -U {{port}} {{example.com}}`

