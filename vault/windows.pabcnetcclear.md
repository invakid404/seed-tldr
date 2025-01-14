---
id: windows.pabcnetcclear
title: Pabcnetcclear
desc: ''
updated: 1676881477680
created: 1676881477680
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pabcnetcclear

> Preprocess and compile PascalABC.NET source files.
> More information: <http://pascalabc.net>.

- Compile the specified source file into an executable with the same name:

`pabcnetcclear {{path\to\source_file.pas}}`

- Compile the specified source file into an executable with the specified name:

`pabcnetcclear /Output:{{path\to\_file.exe}} {{path\to\source_file.pas}}`

- Compile the specified source file into an executable with the same name along with/without debug information:

`pabcnetcclear /Debug:{{0|1}} {{path\to\source_file.pas}}`

- Allow units to be searched in the specified path while compiling the source file into an executable with the same name:

`pabcnetcclear /SearchDir:{{path\to\directory}} {{path\to\source_file.pas}}`

- Compile the specified source file into an executable, defining a symbol:

`pabcnetcclear /Define:{{symbol}} {{path\to\source_file.pas}}`

