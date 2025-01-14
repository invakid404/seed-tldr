---
id: linux.startx
title: Startx
desc: ''
updated: 1665260759050
created: 1665260759050
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# startx

> The startx script is a front end to xinit that provides a nice user interface for running a single session of the X Window System.
> More information: <https://x.org/releases/X11R7.5/doc/man/man1/startx.1.html>.

- Start an X session:

`startx`

- Start an X session with a predefined depth value:

`startx -- -depth {{value}}`

- Start an X session with a predefined dpi value:

`startx -- -dpi {{value}}`

- Override the settings in the `.xinitrc` file and start a new X session:

`startx /{{path/to/window_manager_or_desktop_environment}}`

