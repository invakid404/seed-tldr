---
id: common.airdecap-ng
title: Airdecap Ng
desc: ''
updated: 1684019725016
created: 1684019725016
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# airdecap-ng

> Decrypt a WEP, WPA or WPA2 encrypted capture file.
> Part of Aircrack-ng network software suite.
> More information: <https://www.aircrack-ng.org/doku.php?id=airdecap-ng>.

- Remove wireless headers from an open network capture file and use the access point's MAC address to filter:

`airdecap-ng -b {{ap_mac}} {{path/to/capture.cap}}`

- Decrypt a WEP encrypted capture file using the key in hex format:

`airdecap-ng -w {{hex_key}} {{path/to/capture.cap}}`

- Decrypt a WPA/WPA2 encrypted capture file using the access point's [e]ssid and [p]assword:

`airdecap-ng -e {{essid}} -p {{password}} {{path/to/capture.cap}}`

- Decrypt a WPA/WPA2 encrypted capture file preserving the headers using the access point's [e]ssid and [p]assword:

`airdecap-ng -l -e {{essid}} -p {{password}} {{path/to/capture.cap}}`

- Decrypt a WPA/WPA2 encrypted capture file using the access point's [e]ssid and [p]assword and use its MAC address to filter:

`airdecap-ng -b {{ap_mac}} -e {{essid}} -p {{password}} {{path/to/capture.cap}}`

