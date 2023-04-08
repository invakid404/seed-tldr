---
id: common.snort
title: Snort
desc: ''
updated: 1680963230058
created: 1680963230058
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# snort

> Open-source network intrusion detection system.
> More information: <https://www.snort.org/#documents>.

- Capture packets with verbose output:

`sudo snort -v -i {{interface}}`

- Capture packets and dump application layer data with verbose output:

`sudo snort -vd -i {{interface}}`

- Capture packets and display link layer packet headers with verbose output:

`sudo snort -ve -i {{interface}}`

- Capture packets and save them in the specified directory:

`sudo snort -i {{interface}} -l {{path/to/directory}}`

- Capture packets according to rules and save offending packets along with alerts:

`sudo snort -i {{interface}} -c {{path/to/rules.conf}} -l {{path/to/directory}}`

