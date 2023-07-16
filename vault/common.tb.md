---
id: common.tb
title: Tb
desc: ''
updated: 1689531679734
created: 1689531679734
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tb

> Manage tasks and notes across multiple boards.
> More information: <https://github.com/klaussinani/taskbook>.

- Add a new task to a board:

`tb --task {{task_description}} @{{board_name}}`

- Add a new note to a board:

`tb --note {{note_description}} @{{board_name}}`

- Edit item's priority:

`tb --priority @{{item_id}} {{priority}}`

- Check/uncheck item:

`tb --check {{item_id}}`

- Archive all checked items:

`tb --clear`

- Move item to a board:

`tb --move @{{item_id}} {{board_name}}`

