---
id: linux.protontricks
title: Protontricks
desc: ''
updated: 1663543430748
created: 1663543430748
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# protontricks

> A simple wrapper that runs Winetricks commands for Proton enabled games.
> More information: <https://github.com/Matoking/protontricks>.

- Run the protontricks GUI:

`protontricks --gui`

- Run Winetricks for a specific game:

`protontricks {{appid}} {{winetricks_args}}`

- Run a command within a game's installation directory:

`protontricks -c {{command}} {{appid}}`

- [l]ist all installed games:

`protontricks -l`

- [s]earch for a game's App ID by name:

`protontricks -s {{game_name}}`

- Show the protontricks help message:

`protontricks --help`

