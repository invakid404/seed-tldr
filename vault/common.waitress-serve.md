---
id: common.waitress-serve
title: Waitress Serve
desc: ''
updated: 1658926036849
created: 1658926036849
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# waitress-serve

> Pure Python WSGI HTTP Server.
> More information: <https://docs.pylonsproject.org/projects/waitress/en/latest/runner.html>.

- Run a Python web app:

`waitress-serve {{import.path:wsgi_func}}`

- Listen on port 8080 on localhost:

`waitress-serve --listen={{localhost}}:{{8080}} {{import.path:wsgi_func}}`

- Start waitress on a Unix socket:

`waitress-serve --unix-socket={{path/to/socket}} {{import.path:wsgi_func}}`

- Use 4 threads to process requests:

`waitress-serve --threads={{4}} {{import.path:wsgifunc}}`

- Call a factory method that returns a WSGI object:

`waitress-serve --call {{import.path.wsgi_factory}}`

- Set the URL scheme to HTTPS&#x3A;

`waitress-serve --url-scheme={{https}} {{import.path:wsgi_func}}`

