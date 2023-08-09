---
id: common.rake
title: Rake
desc: ''
updated: 1691565334430
created: 1691565334430
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rake

> A Make-like program for Ruby.
> Tasks for `rake` are specified in a Rakefile.
> More information: <https://ruby.github.io/rake>.

- Run the `default` Rakefile task:

`rake`

- Run a specific task:

`rake {{task}}`

- Execute `n` jobs at a time in parallel (number of CPU cores + 4 by default):

`rake --jobs {{n}}`

- Use a specific Rakefile:

`rake --rakefile {{path/to/Rakefile}}`

- Execute `rake` from another directory:

`rake --directory {{path/to/directory}}`

