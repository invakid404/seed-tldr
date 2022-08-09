---
id: linux.termusic
title: Termusic
desc: ''
updated: 1660072904816
created: 1660072904816
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# termusic

> A terminal music player written in Rust that uses vim-like key bindings.
> More information: <https://github.com/tramhao/termusic>.

- Open termusic to a specific directory. (It can be set permanently in `~/.config/termusic/config.toml`):

`termusic {path/to/directory}`

- Disable showing the album cover for a specific file:

`termusic -c {path/to/music_file}`

- View termusic's usage info:

`termusic --help`

