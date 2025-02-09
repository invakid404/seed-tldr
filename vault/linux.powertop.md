---
id: linux.powertop
title: Powertop
desc: ''
updated: 1692289227400
created: 1692289227400
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# powertop

> Optimize battery power usage.
> More information: <https://github.com/fenrus75/powertop>.

- Calibrate power usage measurements:

`sudo powertop --calibrate`

- Generate HTML power usage report in the current directory:

`sudo powertop --html={{power_report.html}}`

- Tune to optimal settings:

`sudo powertop --auto-tune`

- Generate a report for a specified number of seconds (instead of 20 by default):

`sudo powertop --time={{5}}`

