---
id: common.verilator
title: Verilator
desc: ''
updated: 1669451017752
created: 1669451017752
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# verilator

> Converts Verilog and SystemVerilog hardware description language (HDL) designs into a C++ or SystemC model that after compiling can be executed.
> More information: <https://veripool.org/guide/latest/>.

- Build a specific C project in the current directory:

`verilator --binary --build-jobs 0 -Wall {{path/to/source.v}}`

- Create a C++ executable in a specific folder:

`verilator --cc --exe --build --build-jobs 0 -Wall {{path/to/source.cpp}} {{path/to/output.v}}`

- Perform linting over a code in the current directory:

`verilator --lint-only -Wall`

- Create XML output about the design (files, modules, instance hierarchy, logic and data types) to feed into other tools:

`verilator --xml-output -Wall {{path/to/output.xml}}`

