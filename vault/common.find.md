---
id: common.find
title: Find
desc: ''
updated: 1690474846408
created: 1690474846408
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# find

> Find files or directories under the given directory tree, recursively.
> More information: <https://manned.org/find>.

- Find files by extension:

`find {{root_path}} -name '{{*.ext}}'`

- Find files matching multiple path/name patterns:

`find {{root_path}} -path '{{**/path/**/*.ext}}' -or -name '{{*pattern*}}'`

- Find directories matching a given name, in case-insensitive mode:

`find {{root_path}} -type d -iname '{{*lib*}}'`

- Find files matching a given pattern, excluding specific paths:

`find {{root_path}} -name '{{*.py}}' -not -path '{{*/site-packages/*}}'`

- Find files matching a given size range, limiting the recursive depth to "1":

`find {{root_path}} -maxdepth 1 -size {{+500k}} -size {{-10M}}`

- Run a command for each file (use `{}` within the command to access the filename):

`find {{root_path}} -name '{{*.ext}}' -exec {{wc -l {} }}\;`

- Find files modified in the last 7 days:

`find {{root_path}} -daystart -mtime -{{7}}`

- Find empty (0 byte) files and delete them:

`find {{root_path}} -type {{f}} -empty -delete`

