---
id: linux.cockpit-ws
title: Cockpit Ws
desc: ''
updated: 1667078414298
created: 1667078414298
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cockpit-ws

> Communicate between the browser application and various configuration tools and services like `cockpit-bridge`.
> More information: <https://cockpit-project.org/guide/latest/cockpit-ws.8.html>.

- Start with authentication via SSH at `127.0.0.1` with port `22` enabled:

`cockpit-ws --local-ssh`

- Start an HTTP server on a specific port:

`cockpit-ws --port {{port}}`

- Start and bind to a specific IP address (defaults to `0.0.0.0`):

`cockpit-ws --address {{ip_address}}`

- Start without TLS:

`cockpit-ws --no-tls`

- Display help:

`cockpit-ws --help`

