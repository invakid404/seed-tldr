---
id: common.eksctl
title: Eksctl
desc: ''
updated: 1681982195628
created: 1681982195628
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# eksctl

> The official CLI for Amazon EKS.
> More information: <https://eksctl.io>.

- Create a basic cluster:

`eksctl create cluster`

- List the details about a cluster or all of the clusters:

`eksctl get cluster --name={{name}} --region={{region}}`

- Create a cluster passing all configuration information in a file:

`eksctl create cluster --config-file={{path/to/file}}`

- Create a cluster using a configuration file and skip creating nodegroups until later:

`eksctl create cluster --config-file=<path> --without-nodegroup`

- Delete a cluster:

`eksctl delete cluster --name={{name}} --region={{region}}`

- Create cluster and write cluster credentials to a file other than the default:

`eksctl create cluster --name={{name}} --nodes={{4}} --kubeconfig={{path/to/config.yaml}}`

- Create a cluster and prevent storing cluster credentials locally:

`eksctl create cluster --name={{name}} --nodes={{4}} --write-kubeconfig=false`

- Create a cluster and let `eksctl` manage cluster credentials under the `~/.kube/eksctl/clusters` directory:

`eksctl create cluster --name={{name}} --nodes={{4}} --auto-kubeconfig`

