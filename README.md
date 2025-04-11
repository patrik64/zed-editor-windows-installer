# zed-editor-windows-installer
windows installer script for the zed editor

to create the installer (msi file):

- create a [windows release build](https://zed.dev/docs/development/windows)
- copy the wix folder under crates/zed folder
- from the root folder execute:

``cargo wix --package zed``

the resulting installer file will be located in the target/wix folder 
