---
id: common.qdbus
title: Qdbus
desc: ''
updated: 1691594335961
created: 1691594335961
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qdbus

> Inter-Process Communication (IPC) and Remote Procedure Calling (RPC) mechanism originally developed for Linux.
> More information: <https://doc.qt.io/qt-5/qtdbus-index.html>.

- List available service names:

`qdbus`

- List object paths for a specific service:

`qdbus {{service_name}}`

- List methods, signals and properties available on a specific object:

`qdbus {{service_name}} {{/path/to/object}}`

- Execute a specific method passing arguments and display the returned value:

`qdbus {{service_name}} {{/path/to/object}} {{method_name}} {{argument1}} {{argument2}}`

- Display the current brightness value in a KDE Plasma session:

`qdbus {{org.kde.Solid.PowerManagement}} {{/org/kde/Solid/PowerManagement/Actions/BrightnessControl}} {{org.kde.Solid.PowerManagement.Actions.BrightnessControl.brightness}}`

- Set a specific brightness to a KDE Plasma session:

`qdbus {{org.kde.Solid.PowerManagement}} {{/org/kde/Solid/PowerManagement/Actions/BrightnessControl}} {{org.kde.Solid.PowerManagement.Actions.BrightnessControl.setBrightness}} {{5000}}`

- Invoke volume up shortcut in a KDE Plasma session:

`qdbus {{org.kde.kglobalaccel}} {{/component/kmix}} {{invokeShortcut}} "{{increase_volume}}"`

- Gracefully log out and then do nothing, reboot or shut down:

`qdbus {{org.kde.Shutdown}} {{/Shutdown}} {{logout|logoutAndReboot|logoutAndShutdown}}`

