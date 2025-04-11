# zed-editor-windows-installer
windows installer script for the zed editor

to create the installer (msi file), copy the wix folder under crates/zed folder and from the root folder execute:

``cargo wix --package zed``

the resulting installer file will be located in the target/wix folder 
