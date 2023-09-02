---
id: linux.systemd-tty-ask-password-agent
title: Systemd Tty Ask Password Agent
desc: ''
updated: 1693667639903
created: 1693667639903
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# systemd-tty-ask-password-agent

> List or process pending systemd password requests.
> More information: <https://www.freedesktop.org/software/systemd/man/systemd-tty-ask-password-agent.html>.

- List all currently pending system password requests:

`systemd-tty-ask-password-agent --list`

- Continuously process password requests:

`systemd-tty-ask-password-agent --watch`

- Process all currently pending system password requests by querying the user on the calling TTY:

`systemd-tty-ask-password-agent --query`

- Forward password requests to wall instead of querying the user on the calling TTY:

`systemd-tty-ask-password-agent --wall`

