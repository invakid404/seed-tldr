---
id: common.wondershaper
title: Wondershaper
desc: ''
updated: 1656591837595
created: 1656591837595
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wondershaper

> Allows the user to limit the bandwidth of one or more network adapters.
> More information: <https://github.com/magnific0/wondershaper#usage>.

- Display [h]elp:

`wondershaper -h`

- Show the current [s]tatus of a specific [a]dapter:

`wondershaper -s -a {{adapter_name}}`

- Clear limits from a specific [a]dapter:

`wondershaper -c -a {{adapter_name}}`

- Set a specific maximum [d]ownload rate (in Kbps):

`wondershaper -a {{adapter_name}} -d {{1024}}`

- Set a specific maximum [u]pload rate (in Kbps):

`wondershaper -a {{adapter_name}} -u {{512}}`

- Set a specific maximum [d]ownload rate and [u]pload rate (in Kpbs):

`wondershaper -a {{adapter_name}} -d {{1024}} -u {{512}}`

