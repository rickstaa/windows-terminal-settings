# windows-terminal-settings profiles.json file backup

A backup repository I created to be able share my windows-terminal setup across machines while keeping track of any changes I made.

## Installation

### Dependencies
This windows terminal setup requires the following packages and fonts:

- [Roboto Mono regular font](https://fonts.google.com/specimen/Roboto+Mono?selection.family=Roboto+Mono:100,100i,300,300i,400,400i,500,500i,700,700i)

### Installation instructions
If you installed the dependencies you can install my .tmux configuration by running the following commands in the windows command prompt:

```PowerShell
cd
git clone https://github.com/rickstaa/windows-terminal-settings
cd windows-terminal-settings
copy C:\Users\<USER_NAME>\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\profiles.json C:\Users\<USER_NAME>\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\profiles.json.bak
rmdir C:\Users\<USER_NAME>\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\profiles.json
mklink /H C:\Users\<USER_NAME>\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\profiles.json profiles.json
```
