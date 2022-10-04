---
id: common.az-storage-blob
title: Az Storage Blob
desc: ''
updated: 1664897373956
created: 1664897373956
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# az storage blob

> Manage blob storage containers and objects in Azure.
> Part of `azure-cli`.
> More information: <https://learn.microsoft.com/cli/azure/storage/blob>.

- Download a blob to a file path:

`az storage blob download --account-name {{storage_account_name}} --account-key {{storage_account_key}} -c {{container_name}} -n {{path/to/blob}} -f {{path/to/local_file}}`

- Download blobs from a blob container recursively:

`az storage blob download-batch --account-name {{storage_account_name}} --account-key {{storage_account_key}} -s {{container_name}} -d {{path/to/remote}} --pattern {{filename_regex}} --destination {{path/to/destination}}`

- Upload a local file to blob storage:

`az storage blob upload --account-name {{storage_account_name}} --account-key {{storage_account_key}} -c {{container_name}} -n {{path/to/blob}} -f {{path/to/local_file}}`

- Delete a blob object:

`az storage blob delete --account-name {{storage_account_name}} --account-key {{storage_account_key}} -c {{container_name}} -n {{path/to/blob}}`

- Generate a shared access signature for a blob:

`az storage blob generate-sas --account-name {{storage_account_name}} --account-key {{storage_account_key}} -c {{container_name}} -n {{path/to/blob}} --permissions {{permission_set}} --expiry {{Y-m-d'T'H:M'Z'}} --https-only`

