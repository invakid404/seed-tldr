---
id: common.skopeo
title: Skopeo
desc: ''
updated: 1665415810262
created: 1665415810262
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# skopeo

> Container image management toolbox.
> Provides various utility commands to manage remote container images.
> More information: <https://github.com/containers/skopeo>.

- Inspect a remote image from a registry:

`skopeo inspect docker://{{registry_hostname}}/{{image:tag}}`

- List available tags for a remote image:

`skopeo list-tags docker://{{registry_hostname}}/{{image}}`

- Download an image from a registry:

`skopeo copy docker://{{registry_hostname}}/{{image:tag}} dir:{{path/to/directory}}`

- Copy an image from one registry to another:

`skopeo copy docker://{{source_registry}}/{{image:tag}} docker://{{destination_registry}}/{{image:tag}}`

- Delete an image from a registry:

`skopeo delete docker://{{registry_hostname}}/{{image:tag}}`

- Log in to a registry:

`skopeo login --username {{username}} {{registry_hostname}}`

