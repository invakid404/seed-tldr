---
id: common.gimp
title: Gimp
desc: ''
updated: 1656591837471
created: 1656591837471
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gimp

> GNU image manipulation program.
> See also: `krita`.
> More information: <https://docs.gimp.org/en/gimp-fire-up.html#gimp-concepts-running-command-line>.

- Start GIMP:

`gimp`

- Open specific files:

`gimp {{path/to/image1 path/to/image2 ...}}`

- Open specific files in a new window:

`gimp --new-instance {{path/to/image1 path/to/image2 ...}}`

- Start without a splash screen:

`gimp --no-splash`

- Print errors and warnings to the console instead of showing them in a dialog box:

`gimp --console-messages`

- Enable debugging signal handlers:

`gimp --debug-handlers`

