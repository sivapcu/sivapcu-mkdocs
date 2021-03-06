This page contains tips related to [Visual Studio Code](https://code.visualstudio.com/) IDE.
<center>![Powershell](../img/blog/vscode/vscode.png)</center>
## Integrated Terminal

### Short Cuts
* To perform a search throughout the project, use the short cut _Ctrl + p_
* To quickly open the terminal use the short cut _Ctrl + `_
* To open additional terminal use the short cut _Ctrl + Shift + `_

### Working with Multiple Projects in Same Window
Many of the times, we want to work on multiple projects or we want to refer to refer to an existing project. But when we use _File -> Open Folder..._ the existing project is replaced with the newly selected folder in the VS Code window. Else we have use _File -> New Window_ to open new window and open the other project in that window. To avoid this and work on multiple projects in the same window use the option _File -> Add Folder to Workspace..._ 

### Change from powershell.exe to cmd.exe
Before Windows 10, the default Integrated Terminal provides cmd.exe. But in Windows 10, the default program is changed to powershell.exe. 

<center>![Powershell](../img/blog/vscode/powershell.png)</center>

If you want to change it back to cmd.exe just like me, then follow the following actions

1. Navigate to _File -> Prefrences -> Settings._ This will open the `settings.json` in the editor.
2. Select user settings in the editor
3. Add the following variables in the json as shown in the image below. 
    `"terminal.integrated.shell.windows": "cmd.exe"`
<center>![shell-settings](../img/blog/vscode/shell-settings.png)</center>
4. Now open the terminal using the shortcut Ctrl + `
<center>![cmd](../img/blog/vscode/cmd.png)</center>


## Proxy Settings
1. Navigate to File -> Prefrences -> Settings. This will open the `settings.json` in the editor.
2. Select user settings in the editor
3. Add the following variables in the json as shown in the image below.

    _"http.proxy": "http://username:password@proxyip:proxyport/"_

    _"http.proxyStrictSSL": false_
<center>![ProxySettings](../img/blog/vscode/proxy.png)</center>
