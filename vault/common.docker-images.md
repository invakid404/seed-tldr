---
id: common.docker-images
title: Docker Images
desc: ''
updated: 1689488527775
created: 1689488527775
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# docker images

> Manage Docker images.
> More information: <https://docs.docker.com/engine/reference/commandline/images/>.

- List all Docker images:

`docker images`

- List all Docker images including intermediates:

`docker images --all`

- List the output in quiet mode (only numeric IDs):

`docker images --quiet`

- List all Docker images not used by any container:

`docker images --filter dangling=true`

- List images that contain a substring in their name:

`docker images "{{*name*}}"`

- Sort images by size:

`docker images --format "{{.ID}}\t{{.Size}}\t{{.Repository}}:{{.Tag}}" | sort -k 2 -h`

