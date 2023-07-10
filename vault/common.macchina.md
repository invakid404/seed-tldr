---
id: common.macchina
title: Macchina
desc: ''
updated: 1688970295075
created: 1688970295075
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# macchina

> Display information about your computer.
> More information: <https://github.com/Macchina-CLI/macchina>.

- List out system information, with either default settings or those specified in your configuration file:

`macchina`

- Specify a custom configuration file path:

`macchina --config {{path/to/configuration_file}}`

- List system information, but lengthen uptime, shell and kernel output:

`macchina --long-uptime --long-shell --long-kernel`

- Check for any errors/system failures encountered when trying to fetch system information:

`macchina --doctor`

- List original artists of all the ASCII art:

`macchina --ascii-artists`

