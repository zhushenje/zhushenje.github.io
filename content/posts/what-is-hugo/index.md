+++
title = "渐变魔方介绍"
date = "2022-02-03"
+++

鲁比克公司是目前世界上最大的魔方制造与销售公司，名称鲁比克源自魔方的发明人，匈牙利建筑学教授Erno Rubik。这款渐变魔方是我心目中鲁比克公司最为成功的产品。通常常见的魔方都是一面一种颜色，而这款魔方采用的是3D光栅打印技术，使得魔方的贴片在经过角度倾斜之后能够变换成为另一种颜色，这使得还原这个魔方变得十分困难，因此被称作不可能魔方。

<!--more-->

## Assumptions

This contribution guide takes a step-by-step approach in hopes of helping newcomers. Therefore, we only assume the following:

* You are new to Git or open-source projects in general
* You are a fan of Hugo and enthusiastic about contributing to the project

## Install Go

The installation of Go should take only a few minutes. You have more than one option to get Go up and running on your machine.

If you are having trouble following the installation guides for Go, check out Go Bootcamp, which contains setups for every platform  or reach out to the Hugo community in the Hugo Discussion Forums.

### Install Go From Source

Download the latest stable version of Go and follow the official Go installation guide.

Once you're finished installing Go, let's confirm everything is working correctly. Open a terminal---or command line under Windows--and type the following:

```
go version
```

You should see something similar to the following written to the console. Note that the version here reflects the most recent version of Go as of the last update for this page:

```
go version go1.12 darwin/amd64
```

Next, make sure that you set up your `GOPATH` as described in the installation guide.

You can print the `GOPATH` with `echo $GOPATH`. You should see a non-empty string containing a valid path to your Go workspace; for example:

```
/Users/<yourusername>/Code/go
```
