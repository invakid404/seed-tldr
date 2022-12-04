---
id: common.make
title: Make
desc: ''
updated: 1670145407011
created: 1670145407011
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# make

> Task runner for targets described in Makefile.
> Mostly used to control the compilation of an executable from source code.
> More information: <https://www.gnu.org/software/make/manual/make.html>.

- Call the first target specified in the Makefile (usually named "all"):

`make`

- Call a specific target:

`make {{target}}`

- Call a specific target, executing 4 jobs at a time in parallel:

`make -j{{4}} {{target}}`

- Use a specific Makefile:

`make --file {{path/to/file}}`

- Execute make from another directory:

`make --directory {{path/to/directory}}`

- Force making of a target, even if source files are unchanged:

`make --always-make {{target}}`

- Override a variable defined in the Makefile:

`make {{target}} {{variable}}={{new_value}}`

- Override variables defined in the Makefile by the environment:

`make --environment-overrides {{target}}`

