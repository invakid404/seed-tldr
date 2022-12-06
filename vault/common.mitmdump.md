---
id: common.mitmdump
title: Mitmdump
desc: ''
updated: 1670310991825
created: 1670310991825
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mitmdump

> View, record, and programmatically transform HTTP traffic.
> The command-line counterpart to mitmproxy.
> More information: <https://docs.mitmproxy.org/stable/overview-tools/#mitmdump>.

- Start a proxy and save all output to a file:

`mitmdump -w {{path/to/file}}`

- Filter a saved traffic file to just POST requests:

`mitmdump -nr {{input_filename}} -w {{output_filename}} "{{~m post}}"`

- Replay a saved traffic file:

`mitmdump -nc {{path/to/file}}`

