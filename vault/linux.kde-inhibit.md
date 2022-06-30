---
id: linux.kde-inhibit
title: Kde Inhibit
desc: ''
updated: 1656591837629
created: 1656591837629
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kde-inhibit

> Inhibit various desktop functions while a command runs.
> More information: <https://invent.kde.org/plasma/kde-cli-tools/-/blob/master/kdeinhibit/main.cpp>.

- Inhibit power management:

`kde-inhibit --power {{command}} {{command_arguments}}`

- Inhibit screen saver:

`kde-inhibit --screenSaver {{command}} {{command_arguments}}`

- Launch VLC, and inhibit color correction (night mode) while it's running:

`kde-inhibit --colorCorrect {{vlc}}`

