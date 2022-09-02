---
id: common.task
title: Task
desc: ''
updated: 1662085258463
created: 1662085258463
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# task

> Command-line to-do list manager.
> More information: <https://taskwarrior.org/docs/>.

- Add a new task which is due tomorrow:

`task add {{description}} due:{{tomorrow}}`

- Update a task's priority:

`task {{task_id}} modify priority:{{H|M|L}}`

- Complete a task:

`task {{task_id}} done`

- Delete a task:

`task {{task_id}} delete`

- List all open tasks:

`task list`

- List open tasks due before the end of the week:

`task list due.before:{{eow}}`

- Show a graphical burndown chart, by day:

`task burndown.daily`

- List all reports:

`task reports`

