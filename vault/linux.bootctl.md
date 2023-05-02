---
id: linux.bootctl
title: Bootctl
desc: ''
updated: 1683022666221
created: 1683022666221
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bootctl

> Control EFI firmware boot settings and manage boot loader.
> More information: <https://manned.org/bootctl>.

- Show information about the system firmware and the bootloaders:

`bootctl status`

- Show all available bootloader entries:

`bootctl list`

- Set a flag to boot into the system firmware on the next boot (similar to `sudo systemctl reboot --firmware-setup`):

`sudo bootctl reboot-to-firmware true`

- Specify the path to the EFI system partition (defaults to `/efi/`, `/boot/` or `/boot/efi`):

`bootctl --esp-path={{/path/to/efi_system_partition/}}`

- Install `systemd-boot` into the EFI system partition:

`sudo bootctl install`

- Remove all installed versions of `systemd-boot` from the EFI system partition:

`sudo bootctl remove`

