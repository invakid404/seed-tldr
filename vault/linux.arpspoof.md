---
id: linux.arpspoof
title: Arpspoof
desc: ''
updated: 1677745487000
created: 1677745487000
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# arpspoof

> Forge ARP replies to intercept packets.
> More information: <https://monkey.org/~dugsong/dsniff>.

- Poison all hosts to intercept packets on [i]nterface for the host:

`sudo arpspoof -i {{wlan0}} {{host_ip}}`

- Poison [t]arget to intercept packets on [i]nterface for the host:

`sudo arpspoof -i {{wlan0}} -t {{target_ip}} {{host_ip}}`

- Poison both [t]arget and host to intercept packets on [i]nterface for the host:

`sudo arpspoof -i {{wlan0}} -r -t {{target_ip}} {{host_ip}}`

