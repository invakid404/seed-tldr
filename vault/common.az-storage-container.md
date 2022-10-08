---
id: common.az-storage-container
title: Az Storage Container
desc: ''
updated: 1665264153070
created: 1665264153070
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# az storage container

> Manage blob storage containers in Azure.
> Part of `azure-cli`.
> More information: <https://learn.microsoft.com/cli/azure/storage/container>.

- Create a container in a storage account:

`az storage container create --account-name {{storage_account_name}} --name {{container_name}} --public-access {{access_level}} --fail-on-exist`

- Generate a shared access signature for the container:

`az storage container generate-sas --account-name {{storage_account_name}} --name {{container_name}} --permissions {{sas_permissions}} --expiry {{expiry_date}} --https-only`

- List containers in a storage account:

`az storage container list --account-name {{storage_account_name}} --prefix {{filter_prefix}}`

- Mark the specified container for deletion:

`az storage container delete --account-name {{storage_account_name}} --name {{container_name}} --fail-not-exist`

