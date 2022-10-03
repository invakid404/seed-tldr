---
id: common.docker-load
title: Docker Load
desc: ''
updated: 1664769727574
created: 1664769727574
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# docker load

> Load Docker images from files or stdin.
> More information: <https://docs.docker.com/engine/reference/commandline/load/>.

- Load a Docker image from stdin:

`docker load < {{path/to/image_file.tar}}`

- Load a Docker image from a specific file:

`docker load --input {{path/to/image_file.tar}}`

- Load a Docker image from a specific file in quiet mode:

`docker load --quiet --input {{path/to/image_file.tar}}`

