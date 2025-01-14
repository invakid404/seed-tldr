---
id: common.aws-backup
title: Aws Backup
desc: ''
updated: 1671265249792
created: 1671265249792
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# aws backup

> Unified backup service designed to protect Amazon Web Services services and their associated data.
> More information: <https://docs.aws.amazon.com/cli/latest/reference/backup/index.html>.

- Return BackupPlan details for a specific BackupPlanId:

`aws backup get-backup-plan --backup-plan-id {{id}}`

- Create a backup plan using a specific backup plan name and backup rules:

`aws backup create-backup-plan --backup-plan {{plan}}`

- Delete a specific backup plan:

`aws backup delete-backup-plan --backup-plan-id {{id}}`

- Return a list of all active backup plans for the current account:

`aws backup list-backup-plans`

- Display details about your report jobs:

`aws backup list-report-jobs`

