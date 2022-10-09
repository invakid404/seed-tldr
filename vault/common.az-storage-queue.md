---
id: common.az-storage-queue
title: Az Storage Queue
desc: ''
updated: 1665294081710
created: 1665294081710
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# az storage queue

> Manage storage queues in Azure.
> Part of `azure-cli`.
> More information: <https://learn.microsoft.com/cli/azure/storage/queue>.

- Create a queue:

`az storage queue create --account-name {{storage_account_name}} --name {{queue_name}} --metadata {{queue_metadata}}`

- Generate a shared access signature for the queue:

`az storage queue generate-sas --account-name {{storage_account_name}} --name {{queue_name}} --permissions {{queue_permissions}} --expiry {{expiry_date}} --https-only`

- List queues in a storage account:

`az storage queue list --prefix {{filter_prefix}} --account-name {{storage_account_name}}`

- Delete the specified queue and any messages it contains:

`az storage queue delete --account-name {{storage_account_name}} --name {{queue_name}} --fail-not-exist`

