---
id: common.shuf
title: Shuf
desc: ''
updated: 1670310991868
created: 1670310991868
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# shuf

> Generate random permutations.
> More information: <https://www.gnu.org/software/coreutils/shuf>.

- Randomize the order of lines in a file and output the result:

`shuf {{path/to/file}}`

- Only output the first 5 entries of the result:

`shuf --head-count={{5}} {{path/to/file}}`

- Write the output to another file:

`shuf {{path/to/input}} --output={{path/to/output}}`

- Generate 3 random numbers in the range 1-10 (inclusive):

`shuf --head-count={{3}} --input-range={{1-10}} --repeat`

