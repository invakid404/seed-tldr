---
id: common.kubectl-edit
title: Kubectl Edit
desc: ''
updated: 1683702926117
created: 1683702926117
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kubectl edit

> Edit Kubernetes resources.
> More information: <https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands#edit>.

- Edit a pod:

`kubectl edit pod/{{pod_name}}`

- Edit a deployment:

`kubectl edit deployment/{{deployment_name}}`

- Edit a service:

`kubectl edit svc/{{service_name}}`

- Edit a resource using a specific editor:

`KUBE_EDITOR={{nano}} kubectl edit {{resource}}/{{resource_name}}`

- Edit a resource in JSON format:

`kubectl edit {{resource}}/{{resource_name}} --output json`

