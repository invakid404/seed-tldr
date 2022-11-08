---
id: common.stty
title: Stty
desc: ''
updated: 1667882859779
created: 1667882859779
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# stty

> Set options for a terminal device interface.
> More information: <https://www.gnu.org/software/coreutils/stty>.

- Display all settings for the current terminal:

`stty --all`

- Set the number of rows:

`stty rows {{rows}}`

- Set the number of columns:

`stty cols {{cols}}`

- Get the actual transfer speed of a device:

`stty --file {{path/to/device_file}} speed`

- Reset all modes to reasonable values for the current terminal:

`stty sane`

