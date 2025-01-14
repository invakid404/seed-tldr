---
id: linux.grub-script-check
title: Grub Script Check
desc: ''
updated: 1691562059148
created: 1691562059148
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# grub-script-check

> The program `grub-script-check` takes a GRUB script file and checks it for syntax errors.
> It may take a path as a non-option argument. If none is supplied, it will read from `stdin`.
> More information: <https://www.gnu.org/software/grub/manual/grub/html_node/Invoking-grub_002dscript_002dcheck.html>.

- Check a specific script file for syntax errors:

`grub-script-check {{path/to/grub_config_file}}`

- Display each line of input after reading it:

`grub-script-check --verbose`

- Display version:

`grub-script-check --version`

- Display help:

`grub-script-check --help`

