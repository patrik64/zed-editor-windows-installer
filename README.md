# zed-editor-windows-installer
windows installer script for the [zed editor](https://zed.dev/)

to create the installer (msi file):

- install [cargo-wix](https://github.com/volks73/cargo-wix) subcommand : ``cargo install cargo-wix``
- install the [wix 3.14 toolset](https://github.com/wixtoolset/wix3/releases)
- create the [zed editor windows release build](https://zed.dev/docs/development/windows)
- copy the above ``wix`` folder to ``crates/zed`` folder of the zed editor project
- from the zed editor root folder execute:

``cargo wix --package zed``

the resulting installer (msi) file will be located in the ``target/wix`` folder:

<br/>
<p align="center">
<img src="https://github.com/user-attachments/assets/640b1ef7-9863-463f-936c-bcb3477ae9ee" width="700" />
</p>
<br/>

the following are screenshots of the activated installer:

<br/>
<p align="center">
<img src="https://github.com/user-attachments/assets/3317ae9c-2811-492d-8533-981fee8a40f7" width="500" />
</p>
<br/>

<br/>
<p align="center">
<img src="https://github.com/user-attachments/assets/8de5f486-e6cc-4b3d-a610-e65cd160387e" width="500" />
</p>
<br/>

<br/>
<p align="center">
<img src="https://github.com/user-attachments/assets/3a93fe89-f471-4656-b276-7191f6400f69" width="500" />
</p>
<br/>

<br/>
<p align="center">
<img src="https://github.com/user-attachments/assets/d6722d88-29dd-4784-83af-c8bc1c797ebb" width="500" />
</p>
<br/>

and the resulting Apps item:

<br/>
<p align="center">
<img src="https://github.com/user-attachments/assets/5219b005-b9c2-4454-959a-30103cf710ab" width="800" />
</p>
<br/>


zed editor running on windows:

![image](https://github.com/user-attachments/assets/f718059b-2bfd-4870-8f8f-0aa32f6e923c)


