---
id: windows.test-json
title: Test Json
desc: ''
updated: 1688304045099
created: 1688304045099
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# Test-Json

> Tests whether a string is a valid JSON document.
> This command can only be used through PowerShell.
> More information: <https://learn.microsoft.com/powershell/module/microsoft.powershell.utility/test-json>.

- Test if a string from `stdin` is in JSON format:

`'{{string}}' | Test-Json`

- Test if a string JSON format:

`Test-Json -Json '{{json_to_test}}'`

- Test if a string from `stdin` matches a specific schema file:

`'{{string}}' | Test-Json -SchemaFile {{path\to\schema_file.json}}`

