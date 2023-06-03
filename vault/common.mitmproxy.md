---
id: common.mitmproxy
title: Mitmproxy
desc: ''
updated: 1685798278874
created: 1685798278874
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mitmproxy

> An interactive man-in-the-middle HTTP proxy.
> See also: `mitmweb`.
> More information: <https://docs.mitmproxy.org/stable/concepts-options>.

- Start `mitmproxy` with default settings:

`mitmproxy`

- Start `mitmproxy` bound to a custom address and port:

`mitmproxy --listen-host {{ip_address}} --listen-port {{port}}`

- Start `mitmproxy` using a script to process traffic:

`mitmproxy --scripts {{path/to/script.py}}`

- Export the logs with SSL/TLS master keys to external programs (wireshark, etc.):

`SSLKEYLOGFILE="{{path/to/file}}" mitmproxy`

