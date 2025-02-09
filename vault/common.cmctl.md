---
id: common.cmctl
title: Cmctl
desc: ''
updated: 1689531679526
created: 1689531679526
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cmctl

> Manage cert-manager resources inside your cluster.
> Check cert signing status, approve/deny requests, and issue new certificate requests.
> More information: <https://cert-manager.io/docs/usage/cmctl/>.

- Check if the cert-manager API is ready:

`cmctl check api`

- Check the status of a certificate:

`cmctl status certificate {{cert_name}}`

- Create a new certificate request based on an existing certificate:

`cmctl create certificaterequest my-cr --from-certificate-file {{cert.yaml}}`

- Create a new certificate request, fetch the signed certificate, and set a maximum wait time:

`cmctl create certificaterequest my-cr --from-certificate-file {{cert.yaml}} --fetch-certificate --timeout {{20m}}`

