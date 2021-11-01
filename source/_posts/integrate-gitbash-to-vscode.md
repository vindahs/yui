---
title: Integrate Gitbash to VS Code
date: 2021-09-02 19:13:36
tags:
---


integrate gitbash command line interface to visual studio code in simple steps.

## Open VS code and select settings through file > Preferences

``` bash
$ File > preferences > settings
```



### Open terminal through features tab

``` bash
$ features > terminal
```

### Scroll to integrated > automation shell: windows and click Edit in settings.json

``` bash
$ integrated > automation shell: windows > click Edit in settings.json
```


### Paste in the command below

``` bash
$ { 
    "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
    "files.autoSave": "afterDelay",
    "terminal.integrated.automationShell.windows": "",
}
```

### Restart VS code

