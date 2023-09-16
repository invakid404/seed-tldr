---
id: common.linode-cli-object-storage
title: Linode CLI Object Storage
desc: ''
updated: 1694898750775
created: 1694898750775
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# linode-cli object-storage

> Manage Linode Object Storage.
> See also: `linode-cli`.
> More information: <https://www.linode.com/docs/products/tools/cli/guides/object-storage/>.

- List all Object Storage buckets:

`linode-cli object-storage buckets list`

- Create a new Object Storage bucket:

`linode-cli object-storage buckets create --cluster {{cluster_id}} --label {{bucket_label}}`

- Delete an Object Storage bucket:

`linode-cli object-storage buckets delete {{cluster_id}} {{bucket_label}}`

- List Object Storage cluster regions:

`linode-cli object-storage clusters list`

- List access keys for Object Storage:

`linode-cli object-storage keys list`

- Create a new access key for Object Storage:

`linode-cli object-storage keys create --label {{label}}`

- Revoke an access key for Object Storage:

`linode-cli object-storage keys revoke {{access_key_id}}`

