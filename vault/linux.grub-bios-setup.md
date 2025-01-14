---
id: linux.grub-bios-setup
title: Grub Bios Setup
desc: ''
updated: 1659923836893
created: 1659923836893
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# grub-bios-setup

> Set up a device to use GRUB with a BIOS configuration.
> You should use `grub-install` instead of `grub-bios-setup` in most cases.
> More information: <https://manned.org/grub-bios-setup.8>.

- Set up a device to boot with GRUB:

`grub-bios-setup {{/dev/sdX}}`

- Install even if problems are detected:

`grub-bios-setup --force {{/dev/sdX}}`

- Install GRUB in a specific directory:

`grub-bios-setup --directory={{/boot/grub}} {{/dev/sdX}}`

