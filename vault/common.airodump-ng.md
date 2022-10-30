---
id: common.airodump-ng
title: Airodump Ng
desc: ''
updated: 1667133702642
created: 1667133702642
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# airodump-ng

> Capture packets and display information about wireless networks.
> Part of `aircrack-ng`.
> More information: <https://www.aircrack-ng.org/doku.php?id=airodump-ng>.

- Capture packets and display information about a wireless network:

`sudo airodump-ng {{interface}}`

- Capture packets and display information about a wireless network given the MAC address and channel, and save the output to a file:

`sudo airodump-ng --channel {{channel}} --write {{path/to/file}} --bssid {{mac}} {{interface}}`

