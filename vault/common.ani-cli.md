---
id: common.ani-cli
title: Ani CLI
desc: ''
updated: 1666097653199
created: 1666097653199
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ani-cli

> A cli to browse and watch anime.
> More information: <https://github.com/pystardust/ani-cli>.

- Search anime by name:

`ani-cli "{{anime_name}}"`

- Download episode:

`ani-cli -d "{{anime_name}}"`

- Use VLC as the media player:

`ani-cli -v "{{anime_name}}"`

- Specify episode to watch:

`ani-cli -a {{episode_number}} "{{anime_name}}"`

- Continue watching anime from history:

`ani-cli -c`

- Update `ani-cli`:

`ani-cli -U`

