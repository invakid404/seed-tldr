---
id: common.cat
title: Cat
desc: ''
updated: 1664619989582
created: 1664619989582
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

- Print the contents of a file to the standard output:

`cat {{path/to/file}}`

- Concatenate several files into an output file:

`cat {{path/to/file1}} {{path/to/file2}} > {{path/to/output_file}}`

- Append several files into an output file:

`cat {{path/to/file1}} {{path/to/file2}} >> {{path/to/output_file}}`

- Number all output lines:

`cat -n {{path/to/file}}`

- Display non-printable and whitespace characters (with `M-` prefix if non-ASCII):

`cat -v -t -e {{path/to/file}}`

