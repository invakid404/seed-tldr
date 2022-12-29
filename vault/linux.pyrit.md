---
id: linux.pyrit
title: Pyrit
desc: ''
updated: 1672355933803
created: 1672355933803
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pyrit

> WPA/WPA2 cracking tool using computational power.
> More information: <https://github.com/JPaulMora/Pyrit>.

- Display system cracking speed:

`pyrit benchmark`

- List available cores:

`pyrit list_cores`

- Set [e]SSID:

`pyrit -e "{{ESSID}}" create_essid`

- [r]ead and analyze a specific packet capture file:

`pyrit -r {{path/to/file.cap|path/to/file.pcap}} analyze`

- Read and [i]mport passwords to the current database:

`pyrit -i {{path/to/file}} {{import_unique_passwords|unique_passwords|import_passwords}}`

- Exp[o]rt passwords from database to a specific file:

`pyrit -o {{path/to/file}} export_passwords`

- Translate passwords with Pired Master Keys:

`pyrit batch`

- [r]ead the capture file and crack the password:

`pyrit -r {{path/to/file}} attack_db`

