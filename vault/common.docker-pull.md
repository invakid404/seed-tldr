---
id: common.docker-pull
title: Docker Pull
desc: ''
updated: 1678684633347
created: 1678684633347
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# docker pull

> Download Docker images from a registry.
> More information: <https://docs.docker.com/engine/reference/commandline/pull/>.

- Download a specific Docker image:

`docker pull {{image}}:{{tag}}`

- Download a specific Docker image in quiet mode:

`docker pull --quiet {{image}}:{{tag}}`

- Download all tags of a specific Docker image:

`docker pull --all-tags {{image}}`

- Download a Docker images for a specific platform, e.g. linux/amd64:

`docker pull --platform {{linux/amd64}} {{image}}:{{tag}}`

- Display help:

`docker pull --help`

