---
id: linux.sleep
title: Sleep
desc: ''
updated: 1675876629197
created: 1675876629197
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sleep

> Delay for a specified amount of time.
> More information: <https://www.gnu.org/software/coreutils/sleep>.

- Delay in seconds:

`sleep {{seconds}}`

- Delay in [m]inutes. (Other units [d]ay, [h]our, [s]econd, [inf]inity can also be used):

`sleep {{minutes}}m`

- Delay for 1 [d]ay 3 [h]ours:

`sleep 1d 3h`

- Execute a specific command after 20 [m]inutes delay:

`sleep 20m && {{command}}`

