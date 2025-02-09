---
id: linux.read
title: Read
desc: ''
updated: 1688700642070
created: 1688700642070
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# read

> Shell builtin for retrieving data from `stdin`.
> More information: <https://manned.org/read.1p>.

- Store data that you type from the keyboard:

`read {{variable}}`

- Store each of the next lines you enter as values of an array:

`read -a {{array}}`

- Specify the number of maximum characters to be read:

`read -n {{character_count}} {{variable}}`

- Use a specific character as a delimiter instead of a new line:

`read -d {{new_delimiter}} {{variable}}`

- Do not let backslash (\\) act as an escape character:

`read -r {{variable}}`

- Display a prompt before the input:

`read -p "{{Enter your input here: }}" {{variable}}`

- Do not echo typed characters (silent mode):

`read -s {{variable}}`

- Read `stdin` and perform an action on every line:

`while read line; do echo "$line"; done`

