---
id: common.smartctl
title: Smartctl
desc: ''
updated: 1664955321107
created: 1664955321107
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# smartctl

> Monitor disk health including SMART data.
> More information: <https://www.smartmontools.org>.

- Display SMART health summary:

`sudo smartctl --health {{/dev/sdX}}`

- Display device information:

`sudo smartctl --info {{/dev/sdX}}`

- Start a short self-test in the background:

`sudo smartctl --test short {{/dev/sdX}}`

- Display current/last self-test status and other SMART capabilities:

`sudo smartctl --capabilities {{/dev/sdX}}`

- Display exhaustive SMART data:

`sudo smartctl --all {{/dev/sdX}}`

