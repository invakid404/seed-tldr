---
id: linux.cp
title: Cp
desc: ''
updated: 1681107675515
created: 1681107675515
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cp

> Copy files and directories.
> More information: <https://www.gnu.org/software/coreutils/cp>.

- Copy a file to another location:

`cp {{path/to/source_file.ext}} {{path/to/target_file.ext}}`

- Copy a file into another directory, keeping the filename:

`cp {{path/to/source_file.ext}} {{path/to/target_parent_directory}}`

- Recursively copy a directory's contents to another location (if the destination exists, the directory is copied inside it):

`cp -r {{path/to/source_directory}} {{path/to/target_directory}}`

- Copy a directory recursively, in verbose mode (shows files as they are copied):

`cp -vr {{path/to/source_directory}} {{path/to/target_directory}}`

- Copy multiple files at once to a directory:

`cp -t {{path/to/destination_directory}} {{path/to/file1 path/to/file2 ...}}`

- Copy text files to another location, in interactive mode (prompts user before overwriting):

`cp -i {{*.txt}} {{path/to/target_directory}}`

- Follow symbolic links before copying:

`cp -L {{link}} {{path/to/target_directory}}`

- Use the full path of source files, creating any missing intermediate directories when copying:

`cp --parents {{source/path/to/file}} {{path/to/target_file}}`

