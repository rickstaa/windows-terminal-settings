# windows-terminal-settings profiles.json file backup

A backup repository I created to be able share my windows-terminal setup across machines while keeping track of any changes I made.

## Installation

### Installation instructions
If you installed the dependencies you can install my .tmux configuration by running the following commands in your terminal:

```
> cd
> git clone https://github.com/rickstaa/windows-terminal-settings
> cd windows-terminal-settings
> copy C:\Users\<USER_NAME>\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\profiles.json C:\Users\<USER_NAME>\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\profiles.json.bak
> mklink C:\Users\<USER_NAME>\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\profiles.json profiles.json
```
