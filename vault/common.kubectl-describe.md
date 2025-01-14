---
id: common.kubectl-describe
title: Kubectl Describe
desc: ''
updated: 1665588712619
created: 1665588712619
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kubectl describe

> Show details of Kubernetes objects and resources.
> More information: <https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands#describe>.

- Show details of pods in a namespace:

`kubectl describe pods -n {{namespace}}`

- Show details of nodes in a namespace:

`kubectl describe nodes -n {{namespace}}`

- Show the details of a specific pod in a namespace:

`kubectl describe pods {{pod_name}} -n {{namespace}}`

- Show the details of a specific node in a namespace:

`kubectl describe nodes {{node_name}} -n {{namespace}}`

- Show details of Kubernetes objects defined in a YAML manifest:

`kubectl describe -f {{path/to/manifest.yaml}}`

