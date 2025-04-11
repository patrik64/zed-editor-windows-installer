# zed-editor-windows-installer
windows installer script for the zed editor

to create the installer (msi file):

- create the [windows release build](https://zed.dev/docs/development/windows)
- copy the above wix folder to crates/zed folder of the zed editor project
- from the zed editor root folder execute:

``cargo wix --package zed``

the resulting installer file will be located in the target/wix folder 
