---
id: linux.cat
title: Cat
desc: ''
updated: 1691562059132
created: 1691562059132
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cat

> Print and concatenate files.
> More information: <https://www.gnu.org/software/coreutils/cat>.

- Print the contents of a file to `stdout`:

`cat {{path/to/file}}`

- Concatenate several files into an output file:

`cat {{path/to/file1 path/to/file2 ...}} > {{path/to/output_file}}`

- Append several files to an output file:

`cat {{path/to/file1 path/to/file2 ...}} >> {{path/to/output_file}}`

- Copy the contents of a file into an output file in [u]nbuffered mode:

`cat -u {{/dev/tty12}} > {{/dev/tty13}}`

- Write `stdin` to a file:

`cat - > {{path/to/file}}`

- [n]umber all output lines:

`cat -n {{path/to/file}}`

- Display non-printable and whitespace characters (with `M-` prefix if non-ASCII):

`cat -v -t -e {{path/to/file}}`

