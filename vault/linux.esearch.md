---
id: linux.esearch
title: Esearch
desc: ''
updated: 1665585710858
created: 1665585710858
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# esearch

> Perform a new Entrez search using terms in indexed fields.
> It is part of the `edirect` package.
> More information: <https://www.ncbi.nlm.nih.gov/books/NBK179288/>.

- Search the pubmed database for selective serotonin reuptake inhibitor:

`esearch -db pubmed -query "{{selective serotonin reuptake inhibitor}}"`

- Search the nucleotide database for sequences whose metadata contain insulin and rodents:

`esearch -db nuccore -query "{{insulin [PROT] AND rodents [ORGN]}}"`

