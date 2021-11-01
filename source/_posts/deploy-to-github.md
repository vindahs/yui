---
title: Deploy Your Website on Github in Mins.
date: 2021-09-03 19:12:20
tags:
---

Deploy your website to github in minutes to avoid loosing progress made in your project and to easily interact with with team or organization, to deploy your website on [github](https://github.com/join/), first you need to signup a github account if you dont have one.

## Create a new git repository


``` bash
$ Click on new repositories, then enter folder name and select if you want it to be a public or private project, the click create repository.
```

### Initialize a git repository throuh your command line interface

``` bash
$ git init
```

### Add projects on the directory

``` bash
$ git add .
```


### Commit current project

``` bash
$ git commit -m "first commit"
```

### Connect to your github address remotely

``` bash
$ git remote add origin https://github.com/vindahs/NAME-OF-REPOSITORY.git
```

### Deploy

``` bash
$ git push -u origin master
```
