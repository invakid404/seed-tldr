---
id: linux.curlie
title: Curlie
desc: ''
updated: 1664613092237
created: 1664613092237
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# curlie

> Curlie is a frontend to curl that adds the ease of use of httpie.
> More information: <https://github.com/rs/curlie>.

- Send a GET request:

`curlie {{httpbin.org/get}}`

- Send a POST request:

`curlie post {{httpbin.org/post}} {{name=john}} {{age:=25}}`

- Send a GET request with query parameters (e.g. `first_param=5&second_param=true`):

`curlie get {{httpbin.org/get}} {{first_param==5}} {{second_param==true}}`

- Send a GET request with a custom header:

`curlie get {{httpbin.org/get}} {{header-name:header-value}}`

