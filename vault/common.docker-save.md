---
id: common.docker-save
title: Docker Save
desc: ''
updated: 1670142130899
created: 1670142130899
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# docker save

> Export one or more docker images to archive.
> More information: <https://docs.docker.com/engine/reference/commandline/save/>.

- Save an image by redirecting `stdout` to a tar archive:

`docker save {{image}}:{{tag}} > {{path/to/file.tar}}`

- Save an image to a tar archive:

`docker save --output {{path/to/file.tar}} {{image}}:{{tag}}`

- Save all tags of the image:

`docker save --output {{path/to/file.tar}} {{image_name}}`

- Cherry-pick particular tags of an image to save:

`docker save --output {{path/to/file.tar}} {{image_name:tag1 image_name:tag2 ...}}`

