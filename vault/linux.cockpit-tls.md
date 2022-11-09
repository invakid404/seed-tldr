---
id: linux.cockpit-tls
title: Cockpit Tls
desc: ''
updated: 1667989445060
created: 1667989445060
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cockpit-tls

> TLS terminating HTTP proxy to encrypt traffic between a client and `cockpit-ws`.
> More information: <https://cockpit-project.org/guide/latest/cockpit-tls.8.html>.

- Serve HTTP requests to a specific port instead of port `9090`:

`cockpit-tls --port {{port}}`

- Display help:

`cockpit-tls --help`

