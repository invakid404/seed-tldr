---
id: linux.mpicc
title: Mpicc
desc: ''
updated: 1681355859567
created: 1681355859567
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mpicc

> Open MPI C wrapper compiler.
> The wrappers are simply thin shells on top of a C compiler, they add the relevant compiler and linker flags to the command line that are necessary to compile/link Open MPI programs, and then invoke the underlying C compiler to actually perform the command.
> More information: <https://www.mpich.org/static/docs/latest/www1/mpicc.html>.

- Compile a source code file into an object file:

`mpicc -c {{path/to/file.c}}`

- Link an object file and make an executable:

`mpicc -o {{executable}} {{path/to/object_file.o}}`

- Compile and link source code in a single command:

`mpicc -o {{executable}} {{path/to/file.c}}`

