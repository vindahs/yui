---
title: Create A Node JS Blog Website In Mins Using Hexo
date: 2021-09-03 19:55:56
tags:
---

Hexo is a simple yet powerful framework for generating static websites, Dont spend much time on figuring out how to organize authentication and databases, while having very little time to actually write. To proceed you need to install some softwares such as [Visual studio code](https://code.visualstudio.com/Download/), [node js](https://nodejs.org/dist/v10.18.0/node-v10.18.0-x64.msi/) and [git bash](https://github.com/git-for-windows/git/releases/download/v2.33.0.windows.2/Git-2.33.0.2-64-bit.exe). The next step after installing those will be to integrate gitbash to VS code.

## Crete project folder

### Create a root folder from vs code git bash cli by typing following command on the terminal

``` bash
$ mkdir folder name
```

### Enter into your project path

``` bash
$ cd folder
```

## Install Hexo through command line interface using npm

``` bash
$ npm install -g hexo
```

### Create your blog, this will initialize a repository with a default Hexo website

``` bash
$ hexo init blog
```

### Enter blog directory and run server and open in browser to view blog by typing these commands

``` bash
$ cd blog
```
``` bash
$ hexo server
```
``` bash
$ copy http://localhost:4000/ and open in browser
```


