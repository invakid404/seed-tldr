---
id: common.minifab
title: Minifab
desc: ''
updated: 1693073888520
created: 1693073888520
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# minifab

> Utility tool that automates the setup and deployment of Hyperledger Fabric networks.
> More information: <https://github.com/hyperledger-labs/minifabric>.

- Bring up the default Hyperledger Fabric network:

`minifab up -i {{minifab_version}}`

- Bring down the Hyperledger Fabric network:

`minifab down`

- Install chaincode onto a specified channel:

`minifab install -n {{chaincode_name}}`

- Install a specific chaincode version onto a channel:

`minifab install -n {{chaincode_name}} -v {{chaincode_version}}`

- Initialize the chaincode after installation/upgrade:

`minifab approve,commit,initialize,discover`

- Invoke a chaincode method with the specified arguments:

`minifab invoke -n {{chaincode_name}} -p '"{{method_name}}", "{{argument1}}", "{{argument2}}", ...'`

- Make a query on the ledger:

`minifab blockquery {{block_number}}`

- Quickly run an application:

`minifab apprun -l {{app_programming_language}}`

