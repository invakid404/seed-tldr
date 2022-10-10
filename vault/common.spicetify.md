---
id: common.spicetify
title: Spicetify
desc: ''
updated: 1665415810265
created: 1665415810265
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# spicetify

> A CLI utility to customize the Spotify client UI and functionality.
> More information: <https://spicetify.app>.

- Generate a configuration file on very first run and display help:

`spicetify`

- Backup and preprocess Spotify application files:

`spicetify backup`

- Print all configuration fields and values:

`spicetify config`

- Change the value of a configuration field:

`spicetify config {{field}} {{value}}`

- Apply the customization changes to Spotify:

`spicetify apply`

- Restore Spotify to its original state:

`spicetify restore`

